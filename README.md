## Hi there 👋
안녕하세요.
<div align="center">
  <h3>STACKS</h3>
</div>

<div align="center">
  <!-- 언어 (Languages) -->
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <br>
  
  <!-- 프론트엔드 & 디자인 (Frontend & Design) -->
  <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white">    
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
  <br>

  <!-- 백엔드 & 데이터베이스 (Backend & Databases) -->
  <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <br>

  <!-- 데브옵스 & 협업 (DevOps & Collaboration) -->
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/amazon%20aws-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
  <img src="https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
  <img src="https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
</div>
    
  <!-- [![Solved.ac Profile](http://mazassumnida.wtf/api/generate_badge?boj=gack)](https://solved.ac/gack) -->
---

<div align="center">
  <h3> [만화당] 만화 추천 서비스 </h3>
  <p>2025.12 / 2인 팀프로젝트</p>

  <details>
    <summary><b>💡 한줄 소개: 사용자 취향 분석 기반 만화 추천 및 커뮤니티 AI SaaS</b></summary>

  <div align="left">

  <br>

  <h2>✨ 핵심 구현 및 성과</h2>

  <h3>🤖 LangChain 기반 고품질 번역 파이프라인</h3>
  <ul>
    <li>영어로 제공되는 만화 데이터를 자연스러운 한국어로 변환하기 위한 번역 시스템 구축.</li>
    <li>기존 Google·DeepL 기계번역은 만화 도메인 특유의 고유명사·문맥·뉘앙스를 살리지 못하는 한계가 명확했습니다.</li>
    <li>이를 <b>LangChain 파이프라인 + 프롬프트 엔지니어링</b>으로 전환하여 장르와 문맥을 온전히 반영한 고품질 번역을 구현하고 서비스 퀄리티를 끌어올렸습니다.</li>
  </ul>

  <h3>🎯 투트랙(Two-Track) 맞춤 추천 Engine</h3>
  <p>입체적인 큐레이션을 위해 두 갈래의 추천 엔진을 디자인하고 구현했습니다.</p>
  <ol>
    <li>
      <b>가중치 기반 콘텐츠 필터링</b>
      <ul>
        <li>온보딩 단계에서 선택한 만화들의 장르·테마 빈도를 분석하여 개인별 선호 가중치 도출.</li>
        <li><code>장르 유사도 60% + 테마 유사도 30% + 대중성 보정 10%</code> &rarr; 100점 만점의 개인화 적합도 산출.</li>
        <li><b>다양성 확보:</b> 상위 30개 후보군에서 가중치 무작위 추출(Weighted Random Selection) 방식을 도입해 사용자에게 매번 새로운 발견의 즐거움 제공.</li>
      </ul>
    </li>
    <li>
      <b>초개인화 AI 추천 (LLM 연동)</b>
      <ul>
        <li>MBTI, 선호 그림체, 스토리 전개 속도, 인생작, 평점 등 심층 취향 데이터를 가공하여 LLM 컨텍스트로 전달.</li>
        <li>단순한 제목 나열 방식을 탈피하여 <b>"왜 이 만화가 당신의 취향에 맞는지(Personalized Reason)"</b>에 대한 정성적인 추론 사유를 담은 프리미엄 리포트 동적 생성.</li>
      </ul>
    </li>
  </ol>

  <h3>⚡ 시각화 & 렌더링 최적화</h3>
  <ul>
    <li><b>메인 3D 배경 애니메이션:</b> 순수 WebGL 구현 시 발생하는 최적화 및 런타임 성능 한계를 극복하기 위해 Unicorn Studio를 활용하여 웹 성능 저하 없이 화려한 비주얼 구현.</li>
    <li><b>이미지 로딩 최적화:</b> 대용량 정적 리소스들을 CDN 캐싱 처리하여 클라이언트 전송량을 대폭 절감하고 초기 렌더링 성능 확보.</li>
  </ul>

  <br>

  <h2>🛠️ 시스템 아키텍처 및 데이터 모델링</h2>
  <table width="100%">
    <thead>
      <tr>
        <th width="25%">레이어</th>
        <th width="75%">역할 및 구현 내용</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Frontend (Vue 3)</b></td>
        <td>컴포넌트 단위 대시보드 UI 구성, 실시간 인기 랭킹(TOP 50) 및 커뮤니티 통계 시각화 수립</td>
      </tr>
      <tr>
        <td><b>Backend (Django DRF)</b></td>
        <td>RESTful API 설계, CORS 최적화 및 인프라 분리를 위한 Railway 독립 배포망 구축</td>
      </tr>
      <tr>
        <td><b>AI / Data</b></td>
        <td>Jikan API 연동, 외부 API Rate Limit 우회를 위한 로컬 DB 캐싱, LLM 추천/번역 파이프라인 관리</td>
      </tr>
    </tbody>
  </table>

  <h4>💡 데이터 모델링 핵심 포인트</h4>
  <ul>
    <li><code>Manga</code>: 외부 API 호출 지연 및 Rate Limit 차단을 방지하기 위한 메타데이터 로컬 캐싱 계층 역할.</li>
    <li><code>UserPreference</code> / <code>UserGenrePreference</code>: 유저와 관심 만화 간 N:M 관계 저장 및 장르별 가중치 자동 연산 구조 설계.</li>
    <li><code>PremiumSurveyResponse</code> / <code>PremiumReport</code>: 유저의 심층 설문 데이터 보관 및 생성된 추천 결과물 JSON 영속화.</li>
    <li><code>CommunityPost</code> / <code>MangaInteraction</code>: 게시판 활동 로그 및 조회·클릭 행동 데이터를 수집하여 향후 실시간 트렌드 점수 알고리즘에 반영 가능한 구조 설계.</li>
  </ul>

  <br>

  <h2>💡 트러블 슈팅</h2>

  > ### 🔥 LLM API 호출 지연 최적화 (Bottleneck 해결)
  > **문제 상황:** 고비용의 AI 번역 및 초개인화 추천 연산이 실시간으로 수행될 때 심각한 응답 지연(Bottleneck)이 발생하여 사용자 경험 저하 유발.
  >
  > **해결 방안:** 매번 무거운 AI 연산을 반복하지 않도록, 한번 생성된 번역 데이터와 프리미엄 리포트 결과물 전체를 JSON 구조로 규격화하여 로컬 데이터베이스에 캐싱(Look-Aside Pattern) 처리.
  >
  > **성과:** 중복 요청 시 DB 캐시를 통해 즉각 응답하도록 아키텍처를 개선하여 API 호출 비용을 획기적으로 절감하고 페이지 로딩 속도를 극대화 달성.

  > ### 🌐 분리 배포 환경에서의 CORS 및 Mixed Content 이슈
  > **문제 상황:** 프론트엔드(Vercel)와 백엔드(Railway)를 독립된 환경으로 분리 배포하는 과정에서 CORS 및 HTTPS Mixed Content 통신 에러 발생.
  >
  > **해결 방안:** 백엔드 시스템의 `django-cors-headers` 설정을 기반으로 `CORS_ALLOWED_ORIGINS`에 Vercel 도메인을 명시하였고, 프론트-백 배포 인프라 간 환경 변수를 정확히 매핑하여 크로스 오리진 상황에서의 안정적인 HTTPS 통신 궤도 확보.

  <br>

  <h2>📝 프로젝트 회고</h2>
  <p>
    크롤러로 시작한 데이터 수집 구조를 효율적인 외부 API 아키텍처로 점진적 교체하고, 단순 번역 API의 표현력 한계를 LLM 파이프라인으로 해결해가며 <b>"상황에 맞게 시스템 구조를 유연하게 변경하고 문제를 주도적으로 해결하는 능력"</b>을 깊이 있게 길렀습니다.
  </p>
  <p>
    WebGL의 대안으로 Unicorn Studio를 발굴하여 적용하고 대용량 에셋들을 CDN으로 우회 처리해 보면서 프로덕션 레벨에서의 트래픽 최적화가 얼마나 중요한지 몸소 체감할 수 있었습니다. 프론트엔드의 매끄러운 사용자 인터랙션부터 백엔드의 AI 프롬프트 체인 설계, 그리고 클라우드 분산 배포 환경 제어까지 웹 서비스의 전체 라이프사이클을 밀도 있게 경험한 뜻깊은 프로젝트였습니다.
  </p>

  <br>
  <hr />
  <br>

  </div>

  <p align="center">
    <img width="400" alt="메인페이지" src="https://github.com/user-attachments/assets/88061d30-f506-44c4-89e1-df9519689e0b" />
    <img width="400" alt="어떤만화가 더 끌리나요" src="https://github.com/user-attachments/assets/28905c29-797b-4a12-b69f-4ec4b5e8d18d" />
    <img width="400" alt="추천만화결과" src="https://github.com/user-attachments/assets/1a552c81-bc2b-4d35-8aec-48e4f0fa901e" />
    <img width="400" alt="커뮤니티" src="https://github.com/user-attachments/assets/0bea30eb-425a-437a-be9a-351c62681f12" />
    <img width="400" alt="통합검색" src="https://github.com/user-attachments/assets/77ce31db-37f8-4fec-9bdb-04718711afac" />
    <img width="400" alt="프리미엄 리포트" src="https://github.com/user-attachments/assets/c16a4500-3c4d-4e5c-8f05-9557f38ca21d" />
  </p>

  </details>
</div>

---

<div align="center">
  <h3>[ProTalkAll] 비지니스 언어매너 학습 프로그램</h3>
  <p>2026.01 ~ 2026.02 / 6인 팀프로젝트</p>
  
  <!-- 토글 시작 (가운데 정렬 포함) -->
  <details>
  <summary style="cursor: pointer;"><b>💡 한줄 소개: 사회초년생을 위한 비즈니스 언어 학습 및 케어 AI SaaS</b></summary>
  
  <!-- 상세 내용은 왼쪽 정렬로 가독성 확보 -->
  <div align="left" style="max-width: 600px; margin: 20px auto; padding: 0 10px;">
    <hr>
    <h3>🛠️ 담당 역할</h3>
    <ul>
      <li><b>프론트엔드 개발 및 UI/UX 디자인, 기획 및 전체 파이프라인(API, ERD, QC) 참여</b></li>
      <li>Figma 기반의 엄격한 디자인 시스템 구축</li>
      <li>SaaS 환경에 맞는 반응형/접근성 고려</li>
    </ul>
    <hr>
  </div>

  <!-- 이미지는 다시 가운데 정렬 -->
  <p align="center">
      <img width="400"  alt="스크린샷 2026-02-06 145028" src="https://github.com/user-attachments/assets/33ac947f-ccb4-44c4-bc91-8eda4a452323" />
      <img width="400"  alt="스크린샷 2026-02-05 152723" src="https://github.com/user-attachments/assets/0e11e788-b6d3-4a0a-b9e1-88dd73d283ed" />
      <img width="400"  alt="스크린샷 2026-02-05 102951" src="https://github.com/user-attachments/assets/127fbffe-2996-4ef7-8066-2bc157a1bed9" />
      <img width="400"  alt="스크린샷 2026-02-05 103034" src="https://github.com/user-attachments/assets/e560186c-100b-47e5-ad91-3fefb8937ca9" />
      <img width="400"  alt="스크린샷 2026-02-04 145602" src="https://github.com/user-attachments/assets/955e0827-8f3f-4b01-8a9d-25a4002d85fc" />
      <img width="400"  alt="image" src="https://github.com/user-attachments/assets/dd6e3376-7172-4893-8ad1-530d963d1911" />
      <img width="400"  alt="image (1)" src="https://github.com/user-attachments/assets/e692c5d2-f94e-42a8-bd5f-d2009776c2ec" />


  </p>

  </details>
  <!-- 토글 끝 -->
</div>



---
<div align="center">

### [공모러] 공모주 투자 정보제공 모바일웹
2026.02 ~ 2026.04 / 6인 팀프로젝트

<details>
<summary style="cursor: pointer; text-align: center; list-style: none;"><b>💡 한줄 소개: 공모주 투자자를 위한 정보 제공 AI Mobile Web</b></summary>

<br>

<div align="left" style="max-width: 800px; margin: 0 auto; padding: 0 10px;">
<h2>💡 트러블 슈팅</h2>


### 🚨 문제 상황
* 커뮤니티 게시판의 좋아요 기능 구현 시, 게시물 목록과 상세 페이지 이동 간에 좋아요 상태가 초기화되거나, 클릭 시 좋아요 개수가 일시적으로 줄어들었다가 다시 늘어나는 '화면 깜빡임(경쟁 상태)' 현상 발생.

### 🔍 원인 분석
* 클라이언트 로컬 상태(`useState`)와 서버 상태(API)를 혼용하여 **단일 진실 공급원(Single Source of Truth)** 원칙 위배.
* 좋아요 Mutation 실행 후 서버의 응답 지연 시간 동안 이전 캐시 데이터가 화면을 덮어쓰는 **비동기 경쟁 상태(Race Condition)**가 원인임을 진단.

### 🛠️ 해결 방법
* 클라이언트 로컬 상태를 제거하고 **React Query의 캐시를 기준으로 상태 관리를 일원화**.
* 사용자 경험(UX) 개선을 위해 **낙관적 업데이트(Optimistic Update)**를 적용: API 요청 즉시 UI를 우선 갱신하고, 진행 중인 백그라운드 리패치 쿼리를 강제 취소(`cancelQueries`)하여 깜빡임 제거.
* API 에러 시 Context에 백업된 이전 데이터로 자동 롤백 처리하는 예외 처리 구현으로 안정성 확보.

### ✨ 성과 및 느낀점
* 네트워크 지연 속도에 상관없이 즉각적이고 부드러운 인터랙션을 제공하게 되었으며, 복잡한 비동기 캐시 상태를 안정적으로 제어할 수 있게 됨.

</div>

---

<!-- 이미지는 다시 가운데 정렬 -->
<div align="center">

<img width="240" alt="공모주 상세" src="https://github.com/user-attachments/assets/79dd0292-3479-4f3d-b1f3-a324e55f4a0b" /> <img width="240" alt="IPO Info Home Screen" src="https://github.com/user-attachments/assets/d1a013e5-137f-4ba9-b35d-8599fcf340ee" /> <img width="240" alt="알림내역 관리" src="https://github.com/user-attachments/assets/3446e76a-f022-451e-ba67-ad2d6361bd44" />

</div>

</details>

</div>


---

<div align="center">

### [Ausori] 오디오 효과음 자동 매칭 서비스
2026.04 ~ 2026.06 / 6인 팀프로젝트 (SSAFY 전시발표회 발표부문 3등 / 자율 프로젝트 1등)

<details>
<summary style="cursor: pointer; text-align: center; list-style: none;"><b>💡 한줄 소개: 영상만 넣으면 오디오 효과음을 AI가 자동으로 배치해주는 SaaS</b></summary>

<br>

<div align="left" style="max-width: 800px; margin: 0 auto; padding: 0 10px;">


## 1. 프로젝트 개요 (Overview)
### 💡 기획 배경 및 문제 정의
유튜브, 틱톡, 인스타그램 등 1인 미디어 크리에이터 시장이 급격히 성장하면서 영상 편집의 수요가 폭발적으로 증가했습니다. 하지만 영상의 몰입도를 결정하는 **사운드 디자인(효과음/폴리/배경음 배치)**은 다음과 같은 비효율이 존재합니다.
* **시간 낭비**: 수만 개의 효과음 플랫폼에서 키워드로 사운드를 일일이 검색하고 청취해야 합니다.
* **전문성 요구**: 타임라인에 정확한 타이밍으로 배치하고, 볼륨 믹싱 및 트랙 분리를 하는 과정은 고도의 편집 숙련도가 필요합니다.
* **진입 장벽**: 이러한 사운드 작업의 난이도로 인해 많은 초급 크리에이터들이 사운드 디자인을 생략하거나 단순하게 처리하여 영상 품질 저하를 겪습니다.
---

## 2. 핵심 기능 (Key Features)
1. **AI 멀티모달 기반 자동 사운드 디자인**
   * 영상을 업로드하면 1fps 단위 프레임 및 컷 편집점을 감지하여 장면 맥락 분석.
   * **6트랙 분류 모델**: 대사(Voice), 음악(BGM), 배경 분위기음(Ambience), 일상 행동음(Foley), 연출 효과음(SFX), 극적 연출음(Cinematic)을 구분하여 타임라인에 최적 배치.
   * 각 사운드 이벤트마다 **Top 3~5개의 대체 사운드 후보군** 및 **신뢰도(Confidence)** 매칭.
2. **웹 기반 고성능 멀티트랙 사운드 에디터**
   * Canvas API(Konva) 기반의 매끄러운 캔버스 조작을 통한 멀티트랙 타임라인 인터페이스 제공.
   * AI가 제안한 사운드 블록을 드래그 앤 드롭으로 타이밍 미세 조정 가능.
   * 클릭 한 번으로 AI가 제안한 대체 사운드 목록에서 교체 지원.
   * 트랙별 볼륨 믹서 및 마스터 렌더링.
---

## 3. 기술 스택 (Tech Stack)
### Client (Frontend)
* **Framework**: Next.js 16 (App Router)
* **Language**: TypeScript
* **State Management**: Zustand
* **Graphics / UI**: Tailwind CSS v4, Lucide-React, Recharts (데이터 대시보드)
* **Canvas Library**: Konva, React-Konva (고성능 타임라인 편집 캔버스 렌더링)
* **Media Processing**: @ffmpeg/ffmpeg (브라우저 내 클라이언트 사이드 미디어 유틸리티)
* **Authentication**: @react-oauth/google (구글 소셜 로그인)
### Server (Backend)
* **Runtime**: Node.js (v22 LTS)
* **Language**: TypeScript
* **Framework**: Express 5.1.0
* **Database**: PostgreSQL (pg), Redis (connect-redis를 활용한 고성능 세션 관리 및 작업 큐)
* **Storage**: AWS S3 (Presigned URL을 통한 비디오/오디오 소스 보안 전송)
* **Validation**: Zod (타입 안정성을 갖춘 요청 본문 및 환경 변수 검증)
* **Payment**: Toss Payments SDK
### AI Worker Server
* **Language**: Python 3
* **Queue / Broker**: Redis Pub/Sub, Redis Polling (비동기 배치 워커)
* **Models / APIs**: Google Generative AI (Gemini 2.5 Flash 기반의 멀티모달 영상 맥락 요약 및 큐 시트 작성), VLM(Visual Language Model) 분석 엔진
* **Audio Tech**: pyloudnorm (Loudness Normalize), Soundfile, Scipy, Numpy, Librosa
* **Observability**: Langfuse (AI 응답 추적, 프롬프트 엔지니어링 성능/비용 모니터링)
---

## 4. 핵심 기술 구현 및 문제 해결 (Technical Accomplishments)
### 🛠️ 1. Redis Queue 기반의 비동기 AI 파이프라인 아키텍처
* **문제**: 영상 분석 및 사운드 매칭(멀티모달 모델 호출, 오디오 매칭 검색 등)은 연산이 무겁고 수십 초에서 수 분의 시간이 소요되므로 동기식 HTTP 요청으로 처리 시 타임아웃 발생 및 서버 자원 고갈 위험이 컸습니다.
* **해결**: Express 백엔드와 Python AI Worker를 철저하게 격리했습니다. 백엔드가 S3 업로드 후 **Redis 작업 큐(Job Queue)**에 작업을 생성하면, 비동기 파이프라인 워커가 이를 순차적으로 가져가(Polling) 분석을 수행하도록 설계했습니다.
* **결과**: 무거운 연산 중에도 백엔드는 즉각 클라이언트에 작업 등록 응답을 주어 높은 연결 안정성을 확보하였으며, Redis를 통해 클라이언트에게 `scene_splitting -> analyzing -> matching -> done` 형태로 실시간 진행 상태(Progress)를 피드백하는 완성도 높은 UX를 구현했습니다.
### 🔬 2. Soft & Hard 트랙 분리 및 2-Cycle 프롬프트 파이프라인
* **문제**: 오디오의 성격에 따라 필요한 공간적 특징(예: 바람 소리, 카페 소음 등 지속적인 Ambience)과 행동적 특징(예: 발소리, 총소리, 타격음 등 순간적인 Foley)이 다릅니다. 이 모든 소리를 하나의 프롬프트나 동일한 알고리즘으로 추출하려 하면 환각(Hallucination) 현상이 발생하거나 타이밍의 정교함이 어긋났습니다.
* **해결**: 사운드를 **Soft 트랙**(배경음, 음악, 연출 드론)과 **Hard 트랙**(발소리, 동작음, 순간 SFX)으로 완전 분리하고, **2-Cycle** 분석을 설계했습니다.
  * **1-Cycle (글로벌 분석)**: 영상 전체 프레임을 보고 영상 장르, 전반적 분위기, 주요 공간을 파악하여 글로벌 Context JSON 생성.
  * **2-Cycle (구간/행동 분석)**: 1-Cycle Context를 주입받아 특정 컷 구간의 영상만을 세부적으로 다시 스캐닝하여 카테고리(category_path)와 시간대, 설명(description)을 정밀하게 추출.
* **결과**: AI 분석의 정밀도가 크게 상승하였고, 영상 내에서 쌩뚱맞은 사운드가 매칭되는 문제를 크게 개선했습니다.
### 🔍 3. 벡터 임베딩 유사도 검색을 활용한 사운드 추천 시스템
* **문제**: LLM이 사운드 파일명을 직접 지목하게 하는 것은 파일명이 변경되거나 새로운 사운드 에셋이 추가되는 경우 유연하게 대처할 수 없으며 정확한 선택이 불가능했습니다.
* **해결**: AI 분석 파이프라인을 **"현상 분석 및 요구 사운드 기술(Text Description)"**과 **"실제 사운드 검색(Search Retrieval)"**의 두 레이어로 분리했습니다.
  * AI Worker는 장면에 필요한 소리를 텍스트 설명(ex: *"인물이 콘크리트 바닥을 걸으며 착지하는 발소리"*)과 카테고리로 정의합니다.
  * 사운드 라이브러리의 모든 에셋에 대해 사전에 텍스트 임베딩을 구축하고, **벡터 검색 유사도 매칭**을 수행해 카테고리가 일치하면서 가장 유사도가 높은 최적 사운드를 검색합니다.
* **결과**: AI 모델 변경이나 사운드 라이브러리 추가가 있더라도 시스템 수정 없이 완벽히 호환되는 확장성 있는 아키텍처를 설계했습니다.
### 🎨 4. Canvas API (Konva) 기반의 고성능 멀티트랙 타임라인 에디터
* **문제**: HTML5 Element 기반으로 사운드 블록(Div)을 만들어 수많은 트랙 위에 렌더링하면, 줌인/줌아웃, 여러 사운드의 동시 드래그 조작 및 스크롤 시 브라우저 Reflow로 인해 성능 저하와 버벅임이 유발되었습니다.
* **해결**: Canvas 2D 기반 드로잉 래퍼 라이브러리인 **Konva**와 **React-Konva**를 활용해 전체 에디터 타임라인 영역을 캔버스로 구성했습니다.
* **결과**: 수십 개의 사운드 노드 배치 및 실시간 파형(Waveform) 드로잉 연산 시에도 끊김 없이 60fps에 가까운 반응성을 보여주며 쾌적한 사운드 조작 경험을 제공했습니다.
---




## 5. 프로젝트 성과 및 성장 포인트 (Growth Points)
* **도메인 지식의 융합**: AI 분석에 단순히 프롬프트 하나를 쓰는 데 머무르지 않고, 전문 음향 제작 단계의 큐 시트(Cue Sheet) 개념과 Soft/Hard 사운드 파이프라인의 개념을 결합하여, 실제 현업에서 사용할 수 있는 현실적인 MVP 구조를 직접 설계했습니다.
* **비파괴 편집(Non-destructive Editing) 아키텍처 수립**: AI가 오디오를 직접 인코딩하여 영상을 합쳐 주는 무거운 구조 대신, 백엔드와 프론트엔드 간에 시간 데이터(JSON 타임라인)만을 교환하고 클라이언트 브라우저 단에서 재생/편집을 담당하며 최종 렌더링 시점에만 최종 오디오를 생성하도록 설계하여 엄청난 서버 비용 절감 및 무한 수정 가능한 환경을 제공했습니다.
* **관측 가능성(Observability) 도입**: LLM 호출이 많은 프로젝트 특성상 **Langfuse**를 통합하여 파이프라인 내 단계별 프롬프트의 토큰 비용, Latency 및 환각 발생 빈도를 효과적으로 트래킹하고 프롬프트를 고도화할 수 있었습니다.


</div>

---

<!-- 이미지는 다시 가운데 정렬 -->
<div align="center">

<img width="2659" height="1186" alt="image (2)" src="https://github.com/user-attachments/assets/bf177796-27fc-4cfc-8f0f-1804c5b19a32" />
<img width="2862" height="1508" alt="스크린샷 2026-05-29 092503" src="https://github.com/user-attachments/assets/ecae030d-219a-4940-a9f2-e7dccf94bbc2" />
<img width="877" height="806" alt="스크린샷 2026-05-30 184300" src="https://github.com/user-attachments/assets/69d7f309-96a0-4c80-8a44-cc4ba598775e" />
<img width="2871" height="1511" alt="스크린샷 2026-05-29 092533" src="https://github.com/user-attachments/assets/1c14ff27-b1f0-44fb-8dfb-b9d1365f53a6" />


</div>

</details>

</div>


---
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<div  align=center> 
<a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=kmuchi&utm_content=farm">
<img
  src="https://render.gitanimals.org/farms/kmuchi"
  width="600"
  height="300"
/>
</a>
</div>

<!--
**Kimchi78/kimchi78** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
