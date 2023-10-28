# Abstracts

## Finding diverse solutions of combinatorial problems (TAMREF)

### Korean

대부분 combinatorial (optimization) problem은 조건을 만족하는 (가장 좋은) 구조를 하나 찾아내는 것에 치중합니다. (Spanning Tree, Path, Subgraph, ...) Real-world instance에서는 가능한 다양한 해를 찾아야 하는 경우가 생기고, 많은 경우에 top-k solution을 보는 방법을 사용하기도 합니다. 하지만 대부분의 top-k solution은 구조상 큰 차이가 없어, 정말로 "다양한" 해를 만드는 방법은 아직 잘 모릅니다.
이 발표에서는 두 가지 diversity measure를 정의하고, 그를 최적화하는 matroid base problem, k-path problem을 비롯한 다양한 문제에 대한 FPT-solution을 알아봅니다. 이를 바탕으로, "colorful solution"을 찾는 문제를 어떻게 diversity maximization problem으로 변환할 수 있는지도 알아봅니다.
kw: combinatorial optimization, matroid, color coding

### English

Beyond mere optimization problems, we face many occasions where we need to generate multiple combinatorial instances near the optimum. Classical methods such as "top k best solutions" work well, but they often suffer from a lack of diversity. We define the concept of "diversity" using some basic measures, and investigate related polynomial-time and fixed-parameter tractable algorithms.

kw: combinatorial optimization, matroid, color coding

## Fast Matroid Intersection Algorithms (ainta)

### Korean

Matroid와 그와 관련한 문제들(Matroid intersection, Matroid union, ..)은 Bipartite Matching Colorful Spanning Tree, $k$-disjoint spanning tree, Arboricity 등 다양한 문제에 대한 풀이를 제공합니다. Joakim Blikstad et al, Fast Algorithms via Dynamic-Oracle Matroids(STOC 2023)에서는 기존에 matroid problem을 해결하는 model들의 한계를 이야기하고 dynamic rank oracle model이 이를 어떻게 개선하여 실제 문제의 time complexity bound를 어떻게 개선했는지에 대해서 다룹니다.
이 발표에서는 먼저 matroid 관련 문제를 알아보고, 해당 논문 이전에 matroid intersection 문제를 빠르게 해결하는 어떤 노력이 있었는지 알아봅니다. 이에 관하여 rank oracle과 independence oracle 모델에 대해 다룹니다. 그리고 마지막에 dynamic rank oracle model로 matroid 문제를 해결하는 방법에 관해 소개합니다.

## Shorter Tours by Nicer Ears: From connected -join to graphic TSP variants (leejseo)
### Korean
Abstract:
Connected T-join 문제는 graphic TSP, graphic path TSP 문제를 모두 일반화한 문제입니다. Sebö and Vygen, Shorter Tours by Nicer Ears (2012)에서는 connected T-join 문제에 대한 ear-decomposition 기반의 접근을 제시했으며, 이를 기반으로 graphic TSP, graphic path TSP에 대해 개선된 결과 또한 제시했습니다.
이 발표에서는 먼저 connected T-join 문제를 알아보고, ear decomposition을 기반으로 하는 이 문제에 대한 접근을 소개합니다. 또한, 이 framework을 기반으로 하는 이후의 결과들을 간략히 살펴봅니다.
