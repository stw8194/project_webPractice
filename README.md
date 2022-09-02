# 레이서 포트폴리오 서비스

이 프로젝트는 자기자신의 포트폴리오를 작성하고, 또한 다른 사람의 포트폴리오를 확인할 수 있는 웹 서비스입니다. \
웹 구현 : http://kdt-ai5-team12.elicecoding.com

위 IP 주소는 프로젝트 진행 기간에만 유효합니다.

5개 MVP로 구성됩니다.

- User (회원가입, 로그인 등 사용자 관련)
- Award (포트폴리오 중 상장 이력 관련)
- Certificate (포트폴리오 중 자격증 관련)
- Project (포트폴리오 중 프로젝트 관련)
- Education (포트폴리오 중 교육, 학교 관련)

## 주요 사용 기술

1. 프론트엔드

- React (create-react-app으로 구현되었습니다.)
- React Bootstrap
- axios

2. 백엔드

- Express (nodemon, babel-node로 실행됩니다.)
- Mongodb, Mongoose

### 기본 기능

1. 회원가입, 로그인(로그아웃 상태일떄 기본 페이지), 로그인한 회원의 모든 정보(다른 MVP에서 정보를 가져와 해당 화면에 표시, 로그인 한 후의 기본 화면), 회원가입된 전체 유저 목록, 로그아웃

   - 아래의 항목들은 로그인 후의 기본 화면에 모두 아이콘이 표시됨

   I. Education : 학력 등록, 생성, 삭제

   II. Award : 수상 이력 등록, 생성, 삭제

   III. Project : 프로젝트 등록, 생성, 삭제

   IV. Certificate : 자격증 등록, 생성, 삭제

#### 추가 기능

- ProjectMVP에 프로젝트 증빙 이미지 추가 기능 구현
- 웹페이지에 다크모드 구현
- 맨 위로 바로 돌아올 수 있는 리스트업 리모컨 구현
- 로그인 실패사유 alert으로 알림(추가)
- Project 태그 기능, 아코디언 기능
- Award 수상이력 수상기간 기능

#### 기능 개선

- 이전페이지로 이동 버튼 두번 눌러야 실행되는 오류 해결
- UserMVP에 이미지 업로드 기능 추가
- UserMVP를 제외한 4개의 MVP에 각각 삭제 기능을 추가
- 로그인 후 기본페이지에서 발생하는 DOM관련 오류 수정(Portfolio.js 의 Container Style 변경)
- 다른 유저의 이메일 편집 기능 제거(개선기능)
- REST API 구조 개선
- mongoose schema에 index추가
- 중복되는 id 생성을 module화 함
- 로그인 시 Console 창에 유저정보 띄우던 코드 삭제
- 디테일한 디자인 개선(이모티콘, 버튼, 반응형 웹 개선 등 수정)

### 포지션

- Award (포트폴리오 중 상장 이력 관련) FE 임동민 BE 한혜진
- Education (포트폴리오 중 교육, 학교 관련) FE 임의연 BE 한혜진
- Project (포트폴리오 중 프로젝트 관련) FE 최은오 BE 송태원
- Certificate (포트폴리오 중 자격증 관련) FE 임지원 BE 송태원

본 프로젝트에서 제공하는 모든 코드 등의는 저작권법에 의해 보호받는 ㈜엘리스의 자산이며, 무단 사용 및 도용, 복제 및 배포를 금합니다.
Copyright 2022 엘리스 Inc. All rights reserved.
