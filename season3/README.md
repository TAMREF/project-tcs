# Abstracts

## Finding diverse solutions of combinatorial problems (TAMREF)

### Korean

대부분 combinatorial (optimization) problem은 조건을 만족하는 (가장 좋은) 구조를 하나 찾아내는 것에 치중합니다. (Spanning Tree, Path, Subgraph, ...) Real-world instance에서는 가능한 다양한 해를 찾아야 하는 경우가 생기고, 많은 경우에 top-k solution을 보는 방법을 사용하기도 합니다. 하지만 대부분의 top-k solution은 구조상 큰 차이가 없어, 정말로 "다양한" 해를 만드는 방법은 아직 잘 모릅니다.
이 발표에서는 두 가지 diversity measure를 정의하고, 그를 최적화하는 matroid base problem, k-path problem을 비롯한 다양한 문제에 대한 FPT-solution을 알아봅니다. 이를 바탕으로, "colorful solution"을 찾는 문제를 어떻게 diversity maximization problem으로 변환할 수 있는지도 알아봅니다.
kw: combinatorial optimization, matroid, color coding

### English

Beyond mere optimization problems, we face many occasions where we need to generate multiple combinatorial instances near the optimum. Classical methods such as "top k best solutions" work well, but they often suffer from a lack of diversity. We define the concept of "diversity" using some basic measures, and investigate related polynomial-time and fixed-parameter tractable algorithms.

kw: combinatorial optimization, matroid, color coding
