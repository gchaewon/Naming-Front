## 이름하여 이름하다
<h2>다른 사람이 적어주는 나의 정의를 모아 사전을 만들어보세요!</h2>
### 프로젝트 소개
<h3>이름하여 이름하다는 자신에 대한 정의를 주변인들로부터 모아 나만의 사전을 만들 수 있는 서비스입니다.
00하다에 사전 주인의 이름을 넣을 수 있고, 사전의 특성을 살려 자음별로 정의를 모아볼 수 있게 하였으며 
처음 작성할 때엔 시작해야하는 자음을 랜덤으로 배정해 약간의 강제성이 섞인 재미를 더했습니다.
</h3>
<br>
<hr>
<br>

## 프론트엔드 팀원 소개

<table border="" cellspacing="0" cellpadding="0" width="100%">
    <tr width="100%">
        <td align="center"><a href= "https://github.com/miinjoo">김민주</a></td>
        <td align="center"><a href= "https://github.com/gchaewon">이채원</a></td>
        <td  align="center"><a href= "https://github.com/yun5581">허윤</a></td>
    </tr>
    <tr width="100%">
         <td  align="center"><img src = "https://ifh.cc/v-xS27DL" width="100px"/></td>
        <td  align="center"><img src = "https://ifh.cc/v-rjVP2l" width="100px" /></td>
        <td  align="center"><img src = "https://ifh.cc/v-1FKqMW" width="100px"/></td>
    </tr>
    <tr width="100%">
      <td  align="felx-start">
        [가입자] 홈 화면 페이지 <br/> [가입자] 정의 구경하기 페이지 <br/> [가입자] 사전 검색 페이지 <br/> 햄버거 메뉴
        </td>
      <td  align="flex-start">
        [가입자] 초기/로그인/회원가입 페이지 <br/> 유저인증 & 로그인유지 <br/> 페이지 라우팅 
        <br/> 사전 커스텀 페이지  <br/> 사전 공유 기능 <br/> 만든이들 페이지
        <br/> [방문자] 정의 추가 작성, 정의 둘러보기 
       </td>
      <td  align="flex-start">[방문자] 초기화면 페이지 <br/> [방문자] 작성자 이름 입력 페이지 <br/> [방문자] 정의 초기 작성 페이지
        </td>
   </tr>
</table>

### 개발 기간

- 퍼블리싱 : 1/5 ~ 1/20
- 기능 구현과 API 연결 : 1/20 ~ 2/1
- 알파 테스트 : 2/1 ~ 2/8
- 사이트 공개 : 2/13

<br/>

## 프로젝트 시작
```
git clone https://github.com/NAME-ING/Naming-Front.git
npm install
npm start
```

## 기술 스택

- Frontend : <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=Redux&logoColor=white"> <img src="https://img.shields.io/badge/ReduxToolkit-764ABC?style=flat-square&logo=Redux&logoColor=white"> <img src="https://img.shields.io/badge/ReduxPersist-764ABC?style=flat-square&logo=Redux&logoColor=white"> <img src="https://img.shields.io/badge/styled_components-DB7093?style=flat-square&logo=styled-components&logoColor=white">
- Package Manager : <img src="https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white">
- Code Formmater : <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=React&logoColor=white">
- ETC :
 <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> 
</br>

### 폴더 구조

```
📂 src
├─ 📂 api  ▶️ api 모음
├─ 📂 redux  ▶️ store와 Slice 파일 모음
├─ 📂 components  ▶️ 컴포넌트
├─ 📂 images  ▶️ svg 파일 모음
├─ 📂 pages  ▶️ 조건에 따라 라우팅되는 페이지
├─ 📂 styles  ▶️ 공통적으로 사용되는 스타일 값
└─ 📂 _mock  ▶️ 샘플 데이터
```
