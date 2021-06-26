<h1>Filter</h1>

<p>
Filte란 Web Application에서 관리되는 영역으로써 Spring Boot Framework에서 Client로 부터 오는 요청/응답에 대해서 최초/최종 단계의
위치에 존재하며,
</p>
<p>이를 통해서 요청/응답의 정보를 변경하거나, Spring에 의해서 데이터가 변환되기 전의 순수한 Client의 요청/응답 값을 확인 할수 있다.</p>

<p>유일하게 ServletRequest, ServletResponse의 객체를 변환 할수 있다.</p>

<p>주로 SpringFramework에서는 Reqeust/Response의 Logging용도로 활용하거나, 인증과 관련된 Logi 들을 해당 Filter에서 처리한다.</p>

