## **Queue**
<br>

사전적으로 "줄을 서다"를 의미
먼저 들어온 데이터가 먼저 나가는 형식
-> FIFO(FirstInFirstOut)
큐의 앞부분 front는 삭제 연산만 수행
큐의 뒷부분 rear는 삽입 연산만 수행

<br>

### Queue 선언
Queue<Element> queue = new LinkedList<>()

<br>

### Queue 값 추가
add(value) -> 삽입 성공 true 반환, 실패시 IllegalStateException 발생

offer(value) -> 삽입 성공 true 반환, 실패시 false 반환

<br>

### Queue 값 삭제
poll() -> 첫번째 값을 반환하고 제거
remove() -> 첫번째 값 제거
cleaer() -> queue 초기화

peek() -> 첫번째 값 참조

<br>