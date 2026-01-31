# 📚 semicolon – 2인 팀 중간 프로젝트 (2019 · 아카이브용)

이 프로젝트는 2019년 진행된 **2인 팀 중간 프로젝트**로,  
웹 애플리케이션의 기본 구조와 기능을 실습하기 위해 제작되었습니다.

2026년 현재 기준으로 코드를 다시 보관(Archive)하고자 GitHub에 업로드한 프로젝트이며,  
일부 기능은 미완성 상태로 남아 있으며 당시 구현 수준 그대로 보존되어 있습니다.

---
## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Servlet](https://img.shields.io/badge/Servlet-6DB33F?style=for-the-badge)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)
![MVC](https://img.shields.io/badge/MVC-000000?style=for-the-badge)

### Database
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### Tools
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)
![Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

### Frontend
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🙋‍♀️ My Contributions (내가 담당했던 기능)

프로젝트 당시, 저는 주로 다음과 같은 기능들을 개발했습니다.

### 🔹 1. 로그인 및 세션 처리 구현
- 사용자 로그인/로그아웃 기능 일부 구현
- 세션 기반 사용자 상태 유지 처리
- 로그인 시 유효성 검사 로직 작성

### 🔹 2. 좋아요(Like) 기능 초안 작성
- 특정 게시물에 대한 좋아요 토글 기능 구현
- UI에서 좋아요 반영 확인
- 좋아요 수 증가/감소 처리 일부 참여

### 🔹 3. 페이징 처리 로직 일부 구현
- 게시글 목록에 대한 페이지 이동 처리
- DAO에서 LIMIT/OFFSET로 데이터 조회
- 페이지 번호 UI 구성 일부 담당

### 🔹 4. 게시판 CRUD 일부 구현
- 게시글 등록(Create) · 조회(Read) 기능 구현
- Controller → DAO 흐름 일부 구성
- JSP 뷰 페이지 일부 작업

### 🔹 5. 기타 작업
- JSP UI · HTML 구조 일부 정리
- 테스트 과정에서 오류 수정 발생 시 대응
- 단위 기능별 데이터 흐름 이해 및 실습 중심 참여

---

## 🛠 사용 기술

- **Java**
- **JSP / Servlet**
- **MVC 아키텍처**
- **ORACLE SQL**
- **Tomcat**
- **jQuery / AJAX**

---

## 📁 프로젝트 구조 요약

(아카이브 목적상 세부 구조는 단순화하여 정리)

```
semicolon/
├── src/
│   ├── controller/      # 로그인/게시판 등 컨트롤러
│   ├── dao/             # DB 접근
│   ├── dto/             # VO/DTO
│   ├── service/         # 비즈니스 로직
│   └── webapp/          # JSP 페이지
└── …
```

---

## 🔍 주요 기능 요약

- 로그인/로그아웃 기능(초안)  
- 좋아요 기능 기본 구현  
- 게시판 CRUD 일부 구현  
- 페이징 처리 일부 구현  
- UI(View) 일부 구성  

---

## ⚙️ 실행 방법

1. Eclipse에서 Dynamic Web Project로 Import  
2. ORACLE SQL 연결 설정 수정  
3. Tomcat 서버에서 Run on Server

※ 현재는 개발 환경 차이로 실행이 어려울 수 있으며,  
본 프로젝트는 **아카이브(기록) 목적**으로 업로드되었습니다.

---

## 📝 프로젝트 상태 (2026 기준)

- 당시 구현 완료되지 못한 기능 존재  
- 현재는 유지보수하지 않으며, 학습 기록용으로 보관  
- 코드 스타일 및 구조는 2019년 당시 학습 수준을 반영

---

## 💬 회고 (현재 시점)

- 팀 프로젝트에서 MVC 흐름을 처음 경험하며 구조화된 개발에 익숙해짐  
- 좋아요 기능, 페이징 등 기본 웹 서비스 기능 작동 원리를 이해  
- 지금은 FastAPI · Tortoise ORM 기반의 비동기 웹 개발로 더 확장된 기술을 학습 중  
- 과거 프로젝트들을 보관함으로써 성장의 과정을 확인할 수 있었음

---

## 📬 Contact

- GitHub: https://github.com/chachacheese  
- Velog: https://velog.io/@jiiiin0  
- Email: 10sim_2@naver.com
