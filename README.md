# ORI(Auto-Review) 🐤

## 📚 프로젝트 소개

🏷 **프로젝트 명 : ORI**

🗓️ **프로젝트 기간 : 2024.10.30 \~** 

👥 **구성원 : 최도혁, 신종신**

---
### 👨‍💻 백엔드 코드 바로가기

<span style="color: #33C1FF">:octocat:**Github | https://github.com/Auto-Review/ori-be/tree/dev**

### 📲 서비스 구경 바로가기

🖥 **서비스 주소 : https://autoreview.kr/**

**🎥 소개 영상 보기 : 유튜브 링크 첨부**

---

### ✅ 기획 배경

> “누가 옆에서 복습하라 해줬으면 좋겠다..” <br/> 풀었던 문제를 온전히 내 것으로 만들기 위해 다시 복습하려는데 휴대폰이나 캘린더에 알림 설정하는게 귀찮지 않으셨나요?
> 

우리는 학습을 하면서 많은 문제를 풀고, 그 과정에서 새로운 지식을 쌓아갑니다. 하지만 그 지식을 완전히 내 것으로 만들기 위해서는 반복적인 복습이 필요하다는 것을 잘 알고 있습니다. 그럼에도 불구하고, 복습할 시간을 설정하는 것은 종종 번거롭게 느껴지곤 합니다.

우리가 공부하는 동안, 옆에서 누군가가 “이제 복습할 시간이에요!”라고 말해준다면 얼마나 좋을까요? 그 작은 알림이 우리의 학습을 한층 더 효율적으로 만들어주고, 지속적으로 동기를 부여해줄 것입니다.

이제, 그런 역할을 해줄 서비스가 있습니다. 바로 ORI입니다. ORI는 당신의 학습 과정을 함께하며, 필요한 순간에 복습을 알림으로써 학습의 효율성을 높여줍니다.

혼자가 아닌, 함께하는 학습의 즐거움을 느껴보세요. ORI가 당신의 학습 여정을 더욱 풍요롭게 만들어줄 것입니다.

---

### ✅ 서비스 소개

> 알고리즘 문제나 TIL(Today I Learn) 내용을 정해진 날짜에 복습할 수 있도록 알림을 보내주는 서비스
> 
- **설정한 날짜에 복습 알림**
   - 정해진 시각에 그 날에 해당하는 문제에 대해 복습 알림 발송

- **효율적인 문제 관리**
   - 검색을 통해 특정 문제 확인
   - 문제를 난이도별로 분류 가능
   - 문제에 연관된 태그별 검색(고도화)

- **커뮤니티 활성화**
   - 사용자들이 소통하고 문제를 공유할 수 있는 플랫폼 제공(고도화)

- **안정적이고 확장 가능한 인프라 제공**
   - 안정적인 서버 운영과 효율적인 자원 관리
   - 필요 시 확장 가능한 인프라 구축
   - CI/CD 파이프라인 및 컨테이너 관리 시스템 도입으로 배포 및 운영 효율성 증대

---

### 👥 서비스 대상

- 알고리즘 문제를 풀었을 때 다음에 또 풀고 싶은 사람
- 오늘 공부한 내용을 적어두고 완전히 습득할 때까지 다회독 하는 사람



## 💌 서비스 화면 및 기능 소개

### ✅ 사용자 기능

> **로그인/회원가입**

- 소셜 로그인 기능 (OAuth2.0 사용: Google)

- 사용자 프로필 생성 및 관리

![메인_회원정보수정.gif](readme_assets/메인_회원정보수정.gif)


> **프로필 관리**

- 사용자 프로필 편집 (이름, 이메일, 닉네임 등)

![메인_주변유저조회.gif](readme_assets/메인_주변유저조회.gif)

---

### ✅ 게시물 기능

> **코드 게시판**

- 알고리즘 문제 풀이 등록 기능
- 자신의 게시물 수정 및 삭제 기능
- 복습 알림일 및 난이도 설정 기능
- 복습 게시물 생성 기능

> **TIL 게시판**

- TIL 게시물 등록 기능
- 자신의 게시물 수정 및 삭제 기능
- 게시물 스크랩 기능

![메인_주변유저조회.gif](readme_assets/메인_주변유저조회.gif)

> **리뷰(복습) 작성**

- 알고리즘 게시물에만 등록 가능
- 알고리즘 게시물에 생성 및 수정, 삭제 기능
- 리뷰 목록 조회 기능

![메인_주변유저조회.gif](readme_assets/메인_주변유저조회.gif)

> **댓글**

- 댓글 생성 및 수정, 삭제 기능
- 댓글 최대 depth 1로 고정
- 닉네임 언급 방식으로 표현

![메인_주변유저조회.gif](readme_assets/메인_주변유저조회.gif)

---

### ✅ 서버 관리

> **서버 모니터링**

- 서버 상태 모니터링 및 로그 관리
- GitAction을 이용한 CI/CD 파이프라인 구축

![메인_주변유저조회.gif](readme_assets/메인_주변유저조회.gif)

---

## 🛠 기술 스택

### BE
<p>
   <img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
   <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
   <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=OpenJDK&logoColor=white"/>
</p> 

### DB
<p>
   <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
   <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
</p>


### Dev-Ops
<p>
   <img src="https://img.shields.io/badge/amazonEC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
   <img src="https://img.shields.io/badge/docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
   <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
   <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=Prometheus&logoColor=white"/>
   <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=Grafana&logoColor=white"/>
</p>


### Communication Tool
<p>
   <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>
   <img src="https://img.shields.io/badge/figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
   <img src="https://img.shields.io/badge/jira-0052CC?style=flat-square&logo=jira&logoColor=white">
   <img src="https://img.shields.io/badge/notion-000000?style=flat-square&logo=notion&logoColor=white">
</p>



## 🗂 프로젝트 구조

### BE

```markdown
ori-be (Repository Root)
ori-be (Repository Root)
├── 📂 .github
│   └── 📂 workflows
├── 📂 gradle
│   └── 📂 wrapper
├── 📂 src
│   ├── 📂 main
│   │   └── 📂 java
│   │       └── 📂 org
│   │           └── 📂 example
│   │               └── 📂 autoreview
│   │                   ├── 📂 domain
│   │                   │   ├── 📂 bookmark
│   │                   │   ├── 📂 codepost
│   │                   │   ├── 📂 fcm
│   │                   │   ├── 📂 member
│   │                   │   ├── 📂 notification
│   │                   │   ├── 📂 refresh
│   │                   │   ├── 📂 review
│   │                   │   └── 📂 tilpost
│   │                   ├── 📂 global
│   │                   │   ├── 📂 common
│   │                   │   │   └── 📂 basetime
│   │                   │   ├── 📂 config
│   │                   │   ├── 📂 exception
│   │                   │   ├── 📂 initializer
│   │                   │   ├── 📂 jwt
│   │                   │   └── 📂 scheduler
│   │                   └── 📜 AutoreviewApplication.java
├── .gitignore
├── .gitmodules
├── Dockerfile.dev
├── Dockerfile.local
├── Dockerfile.prod
├── build.gradle
├── gradlew
├── gradlew.bat
└── settings.gradle
```

## 📜 프로젝트 산출물

### 시스템 아키텍쳐
![image](https://github.com/user-attachments/assets/febeedc7-a5ce-40f8-bcc4-d4b1e995b8d0)



---

### ERD
![ORI ERD](https://github.com/user-attachments/assets/4af80514-bcdc-4719-928e-916c4fc8e9a6)



---

### 트러블 슈팅

<span style="color: #FF5733">🧾: [트러블 슈팅](https://backend-repository.tistory.com/category/%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4/AutoReview)</span>



## 👨‍💻  팀원 소개
| 신종신 | 최도혁 | 
| --- | --- |
| **Back-End** <br> - 소셜 로그인 및 회원 서비스 구현 <br> - TIL POST 서비스 구현 <br> - 프로메테우스 및 그라파나로 성능 지표 확인 <br>-  k6로 성능 테스트 | **Back-End** <br> - Code Post 서비스 구현 <br> - 댓글,복습 서비스 구현 <br> - FCM을 활용한 알림 서비스 구현 <br> - k6로 성능 테스트 <br> - DB 마이그레이션을 위해 Flyway 적용 |
| <span style="color: #FF5733">:octocat: [ArcticFoox의 GitHub](https://github.com/ArcticFoox)</span> | <span style="color: #33C1FF">:octocat: [최도혁의 GitHub](https://github.com/ehgur062300)</span>
