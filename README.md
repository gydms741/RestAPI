# RestAPI

## REST 특징

1. Server-Client(서버-클라이언트 구조)
- 자원이 있는 쪽이 Server, 자원을 요청하는 쪽이 Client가 된다.
- REST Server : API를 제공하고 비즈니스 로직 처리 및 저장을 책임진다.
- Client : 사용자 인증이나 context(세션, 로그인 정보) 등을 직접  관리하고 책임진다.
- 서로 간 의존성이 줄어든다.

2. Stateless(무상태)

- HTTP 프로토콜은 Stateless Protocol이므로 Rest역시 무상태성을 갖는다.
- Client의 context를 Server에 저장하지 않는다. 즉, 세션과 쿠키와 같은 context정보를 신경쓰지 않아도 되므로 구현이 단순해진다.
- Server는 각각의 요청을 완전히 별개의 것으로 인식하고 처리한다.
- 각 API서버는 Client의 요청만을 단순 처리한다.

## REST API란

- API(Application Programming Interface)란

데이터와 기능의 집합을 제공하여 컴퓨터 프로그램간 상호작용을 촉진하며, 서로 정보를 교환 가능 하도록 하는 것

- REST API의 정의

REST기반으로 서비스 API를 구현한 것.

최근 Open API, 마이크로 서비스를  제공하는 업체 대부분은 rest api를 제공한다.
