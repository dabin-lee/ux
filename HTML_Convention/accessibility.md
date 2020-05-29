# 접근성에 관하여

## button, a, input 태그
<a>요소 

URI를 ‘연결‘하기 위한 버튼으로서 <a href="#url"> 형식으로 마크업 합니다.



<button>요소

URI를 연결하지 않고 단순하게 사용자 인터페이스만를 ‘조작‘하기 위한 버튼으로서 <button type="button"> 엘리먼트로 마크업 합니다.  type을 명시하지 않으면 어떤 브라우저는 Form Submit 기능을 실행하기 때문에 반드시 type 속성을 button으로 지정해 주어야 합니다.



<input>요소

사용자의 입력을 서버로 ‘전송‘하기 위한 버튼으로서 <input type="submit">, <button type="submit"> 엘리먼트로 마크업 합니다.



버튼의 목적을 명확하게 판단한 뒤 알맞는 엘리먼트를 사용하는 것은 접근성을 향상시켜 줍니다. 

최근에는 Javascript를 지원하지 않는 브라우저 환경이 드물지만 되도록 Javascript에만 의존하여 기능을 수행하지 않도록 하는 것이 좋습니다. 

특히 Link Button을 이용하여 Form을 전송하는 기능을 구현하면 Javascript를 지원하지 않는 환경에서의 상호 운용성을 확보하지 못하고 화면낭독기 장치를 이용하는 사람들의 접근성을 떨어 뜨리게 됩니다. 

Form 페이지의 전송 버튼을 ‘submit’ 버튼 대신 ‘a’  버튼으로 마크업 하는 경우 화면 낭독기는 HTML기반으로 내용을 읽어 주기 때문에 이것을 ‘~링크’라고 읽어 주고 시각장애인은 이것을 ‘~전송 버튼’이라고 확신할 수 없는 문제가 발생 합니다.



출처: https://jsunnylab.tistory.com/38 [Jsunny Lab]


<button onclick ="window.location.href='/page2'">continue</button>

-> javascript를 피요로 하기 때문에 스크린 리더기에는 접근성이 좋지 않음
버튼을 링크처럼 작동시키는 것은 잘못된 해결책이다.
* 링크를 사용하고 버튼처럼 보이도록 스타일을 지정해야 한다.