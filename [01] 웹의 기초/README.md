#### 웹 리소스란?<br>
웹에 콘텐츠를 제공하는 모든 것<br>

### [1.3 리소스]<br>
웹 서버는 웹 리소스를 관리하고 제공한다<br>
리소스는 정적 파일 이거나 사용자 요청에 따라 바뀌는 동적 리소스가 될 수 있다.<br>
정적 파일: 텍스트 파일, HTML 파일, JPEG이미지 등<br>
동적 파일: 주식 거래, 부동산 DB 검색 등 사용자의 요청에 따라 바뀌는 파일<br>

### [1.3.1 미디어 타입]<br>
인터넷은 수천 가지 데이터 타입을 다루기 떄문에 HTTP는 웹에서 전송되는 객체 각각에<br>
MIME타입이라는 데이터 포맷 라벨을 붙인다. Content-type으로 전송됨<br>
사선(/)으로 구분된 주 타입과 부 타입으로 이루어진 문자열 라벨<br>
HTML로 작성된 텍스트문서는 Content-type: text/html<br>
JPEG 이미지는 Content-type: image/jpeg<br>

### [1.3.2 URI]<br>
URI는 Uniform Resource Identitier의 약자로써 자원 식별자 같은 느낌이다.<br>
URL은 Uinform Resource Locator의 약자로써 특정 서버의 한 리소스에 대한 구체적인 위치를 서술한다.<br>
<br>
http://www.yahoo.com/images/log.gif<br>
✅ 보통 첫번째로 오는 https:// 가 scheme(프로토콜) 이 되고,<br>
✅ 두번째로 오는 www.yahoo.com 이 인터넷 서버의 주소,<br>
✅ 마지막인 images/log.gif 가 리소스가 되는 것이다<br>
오늘날의 URI는 대부분 위와 같은 URL이다.<br>
