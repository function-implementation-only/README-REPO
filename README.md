# [Joinus] 개발을 위한 인력 매칭 서비스
![image](https://user-images.githubusercontent.com/26705587/174597543-4ecc39e1-0e8a-44e9-b4d9-b4b97e559787.png)

## 시연영상
<br>

[![mocusa](https://user-images.githubusercontent.com/47559613/190395847-58c23322-89a6-4e1a-a3dc-0295212b9995.png)](https://youtu.be/T2y4gs5TT-Y)

## ✨ 기술스택
#### FRONT-END
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"/> <img src="https://img.shields.io/badge/Redux Toolkit-764ABC?style=for-the-badge&logo=Redux&logoColor=white"/> <br> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white"/> <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white"/> <img src="https://img.shields.io/badge/sockjs-333333?style=for-the-badge&logo=sockjs&logoColor=white"/> <img src="https://img.shields.io/badge/stomp-333333?style=for-the-badge&logo=stomp&logoColor=white"/>

#### BACK-END
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"/> 
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white"/> <br> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"/> 
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"/> <img src="https://img.shields.io/badge/sockjs-333333?style=for-the-badge&logo=sockjs&logoColor=white"/> <img src="https://img.shields.io/badge/stomp-333333?style=for-the-badge&logo=stomp&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white"/>
<br>

## 🔧 서비스 아키텍처
![아키텍처](https://user-images.githubusercontent.com/97332044/217025165-06c7a429-ad98-45f1-92db-5433a5317837.png)
<br>

<br>


## ✨ 프로젝트 소개
### 🎤 프로젝트를 위한 개발자,디자이너,PM을 모집해보세요 !!
>1. **원하시는 파트, 기술의 공고를 검색해주세요 !**  
   게임을 시작하면 유저들은 다른사람이 그릴 문장 또는 단어를 제출해 주세요.  
   떠오르는게 없으셔도 괜찮습니다. 저희가 랜덤하게 드리니 그것을 사용하셔도 👌
>2. **지원현황을 통해 얼마나 많은 사람이 지원하였는지 확인해보세요!**  
   다른 유저가 제출한 제시어를 보고 나만의 그림을 통해 표현해주세요.
>3. **원하는 공고라면 채팅을 통해 지원해보세요**  
   다른 유저가 그린 그림을 보고 여러분이 느끼신 그대로 적어주세요.
>4. **모든 라운드가 종료되면...?**  
   게임이 진행되면서 결과물들이 어떻게 표현되는지 함께 보면서 즐겨주세요 😆


## 핵심 기능

### 🔍 검색(필터 및 정렬)

> * Query DSL을 통한 상품 검색 기능 구현
> * 쿼리 성능 개선을 통해 모든 페이지에서 1초 이내로 응답(Latency 목표값 달성)
> * 부하테스트를 통해 DB 병목 지점을 확인 후 DB 스케일 업으로 해결

### 👠 상품 주문

> * 대규모 트래픽에서 상품 주문 시 동시성 이슈 발생
> * Pessimistic Lock을 통해서 동시성 제어
> * 성능 개선(다중 컬럼 update 쿼리, N+1)

### 🔔 재입고 알림

> * 사용자의 UX 향상을 위해서 사용자가 관심이 있는 상품에 대해서 재입고 알람을 제공
> * Redis pub/sub 방식을 고려해봤지만 프론트 상의 한계로  SSE로 구현

### 🧑🏻사용자 & 판매자 마이페이지

> * 권한에 따라 기능에 대한 접근을 제한 (USER/ADMIN)
> * 사용자 마이페이지의 경우 사용자의 주문내역을 보여주는 기능
> * 판매자 마이페이지의 경우 품절된 상품내역을 관리하고 재입고를 등록하는 기능

## 😺 멤버

|[🔰정영준](https://github.com/synuns)|[이예담](https://github.com/GosuEE)|[이상돈](https://github.com/eunsol-an)|[🔰이승주](https://github.com/code0613)|[123](https://github.com/SHsus1122)|[구지영](https://github.com/beautifulseoul)|                                                      김정우                                                       |
|:---:|:---:|:---:|:---:|:---:|:---:|:--------------------------------------------------------------------------------------------------------------:|
|![장신원](https://user-images.githubusercontent.com/116439064/215262142-47067e5c-59ab-4097-aa89-9c1ca56199c8.png)|![이민규](https://user-images.githubusercontent.com/116439064/215262141-5c84b7e9-1a76-4c89-93a9-9b2f404f829a.png)|![안은솔](https://user-images.githubusercontent.com/116439064/215262140-71f4049c-30c5-4bf3-8072-af2b3ebc7ec9.png)|![김재영](https://user-images.githubusercontent.com/116439064/215262138-c0d1dddd-0394-454e-b721-75269dc1bdb4.png)|![서혁수](https://user-images.githubusercontent.com/116439064/215262139-23bf246f-f9f2-4703-a367-8af22628c549.png)|![황미경](https://user-images.githubusercontent.com/116439064/215262240-af881f71-ac78-4b7a-8e6d-f0cd32ff044b.png)| ![조문정](https://user-images.githubusercontent.com/116439064/216855877-eaa237cb-6d28-49ed-a7d7-b02014d2b0a6.png) |
|FRONT-END|FRONT-END|BACK-END|BACK-END|BACK-END|BACK-END|                                                     DESIGN                                                     |

## 🌈 대표사진
![Group 126](https://user-images.githubusercontent.com/97332044/217054483-23b8cebb-cf51-47b9-928c-0df7439108a5.png)
<br>




