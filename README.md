<p align="center" >
<a href="https://agent-blog.herokuapp.com/" align="center"> <img src="https://user-images.githubusercontent.com/13609011/84003962-c3ecde80-a9a5-11ea-8722-8a7e9d99681f.png" width="250" height="250" align="center"/></a>
</p>
<h1 align="center">
  Agent Blog Client </br>  <img alt="React" src="https://img.shields.io/badge/React-16.9.34-red.svg"> <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3.7.5-blue.svg"> <img alt="Hooks" src="https://img.shields.io/badge/Hooks-0.5.0-blueviolet.svg"> <img alt="Apollo" src="https://img.shields.io/badge/React_Apollo-3.1.5-green.svg"> <img alt="platform" src="https://img.shields.io/badge/platform-Web-orange.svg">
</h1>

### 🔥 Motivation

> React + TypeScript + Hooks + Apollo 기술을 공부하고, **협업능력**을 기르기 위해 시작한 프로젝트입니다. <br /> <br /> 또한 React를 Javascript로 개발해오면서 디버깅이 불편하고 유지보수도 어렵다는 단점을 개선하고자 **TypeScript**를 도입하게 되었습니다.  (+ 효율적인 협업을 위해)


## 서비스 소개

### [Velog](https://velog.io/) 블로그 서비스 클론코딩 프로젝트
- 개발자들을 위한 블로그 서비스.
- 마크다운 (Markdown) 문법을 사용하여 개발자들이 쉽고 빠르게 예쁘게 꾸며진 포스트를 작성 할 수 있습니다.
- 메인 페이지에서 개발 트렌드 및 인기 태그 제공을 통해 융용한 정보를 쉽고 빠르게 찾을 수 있습니다.
- 개발자들을 위한 블로그 서비스인 velog를 프론트엔드, 벡엔드 모두 클론코딩하여 Markdown 기반 게시물 작성, 해시태그 설정, 게시물 검색, 해시태그 검색, 반응형디자인 등 대부분의 기능을 구현하였습니다.


## UI

### 1) 메인 홈페이지

![velog_feed mov](https://user-images.githubusercontent.com/13609011/84225378-edc71200-ab19-11ea-9fd8-371c31a68d09.gif)

- Card 디자인 & Skeleton 로딩 구현
- 트렌딩 / 최신 게시물 노출
- hover 애니메이션
- 인기태그 표시



### 2) Responsive Layout
<table>
   <tr>
     <th align="center">
       <img width="400" alt="1" src="https://user-images.githubusercontent.com/13609011/84225388-f586b680-ab19-11ea-812c-4adea276119b.gif"/>
       <br><br>[피드]
     </th>
     <th align="center">
       <img width="400" alt="2" src="https://user-images.githubusercontent.com/13609011/84225392-f7e91080-ab19-11ea-884a-ec2b1ec6920a.gif"/>
       <br><br>[검색] 
    </th>
  </tr>
</table>

- 미디어 쿼리를 이용하여 반응형 웹사이트를 구현



### 3) 로그인

<table>
   <tr>
     <th align="center">
       <img width="400" alt="1" src="https://user-images.githubusercontent.com/13609011/84225386-f3bcf300-ab19-11ea-96e1-073c342a652d.gif"/>
       <br><br>[로그인]
     </th>
     <th align="center">
       <img width="400" alt="2" src="https://user-images.githubusercontent.com/13609011/84225370-ebfd4e80-ab19-11ea-84d7-0becdc0e8765.gif"/>
       <br><br>[회원가입] 
    </th>
  </tr>
</table>

- 모달을 통해 로그인과 회원가입을 구현했습니다.
    - Portal 사용

![velog_login mov](https://user-images.githubusercontent.com/13609011/84225384-f1f32f80-ab19-11ea-8172-9adfed4cab7d.gif)

- 이메일 인증으로 로그인 구현
    - nodemailer 사용



### 4) 해시태그 검색

![velog_hashtag mov](https://user-images.githubusercontent.com/13609011/84225382-f0296c00-ab19-11ea-9582-e3b538e6a086.gif)

- Skeleton loading 구현



### 5) 게시물 검색

![velog_search mov](https://user-images.githubusercontent.com/13609011/84225393-f91a3d80-ab19-11ea-9db4-99c66a9edec0.gif)

- Input 값의 변화를 실시간으로 감지하여 입력 즉시 검색 데이터를 받아옴



## 활용기술
- **[Styled-component]()**: 
