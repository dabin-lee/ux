javascript

javascript는 가벼운

 인터프리터형 (통역같은 존재 듣고->해석->알아들을 수 있는 형태로 변환)
컴파일 (문서를 번역 정도로 해석)
상대적으로 컴파일보다 느린형태가 인터프리터형

서버가 사용자에게 전달받은 데이터를 해석하고 처리해서 상대적으로 컴파일 언어들에 비해서 느리다.

프로토타입



패더라임 : 개발을 하는 개방성/ 하나만 갖고있는게 아니고 여러방향을 제시


사용자의 행동, 요구사항에 따라


DOM




## 자바스크립트 ES6 개발 환경 - 걸프(gulp), 바벨(babel)

많은 브라우저들이 ES6 문법을 일부 지원하고 있는 것을 볼 수 있지만 아직까지 완벽하게 지원되지 않는 것 같습니다. 때문에 ES6를 선택하고 개발하고자 한다면 트랜스컴파일이라는 작업을 해줘야 합니다. ES6코드를 ES5로 말이죠. 이번 글에서는 그중에서도 babel과 gulp라는 툴의 사용법을 간단히 적어보려 합니다.

Gulp (걸프):  반복적인 개발 작업을 자동화하는 빌드 도구
babel(바벨): ES6코드를 ES5코드로 변환해주는 트랜스컴파일러

https://lucidmaj7.tistory.com/122