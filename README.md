<!-- ============================================================
  ✏️ 업로드 전에 바꿀 곳 (검색: TODO)
  1) 이메일 주소   2) 희망 직무 · 근무 지역 · 입사 가능 시기
============================================================ -->

<div align="center">

<!-- 상단 물결 배너 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,35:002b66,70:0052d4,100:00d2ff&height=250&section=header&text=Kim%20Do-young&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer%20%7C%20Java%20%C2%B7%20Spring%20Boot%20%C2%B7%20React&descAlignY=58&descSize=18" width="100%"/>

<!-- 타이핑 애니메이션 -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3000&pause=800&color=00D2FF&center=true&vCenter=true&width=620&lines=Java+%C2%B7+Spring+Boot+Backend;React+19+Frontend;Team+Leader+of+COMPILE;Always+learning%2C+always+building" alt="Typing SVG"/>

<br/>

<!-- 배지 1줄: 링크 -->
<a href="https://github.com/doyoung040257"><img src="https://img.shields.io/badge/GitHub-doyoung040257-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/doyoung040257/Crypto_Project"><img src="https://img.shields.io/badge/Flagship-COMPILE-00d2ff?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-Contact-0052d4?style=for-the-badge&logo=gmail&logoColor=white"/></a> <!-- TODO: 이메일 -->
<img src="https://komarev.com/ghpvc/?username=doyoung040257&label=Profile%20Views&color=00d2ff&style=for-the-badge"/>

<!-- 배지 2줄: 프로젝트 핵심 수치 -->
<img src="https://img.shields.io/badge/Team_Leader-6_members-002b66?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pages-13_routes-002b66?style=for-the-badge"/>
<img src="https://img.shields.io/badge/External_APIs-5-002b66?style=for-the-badge"/>
<img src="https://img.shields.io/badge/@Transactional-Trade_→_Portfolio-002b66?style=for-the-badge"/>

</div>

<br/>

### 👨‍💻 About Me

안녕하세요, **Java · Spring Boot**와 **React**로 서비스를 처음부터 끝까지 만들어 보는 개발자 **김도영**입니다.
6명이 함께한 암호화폐 모의투자 플랫폼 **COMPILE**에서 팀장을 맡아 요구사항 정리, ERD 설계부터
모의투자 거래 로직과 포트폴리오 계산까지 직접 구현했습니다.

```text
┌──────────────────────────────────────────────────────────────────────────┐
│  COMPILE // CRYPTO SIMULATED-TRADING PIPELINE                            │
├──────────────────────────────────────────────────────────────────────────┤
│  [SIGNUP]    중복 검증 (ID · Email · Phone)  →  가상 자산 10,000,000 KRW   │
│  [MARKET]    CoinGecko USD 시세 × 수출입은행 환율  →  KRW 시세 (Caffeine)   │
│  [TRADE]     매수 / 매도 요청  →  @Transactional 시작                       │
│  [COMMIT]    거래 저장 → 잔액 갱신 → 코인별 포트폴리오 → 총 자산 재계산       │
│  [RESULT]    평가 금액 · 손익 · 수익률  →  랭킹 보드 반영                    │
└──────────────────────────────────────────────────────────────────────────┘
```

- 🧱 **Backend & Data**: Spring Boot REST API, JPA 엔티티 설계, `@Transactional`로 데이터 정합성 확보
- ⚛️ **Frontend**: React Router SPA, Context API + `sessionStorage`로 로그인 상태 전역 관리
- 🔌 **API Integration**: CoinGecko · 환율 · CoinDesk · Gemini 등 외부 API를 하나의 서비스로 연결
- 🧭 **Leadership**: 6인 팀 팀장, 요구사항 분석 · 공통 프로세스 정의 · 발표 진행
- 💼 **Career Status**: 신입 개발자로 취업 준비 중 <!-- TODO: 입사 가능 시기 -->

<br/>

### 🌟 Tier 1: Core Flagship Project

<table>
  <tr>
    <th width="28%">Project & Core Domain</th>
    <th width="52%">Engineering Problem & Solution</th>
    <th width="20%">Direct Links</th>
  </tr>
  <tr>
    <td>
      <h4>🪙 <a href="https://github.com/doyoung040257/Crypto_Project">COMPILE</a></h4>
      암호화폐 모의투자 플랫폼<br/><br/>
      <img src="https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
      <br/><br/>
      <b>Role</b>: 팀장 · Full-Stack<br/>
      <b>Period</b>: 2025.12 ~ 2026.01<br/>
      <b>Team</b>: 6명
    </td>
    <td>
      <b>🎯 Problem</b><br/>
      기존 거래소는 전문가 중심이라 입문자가 연습할 공간이 없음<br/><br/>
      <b>🛠️ Solution</b><br/>
      • 가입 시 가상 자산 1천만 원 지급, 상위 20개 코인 KRW 시세로 매수·매도<br/>
      • 거래 → 잔액 → 포트폴리오 → 총 자산을 <code>@Transactional</code> 하나로 처리<br/>
      • 실시간 시세 기반 평가 금액 · 손익 · 수익률 자동 계산<br/>
      • Gemini AI 코인 분석, 코인 비교, 뉴스, 용어 사전, 랭킹 보드<br/><br/>
      <b>📌 Next</b><br/>
      API 호출 제한 → 캐싱·페이지네이션 확대, WebSocket 실시간 시세 전환
    </td>
    <td align="center">
      <a href="https://github.com/doyoung040257/Crypto_Project"><img src="https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github"/></a><br/><br/>
      <a href="https://github.com/doyoung040257/Crypto_Project/blob/main/docs/Compile_presentation.pdf"><img src="https://img.shields.io/badge/Slides-PDF-00d2ff?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/doyoung040257/Crypto_Project/main/docs/images/main.png" width="49%" alt="COMPILE 메인"/>
  <img src="https://raw.githubusercontent.com/doyoung040257/Crypto_Project/main/docs/images/trading.png" width="49%" alt="COMPILE 모의투자"/>
</p>

<!--
### 🧪 Tier 2: Engineering & Creative Lab
새 프로젝트가 생기면 아래 형식으로 추가하세요.
| Project | Description | Links |
|---|---|---|
| 프로젝트명 | 한 줄 설명 | [GitHub](링크) |
-->

<br/>

### 🛠️ Tech Stack & Architecture

**Backend & Database**<br/>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/>

**Frontend**<br/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white"/>
<img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white"/>

**API & Tools**<br/>
<img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/CoinGecko-8DC63F?style=for-the-badge&logo=coingecko&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white"/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,react,js,html,css,gradle,git,github,vscode,idea,postman&theme=dark"/>
</p>

<br/>

### 📊 GitHub Stats & Dynamic Activity

<table>
  <tr>
    <td><img src="https://github-stats-extended.vercel.app/api?username=doyoung040257&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=00d2ff&icon_color=00d2ff&hide_border=true" alt="GitHub Stats"/></td>
    <td><img src="https://github-stats-extended.vercel.app/api/top-langs/?username=doyoung040257&layout=compact&langs_count=8&theme=tokyonight&bg_color=0d1117&title_color=00d2ff&hide_border=true" alt="Top Languages"/></td>
  </tr>
</table>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=doyoung040257&theme=tokyonight&background=0d1117&ring=00d2ff&fire=ff007a&currStreakLabel=00d2ff&hide_border=true" alt="GitHub Streak"/>
</p>

<br/>

### 📬 Connect & Recruitment Information

- 💻 **GitHub**: [github.com/doyoung040257](https://github.com/doyoung040257)
- 📧 **Email**: your-email@example.com <!-- TODO -->
- 🎯 **희망 직무**: 백엔드 · 풀스택 개발자 <!-- TODO: 확인 -->
- 📍 **근무 지역**: 협의 가능 <!-- TODO -->
- 🗓️ **입사 가능 시기**: 즉시 가능 <!-- TODO -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d2ff,50:0052d4,100:090d16&height=120&section=footer" width="100%"/>

</div>
