- Sorting Algorithm

  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Quick Sort (Top - Down)
  - Merge Sort (Bottom - Up)
  - Heap Sort
  - Topological Sort
    - DAG(방향이 있고 사이클이 없는 그래프)인 경우 사용.
    - 특정 원소끼리 위상을 유지한체 정렬.

- Search Algorithm

  - Binary Search
  - DFS
  - BFS

- Shortest Path or minimum cost Algorithm (최소, 최단)

  - Dijkstra
  - BFS
  - Bellman-Ford
  - Kruskal Algorithm

    ```
    MST의 cycle property를 이용한 알고리즘

    cycle property란 cycle을 이루는 에지중 최대 비용 에지는 MST에 포함되지 않는다.

    pf) cycle이란 2개의 서브그래프를 연결하는 에지가 2개라는 소리다.

    2개의 서브그래프를 연결하는 MST가 최대비용 에지를 선택하였다면 이는 MST정의에 모순이다.

    따라서 cycle property가 증명된다.

    모든 에지를 오름차순으로 정렬한 후 에지를 선택해 나간다.

    이때 cycle이 형성된다면 이 에지는 cycle property에 의해 제외된다.

    따라서 MST가 만들어진다.
    ```

  - Prim Algorithm

    ```
    MST의 cut property를 이용한 알고리즘

    cut property란 그래프를 2개의 서브그래프로 자르는 선상의 에지중에서 최소비용 에지를 포함하는 MST는 최소 1개 이상 존재한다.

    pf) 만약 cut선상의 에지 중 최소비용 에지를 포함하는 MST는 없다고 가정.

    그렇다면 cut선상의 최소비용이 아닌 에지를 사용하여 MST를 구성하였다는 것.

    이는 MST 정의에 모순.

    따라서 cut선상의 최소비용 에지를 포함하는 MST는 최소 1개 이상 존재한다.

    따라서 에지를 선택할때 현재 선택된 노드들에서 나가는 에지중 최소비용 에지만을 선택하여 트리를 구성하면 MST가 된다.
    ```

  - Graph Algorithm

    - Union Find
      - union : 두 노드의 부모노드 중 작은 값으로 합친다.
      - find : 부모노드가 같으면 같은 집합 아니면 다른 집합.
