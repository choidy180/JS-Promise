# JS-Promise

프로미스는 자바스크립트 비동기 처리에 사용되는 객체

자바스크립트 비동기 처리 - "특정 코드의 실행이 완료될 때까지 기다리지 않고 다음 코드를 먼저 수행하는 자바스크립트의 특성"

+ 프로미스가 필요한 이유

프로미스는 주로 서버에서 받아온 데이터를 화면에 표시할 때 사용, 일반적으로 웹 어플리케이션 구현시
서버에서 데이터를 요청하고 받아오기 위해 아래와 같은 API를 사용한다

$.get('url 주소/products/1', function(response){ //... });
