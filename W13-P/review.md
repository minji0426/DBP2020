# 1.새로 배운 내용
    이클립스, 오라클 DB 연동
    오라클DB와 jsp연동
    JSP, Java Server Page
      HTML 내부에 java 코드를 입력하여, 웹 서버에서 동적으로 웹 브라우저를 관리하는 언어
    (jsp 구동원리)
    JSP를 실행하면, JSP 에서 생성된 서블릿이 실행됨
    클라이언트가 jsp 실행을 요청하면, 서블릿 컨테이너는 jsp 파일에 대응하는 자바 서블릿을 찾아서 실행한다.
    대응하는 서블릿이 없거나, jsp 파일이 변경되었으면, jsp 엔진을 통해 서블릿 자바 소스를 생성한다.
    자바 컴파일러가 서블릿 자바 소스를 클래스 파일로 컴파일 한다. (jsp 파일이 변경될때마다 반복)
    jsp 로 부터 생성된 서블릿은 서블릿 구동 방식에 의해 service() 메소드가 호출되고, 서블릿이 생성한 html 화면을 웹 브라우저로 보낸다. 



# 2.문제가 발생하거나 고민한 내용
    1. 포트번호 사용중 오류
      톰캣 서버 설정을 할 때 8090, 8005 포트번호가 이미 사용중이라고 떴다. 그래서 새로 9090, 8006번을 입력했었는데
      실습 처음에 했던 터미널 창을 켜놓은 상태여서 닫고 다시 8090, 8005번을 입력해서 해보니 정상적으로 설정되었다.
      
    2. ojdbc를 연결할 때 connection test 오류
      며칠동안 계속 구글링을 해서 나오는걸 전부 해봤는데도 계속 오류가 났다.
      슬랙 qna채널을 보니 교수님이 localhost로 변경해보라고 하셔서 변경해보니 success메세지가 떴다!!
      
    3. index.html 삭제 링크 추가 안되는 오류
      직원 추가 링크 밑에 직원 삭제 링크를 만들고 다시 실행시켜봤는데 삭제 링크가 계속 추가가 안됐다.
      문법 오류가 있는것도 아니었고 이클리스를 껐다가 다시 켜봐도 안되고 서버를 재시작해도 안됐다.
      실행 창에서 주소창 옆 화살표를 클릭해서 index.html을 광클했는데 갑자기 추가가 됐다. 


# 3.참고할만한 내용
    슬랙 qna게시판을 참고했다.


# 4.회고
    (+) 오류때문에 힘들었지만 과제를 끝내고 나니까 너무 뿌듯하다.

    (-) 이번 과제는 오류가 많이 떠서 시간도 오래 걸리고 결국 과제도 지각제출했다... 과제를 미리미리 하기가 참 힘든 것 같다...

    (!) 오류를 해결할 수 있을까 싶었는데 결국은 다 해결했다! 
    
    
# 5.실행동영상

https://youtu.be/fEw5W04ubOk
