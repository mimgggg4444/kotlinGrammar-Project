
1. **배열(Array)**:
   - 동일한 데이터 형식의 요소들을 순서대로 저장하는 선형 자료구조입니다.
   - 요소의 인덱스를 사용하여 빠르게 접근할 수 있습니다.
   - 크기를 변경할 수 없는 정적인 구조이므로 삽입과 삭제 연산에는 비효율적입니다.

2. **연결 리스트(Linked List)**:
   - 각 요소가 다음 요소의 주소를 가리키는 방식으로 구현된 선형 자료구조입니다.
   - 요소의 삽입과 삭제가 배열에 비해 효율적입니다.
   - 노드의 포인터가 추가 메모리를 사용하므로 공간 효율성은 배열보다 낮을 수 있습니다.

3. **스택(Stack)**:
   - 후입선출(LIFO, Last In First Out) 원칙에 따라 데이터를 저장하는 자료구조입니다.
   - 삽입(Push)과 삭제(Pop) 연산을 지원하며, 가장 최근에 삽입된 요소를 먼저 제거합니다.
   - 함수 호출의 재귀적 구조나 후위 표기법 등에 활용됩니다.

4. **큐(Queue)**:
   - 선입선출(FIFO, First In First Out) 원칙에 따라 데이터를 저장하는 자료구조입니다.
   - 삽입(Enqueue)과 삭제(Dequeue) 연산을 지원하며, 가장 먼저 삽입된 요소를 먼저 제거합니다.
   - 너비 우선 탐색(BFS, Breadth-First Search) 등에 활용됩니다.

5. **트리(Tree)**:
   - 계층적인 구조를 가지며 각 노드가 하위 노드들을 가리키는 자료구조입니다.
   - 이진 트리(Binary Tree)는 각 노드가 최대 두 개의 자식 노드를 가지는 트리입니다.
   - 이진 탐색 트리(Binary Search Tree)는 정렬된 트리로서 삽입, 삭제, 검색이 빠르게 수행됩니다.

6. **해시 테이블(Hash Table)**:
   - 해시 함수를 사용하여 키(key)와 값을 연결하는 자료구조입니다.
   - 키를 해시 함수를 통해 인덱스로 변환하여 값을 저장하고 검색하는데 사용됩니다.
   - 평균적으로 상수 시간(O(1))에 삽입, 삭제, 검색이 가능합니다.

7. **그래프(Graph)**:
   - 정점(Vertex)과 간선(Edge)으로 구성된 자료구조로, 각 간선은 두 개의 정점을 연결합니다.
   - 방향 그래프와 무방향 그래프로 나뉘며, 네트워크 모델링, 경로 탐색 등에 사용됩니다.
