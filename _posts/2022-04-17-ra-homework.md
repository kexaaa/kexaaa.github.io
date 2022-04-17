---
title: Egorov 定理中的条件 $$ m(E) < + \infty $$ 能否去掉
tags: RA
---

习题 21

<!--more-->

---



设 $$ E = [0,+\infty] \subset \mathbb{R} $$ 考虑 $$ E $$ 上的特征函数列 $$ f_n(x) = \chi_{[n,n+1]}(x), n \in \mathbb{N}$$.

$$ \forall x, \forall \epsilon > 0, \exists N = [x], \forall n > N, n > x$$, 故 $$ f_n(x) = 0 < \epsilon, f_n(x) $$处处收敛到 0.

$$ \forall \delta > 0 $$ 为正常数, 设 $$ f_n(x) $$ 在可测集  $$ E_\delta \subset E$$ 上一致收敛到 0. 

假设$$ m(E_\delta) = + \infty $$, 则显然 $$ E_\delta $$无上界.
取 $$ \epsilon \in (0,1), \forall N $$, 总有 $$ x \in E_\delta $$且 $$ x > N + 1 $$, 因此存在 $$ n = [x] > N $$,但是 $$ f_n(x) = 1 > \epsilon$$, 与 $$ f_n(x) $$ 在  $$ E_\delta $$ 上一致收敛到 0 矛盾, 因此必有 $$ m(E_\delta) < +\infty$$.

故 $$ m(E - E_\delta) = m(E) - m(E_\delta) = + \infty > \delta$$.

换言之, $$f_n(x)$$ 在 $$ E $$上处处收敛到 $$ 0 $$, 但是去掉 $$ E $$ 的任何有限测度子集, 在剩下的子集上$$f_n(x)$$都不是处处收敛的, 因此说明 Egorov 定理中 $$ m(E) < + \infty $$ 的条件是必要的.