- Tree

  - Binary Tree
    - Perfect Binary Tree
    - Complete Binary Tree
    - Full Binary Tree
    - 삽입
    - 삭제
  - Binary Search Tree
    - 삽입
    - 삭제
  - Binary Heap
    - 삽입
    - 삭제
  - Minimum Spanning Tree
  - AVL Tree

    - 자식 서브트리의 높이차가 1이하
    - 삽입 O(logN)

    ```
      1. BST 삽입 O(logN).
      2. 삽입된 노드로부터 위로 올라가며 find x(y의 자식), y(z의 자식), z(처음으로 AVL조건이 깨진 노드) O(logN)
      3. rebalance(x, y, z) O(1) : x, y, z의 정렬상태에 따라 일자면 회전 1번, 꺽인선이면 회전 2번.
      4. root가 바뀌었으면 교체 O(1)
    ```

    - 삭제

  - Red Black Tree
    - 조건 5개
    - 삽입
    - 삭제
  - B Tree
  - B+ Tree
  - Trie

- Hash Table
  - hashfunction(key) => hashcode
