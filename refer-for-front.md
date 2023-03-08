<h2>🛠 주요 기술</h2>
<table border="1">
	<th>사용 기술</th>
	<th>기술내용</th>
	<tr>
	    <td>CI/CD</td>
	    <td>FE에서는  Github Actions, BE에서는 jenkins, nginx를 사용한 자동 빌드 및 무중단 배포 구현</td>
	</tr>
	<tr>
	    <td>Refresh token</td>
	    <td>JWT 토큰을 일정 시간마다 자동 발급하여 으로 인증시간을 늘리고 보안성 높임</td>
	</tr>
	<tr>
	    <td>이메일 인증</td>
	    <td>회원가입시 인증 이메일을 발송하여 사용자 확인</td>
	</tr>
	<tr>
	    <td>소셜 로그인</td>
	    <td>카카오를 통한 소셜 로그인</td>
	</tr>
	<tr>
	    <td>Cache</td>
	    <td>케시 데이터를 사용한 API 요청 최소화</td>
	</tr>
	<tr>
	    <td>CloudFront</td>
	    <td>정적 컨텐츠의 전송 속도를 높이고 HTTPS 적용을 통한 보안강화</td>
	</tr>
	<tr>
	    <td>통계데이터 시각화</td>
	    <td>ApexCharts 커스텀을 통해 통계 데이터를 다양한 그래프로 시각화</td>
	</tr>
    </table>

<br/><br/>

<h2>📚 주요 라이브러리</h2>
<table border="1">
	<th width="12%">라이브러리명</th>
	<th align="center">버전</th>
	<th>사용목적</th>
	<tr>
	    <td>react-redux</td>
	    <td align="center"> 6.3.0</td>
	    <td>규모가 큰 프로젝트의 데이터 전역관리에 용이. mobx, recoil 등과 비교했을 때 아직까지 사용자가 압도적으로 많고 커뮤니티가 가장 발달되어 있기 때문에 제일 기본적인 상태관리 라이브러리로 이해도를 높이기 위해 사용</td>
	</tr>
	<tr>
	    <td>react-actions</td>
	    <td align="center"> 2.6.5</td>
	    <td>리듀서를 작성할 때 switch문이 아닌 handleActions라는 함수를 사용하여 코드가 짧아지고 가독성이 좋아짐. 다른 상태 라이브러리에 비해 코드가 길고 복잡한 redux의 단점 보완</td>
	</tr>
	<tr>
	    <td>react-thunk</td>
	    <td align="center">2.4.1</td>
	    <td>redux 액션을 반환할 때 객체뿐 아니라 함수를 반환하게 해주어 미들웨어에서 비동기 처리 가능</td>
	</tr>
	<tr>
	    <td>react-router-dom</td>
	    <td align="center">6.3.0</td>
	    <td>리액트 컴포넌트 기반으로 경로설정 가능</td>
	</tr>
	<tr>
	    <td>Styled-components</td>
	    <td align="center">5.3.5</td>
	    <td>css의 컴포넌트화로 재사용 및 유지보수 용이, props 전달 및 jsx문법 적용 가능</td>
	</tr>
	<tr>
	    <td>jwt-decode</td>
	    <td align="center">3.1.2</td>
	    <td>jwt토큰에서 유저정보 디코딩을 위해 사용</td>
	</tr>
	<tr>
	    <td>axios</td>
	    <td align="center">0.27.2</td>
	    <td>HTTP Client 라이브러리로 Fetch API에 비해 코드가 간결하고 JSON데이터로 자동변환 가능</td>
	</tr>
	<tr>
	    <td>react-big-calendar</td>
	    <td align="center">0.40.2</td>
	    <td>일정 / 장부 / 일지 페이지에서 달력에 등록된 이벤트를 띄워주기 위해 사용
react-calendar, react-datepicker 는 날짜 선택 혹은 등록된 일정의 기간을 직관적으로 보기에 용이하다면 react-big-calendar 는 등록된 이벤트의 내용을 직관적으로 보여줌</td>
	</tr>
	<tr>
	    <td>react-apexcharts</td>
	    <td align="center">1.4.0</td>
	    <td>차트 라이브러리로 디자인이 깔끔하고 CSS 및 데이터 커스텀에 용이</td>
	</tr>
  </table>

    <!-- 상돈 hateyou@kakao.com / https://github.com/powercording
    	웹소켓 실시간 채팅 구현, 서버사이드 이벤트 수신하여 서버에서 사용자에게 알릴 이벤트가 있는경우 클라이언트 화면에 알람기능. -->

<table border="1">
<thead>
<tr><th>라이브러리명</th><th>버전</th><th>사용 목적</th></tr>
</thead>
<tbody>
<tr>
<td>sockjs-client</td>
<td>1.5.1</td>
<td>웹 소켓 통신. 서버와 연결 된 이후 연결을 끊지 않아 서버와 클라이언트 간 양방향 통신이 가능.</td>
</tr>
<tr>
<td>stompjs</td>
<td>2.3.5</td>
<td>웹소켓 통신에 헤더를 추가하여 클라이언트로 부터 서버로 토큰을 전달하여 사용자를 인증 및 구별 할 수 있음.</td>
</tr>
<tr>
<td>event-source-polyfill</td>
<td>1.0.31</td>
<td>기존 EventSource API 는 헤더를 작성 할 수 없기 때문에 이벤트 서버에 연결 하기 위한 헤더를 추가 할 수 있게 도와줌.</td>
</tr>
</tbody>
</tabel>
   
## 트러블 슈팅

<details>
<summary>웹 소켓 연결 엔드포인트를 찾지 못하는 이슈</summary>
<div>

- 문제상황  
  채팅 기능을 구현하기 위해 웹소켓 관련 라이브러리 설치 이후 서버와 연결을 시도 할때
  웹소켓이 서버를 찾지 못하고 연결되지 않는 현상을 마주침. 해당 문제가 해결되지 않아
  채팅기능 개발이 일주일동안 늦춰지고 있었음.

- 해결 과정

  - sockjs-client / stompjs 라이브러리를 재설치. 문제가 해결되지 않음.
  - 연결 로직을 복사하여 그대로 새로운 리액트 프로젝트 생성하여 적용. 서버 연결 성공.
    현재 개발중인 프로젝트는 vite + react 이었으므로 vite 설정의 문제라고 판단.
  - 새로운 vite + react 프로젝트를 생성하여 같은 코드를 통해 연결을 시도 하던중 순수한 리액트 프로젝트에선 발생하지 않는 오류가 발생하는것을 발견함.
  - 몇몇 라이브러리는 vite 에서 global 객체를 찾지 못하는 현상이 있음을 확인함. 이번 케이스의 경우 웹 소켓 으로 채팅을 구현하기 위하여 받은 라이브러리가 해당 오류를 일으킴.
  - 해당 오류를 해결하기 위하여 [stack overflow 검색 결과](#https://stackoverflow.com/questions/72114775/vite-global-is-not-defined)를 적용하여 vite 설정에 global 객체를 빈 객체 리터럴로 설정 해두었던 것이 해당 라이브러리 오류는 피해갔지만 동시에 백엔드 서버를 찾지 못하는 원인이 되었던 것.
  - index.html 스크립트에 global = window 를 추가하여 해결.

- 결과
  서버와의 연결이 성공하는것을 확인 하고 난 후에 바로 기능개발에 착수하여 채팅 기능을 3일만에 완성 할 수 있었음.

- 정리 
	- vite 는 webpack 처럼 global필드를 정의하지 않습니다. 일부 라이브러리는 오래 되어 global에 의존하는 코드를 가지고 있습니다. - 일반적인 경우 window.global ||= window; 등의 코드 추가를 고려해볼만 합니다 - 프로젝트에서 사용된 sockjs 의 경우 글로벌객체를 참조하는 코드를 가지고 있습니다 [ex) if (global.document) { transportList = require(‘./transport-list’)]
	- 이로 인해 global을 정의하지않는 vite환경에서 global 객체를 찾을수 없다는 오류를 발생시켰고, 이를 해결하기 위해서 적용한 global = {} 코드가 global 을 빈 객체로 만들어 예상치 못한 동작을 일으킵니다. 
	- websocket 은 브라우저에서 작동 하므로 해당 global 에 대한 참조를 브라우저 전역 객체인 윈도우로 바꾸어주어 해결합니다.
</div>
</details>
<br/><br/>
