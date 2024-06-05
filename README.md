# alarm-practice

## DeferredResult
DeferredResult는 Spring 3.2 부터 사용 가능합니다. 비동기 요청 처리를 위해 사용하는 Callable의 대안을 제공합니다. “지연된 결과”를 의미하며 외부의 이벤트 혹은 클라이언트 요청에 의해서 지연되어 있는 HTTP 요청에 대한 응답을 나중에 써줄 수 있는 기술입니다. 별도로 워커 스레드를 만들어 대기하지 않고도 처리가 가능합니다.

## ConcurrentHashMap
![image](https://github.com/asd42270/alarm-practice/assets/110414025/923147e9-de4e-4b48-8148-c2f198a78e46)

ConcurrentHashMap은 각각의 Bucket 별로 동기화를 진행하기에 다른 Bucket에 속해있을 경우엔 별도의 lock없이 운용한다.
