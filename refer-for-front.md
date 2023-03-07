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
	
<br/><br/>
