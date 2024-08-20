# day11-jQuery 및 이벤트

생성일: 2024년 8월 9일 오전 9:59
사람: 지환 이

[https://velog.io/@wbguanna/day11](https://velog.io/@wbguanna/day11)

한줄요약 : 실습으로 배우는 jQuery 문법&개념 + 마우스 이벤트



jQuery : 간단하게 쓸 수 있는 js 래핑 라이브러리





간단하게?

- css, js 에서 지원하는 선택자 지원

- 메소드 체이닝 지원

- jQuery 객체로 요소속성 & css & 이벤트 동작 등록

+ jQuery 객체 <=> DOM 요소 변환

+ jQuery 객체 내부의 함수는 함수에 따라, 전달받는 인자에 따라 getter/setter가 달라진다.

​



래핑? 메소드 체이닝?



- 예제 : day11jQuery07.html

- "$" 를 변수로 선언한 함수에 인자로 받은 dom 요소를 조작한다

+ "$" 대신 다른 기호로 할당가능하다.

+ 충돌 경우 참고 : https://knowing-passion.tistory.com/66

- 이때 dom 요소를 변경시키거나 값을 가져올 함수를 요소와 연관시킨다

- 그리고 jQuery 함수에서 선언된 함수의 반환값을 

  연관된 dom 요소의 객체를 반환하게하면 메서드 체이닝이 된다

​

마우스 이벤트

 - 이벤트의 일어나는 종류에 따라 일어나는 시점이 다름

 - 이벤트 종류

   - click / dbclick

   - mousedown / mousemove / mouseup

 - 이벤트 주요 속성

   - screenX / screenY : 컴퓨터의 디스플레이 전체 상의 좌표 (듀얼스크린)

   - clientX / clientY : viewport 내의 좌표를 말한다

   - pageX / pageY : ?