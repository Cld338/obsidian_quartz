---
tags: []
---
군집화 알고리즘의 일종으로 k개의 군집을 형성하는 알고리즘이다. 과정은 다음과 같다.
1. k개의 임의의 지점에 cluster의 중심을 잡는다.
2. 각 샘플에서 가장 가까운 중심에 해당하는 cluster에 샘플을 할당한다.
3. cluster에 할당된 샘플들의 평균을 cluster의 중심으로 지정한다.
4. 2~3을 cluster의 중심이 변하지 않을 때까지 반복한다.