# spring-exception

- Exception
- 서블릿 예외 처리, 오류 페이지 작동 원리
1. WAS(여기까지 전파) <- 필터 <- 서블릿 <- 인터셉터 <- 컨트롤러(예외발생)
2. WAS `/error-page/500` 다시 요청 -> 필터 -> 서블릿 -> 인터셉터 -> 컨트롤러(/error- page/500) -> View

- HandlerExceptionResolver
- ExceptionHandler
- ControllerAdvice




### Git Convention

- feat : 기능추가
- fix : 버그 수정
- refactor : 리팩토링, 기능은 그대로 두고 코드를 수정
- style : formatting, 세미콜론 추가 / 코드 변경은 없음
- chore : 라이브러리 설치, 빌드 작업 업데이트
- docs : 주석 추가 삭제, 문서 변경
