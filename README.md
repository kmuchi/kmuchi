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

## 🚀 Projects

<!-- 큰 제목과 토글 버튼 라인까지만 깔끔하게 가운데 정렬하고 바로 닫기 -->
<div align="center">
  <h3> [만화당] 만화 추천 서비스 </h3>
  <p>2025.12 / 2인 팀프로젝트</p>
</div>

<details>
  <!-- summary 태그 안에 직접 텍스트 가운데 정렬 스타일을 부여합니다 -->
  <summary style="cursor: pointer; text-align: center;"><b>💡 한줄 소개: 사용자 취향 분석 기반 만화 추천 및 커뮤니티 AI SaaS</b></summary>

  <br>

  <!-- 여기서부터는 감싸는 div가 없으므로 자동으로 깔끔하게 왼쪽 정렬됩니다 -->
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

  <!-- 시스템 아키텍처 -->
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

  <!-- 트러블 슈팅 -->
  <h2>💡 트러블 슈팅</h2>

  <div style="background-color: #f6f8fa; padding: 16px; border-left: 4px solid #dddee1; margin-bottom: 16px;">
    <h3>🔥 LLM API 호출 지연 최적화 (Bottleneck 해결)</h3>
    <p><b>문제 상황:</b> 고비용의 AI 번역 및 초개인화 추천 연산이 실시간으로 수행될 때 심각한 응답 지연(Bottleneck)이 발생하여 사용자 경험 저하 유발.</p>
    <p><b>해결 방안:</b> 매번 무거운 AI 연산을 반복하지 않도록, 한번 생성된 번역 데이터와 프리미엄 리포트 결과물 전체를 JSON 구조로 규격화하여 로컬 데이터베이스에 캐싱(Look-Aside Pattern) 처리.</p>
    <p><b>성과: 중복 요청 시 DB 캐시를 통해 즉각 응답하도록 아키텍처를 개선하여 API 호출 비용을 획기적으로 절감하고 페이지 로딩 속도를 극대화 달성.</b></p>
  </div>

  <div style="background-color: #f6f8fa; padding: 16px; border-left: 4px solid #dddee1; margin-bottom: 16px;">
    <h3>🌐 분리 배포 환경에서의 CORS 및 Mixed Content 이슈</h3>
    <p><b>문제 상황:</b> 프론트엔드(Vercel)와 백엔드(Railway)를 독립된 환경으로 분리 배포하는 과정에서 CORS 및 HTTPS Mixed Content 통신 에러 발생.</p>
    <p><b>해결 방안:</b> 백엔드 시스템의 <code>django-cors-headers</code> 설정을 기반으로 <code>CORS_ALLOWED_ORIGINS</code>에 Vercel 도메인을 명시하였고, 프론트-백 배포 인프라 간 환경 변수를 정확히 매핑하여 크로스 오리진 상황에서의 안정적인 HTTPS 통신 궤도 확보.</p>
  </div>

  <br>

  <!-- 회고 -->
  <h2>📝 프로젝트 회고</h2>
  <p>
    크롤러로 시작한 데이터 수집 구조를 효율적인 외부 API 아키텍처로 점진적 교체하고, 단순 번역 API의 표현력 한계를 LLM 파이프라인으로 해결해가며 <b>"상황에 맞게 시스템 구조를 유연하게 변경하고 문제를 주도적으로 해결하는 능력"</b>을 깊이 있게 길렀습니다.
  </p>
  <p>
    WebGL의 대안으로 Unicorn Studio를 발굴하여 적용하고 대용량 에셋들을 CDN으로 우회 처리해 보면서 프로덕션 레벨에서의 트래픽 최적화가 얼마나 중요한지 몸소 체감할 수 있었습니다. 프론트엔드의 매끄러운 사용자 인터랙션부터 백엔드의 AI 프롬프트 체인 설계, 그리고 클라우드 분산 배포 환경 제어까지 웹 서비스의 전체 라이프사이클을 밀도 있게 경험한 뜻깊은 프로젝트였습니다.
  </p>

  <br>
  <!-- 이미지 분리를 위한 가로 구분선 -->
  <hr />
  <br>

  <!-- 이미지 섹션 부분만 콕 집어서 가운데 정렬 지정 -->
  <div align="center">
    <img width="400" alt="메인페이지" src="https://github.com/user-attachments/assets/88061d30-f506-44c4-89e1-df9519689e0b" />
    <img width="400" alt="어떤만화가 더 끌리나요" src="https://github.com/user-attachments/assets/28905c29-797b-4a12-b69f-4ec4b5e8d18d" />
    <img width="400" alt="추천만화결과" src="https://github.com/user-attachments/assets/1a552c81-bc2b-4d35-8aec-48e4f0fa901e" />
    <img width="400" alt="커뮤니티" src="https://github.com/user-attachments/assets/0bea30eb-425a-437a-be9a-351c62681f12" />
    <img width="400" alt="통합검색" src="https://github.com/user-attachments/assets/77ce31db-37f8-4fec-9bdb-04718711afac" />
    <img width="400" alt="프리미엄 리포트" src="https://github.com/user-attachments/assets/c16a4500-3c4d-4e5c-8f05-9557f38ca21d" />
  </div>

</details>

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
      <img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/dd6e3376-7172-4893-8ad1-530d963d1911" />
        <img width="400" height="300" alt="image (1)" src="https://github.com/user-attachments/assets/e692c5d2-f94e-42a8-bd5f-d2009776c2ec" />
        <img width="400" height="300" alt="스크린샷 2026-02-06 145028" src="https://github.com/user-attachments/assets/33ac947f-ccb4-44c4-bc91-8eda4a452323" />
        <img width="400" height="300" alt="스크린샷 2026-02-05 152723" src="https://github.com/user-attachments/assets/0e11e788-b6d3-4a0a-b9e1-88dd73d283ed" />

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
