## domain과 web
* domain은 핵심 비즈니스 업무 영역, web에 의존X
* web이 변경되더라고 domain은 그대로 사용할 수 있어야 함

## 로그인 처리하기 - 쿠키 사용
* 영속 쿠키와 세션 쿠키

## 로그인 처리하기 - 세션 동작 방식
* sessionId만 쿠키로 저장하여 이를 통해 서버에서만 회원정보 확인

## 로그인 처리하기 - 서블릿 HTTP 세션1
* 서블릿에서 제공하는 세션

## 로그인 처리하기 - 서블릿 HTTP 세션2
* @SessionAttribute를 통해 value가져오기

## 세션 정보와 타임 아웃 설정
* properties 혹은 코드상에 세션만료 interval 설정 가능

## 서블릿 필터 - 소개
* 서블릿에 넘어가기 전에 제한, 수행등이 가능한 필터

## 서블릿 필터 = 요청 로그
* Filter를 상속받아 init(), doFilter(), destroy() 구현
* UUID로 요청별 구분 가능
* chain.doFilter() 없으면 다음 필터, 서블릿으로 넘어가지 않음
* WebConfig에서 Filter 등록
