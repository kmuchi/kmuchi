## Hi there 👋
안녕하세요.
<div  align=center><h3>STACKS</h1></div>

<div  align=center> 
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<br>
<img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white">    
<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
    
  <!-- [![Solved.ac Profile](http://mazassumnida.wtf/api/generate_badge?boj=gack)](https://solved.ac/gack) -->

## 🚀 Projects

### 📚 [만화당] 만화 추천 커뮤니티 (2025.12)
> **한줄 소개:** 사용자 취향 분석 기반 만화 추천 및 커뮤니티 서비스.
</div>

---

<div align="center">
  <h3>[ProTalkAll] 비지니스 언어매너 학습 프로그램</h3>
  <p>2026.01 ~ 2026.02 / 6인 팀프로젝트</p>

  <br>

  <!-- 토글 시작 (가운데 정렬 포함) -->
  <details open>
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
  <h3>[공모러] 공모주 투자 정보제공 모바일앱</h3>
  <p>2026.01 ~ 2026.02 / 6인 팀프로젝트</p>

  <br>

  <!-- 토글 시작 (가운데 정렬 포함) -->
  <details open>
  
  <!-- 상세 내용은 왼쪽 정렬로 가독성 확보 -->
  <div align="left" style="max-width: 600px; margin: 20px auto; padding: 0 10px;">
    <hr>
      <summary style="cursor: pointer;"><b>💡 한줄 소개: 공모주 투자자를 위한 정보 제공 AI Mobile App</b></summary>
    <ul>
            문제: 커뮤니티 게시판의 좋아요 기능 구현 시, 게시물 목록과 상세 페이지 이동 간에 좋아요 상태가 초기화되거나, 클릭 시 좋아요 개수가 일시적으로 줄어들었다가 다시 늘어나는 '화면 깜빡임(경쟁 상태)' 현상 발생.
            원인:
            클라이언트 로컬 상태(useState)와 서버 상태(API)를 혼용하여 단일 진실 공급원(Single Source of Truth) 원칙 위배.
            좋아요 Mutation 실행 후 서버의 응답 지연 시간 동안 이전 캐시 데이터가 화면을 덮어쓰는 비동기 경쟁 상태(Race Condition)가 원인임을 진단.
            해결:
            클라이언트 로컬 상태를 제거하고 React Query의 캐시를 기준으로 상태 관리를 일원화.
            사용자 경험(UX) 개선을 위해 **낙관적 업데이트(Optimistic Update)**를 적용: API 요청 즉시 UI를 우선 갱신하고, 진행 중인 백그라운드 리패치 쿼리를 강제 취소(cancelQueries)하여 깜빡임 제거.
            API 에러 시 Context에 백업된 이전 데이터로 자동 롤백 처리하는 예외 처리 구현으로 안정성 확보.
            성과: 네트워크 지연 속도에 상관없이 즉각적이고 부드러운 인터랙션을 제공하게 되었으며, 복잡한 비동기 캐시 상태를 안정적으로 제어할 수 있게 됨.
    </ul>
    <hr>
  </div>

  <!-- 이미지는 다시 가운데 정렬 -->
  <p align="center">
        <img width="390" height="1531" alt="공모주 상세 - 기본 정보 탭 (1)" src="https://github.com/user-attachments/assets/79dd0292-3479-4f3d-b1f3-a324e55f4a0b" />
        <img width="390" height="1139" alt="IPO Info Home Screen" src="https://github.com/user-attachments/assets/d1a013e5-137f-4ba9-b35d-8599fcf340ee" />
        <img width="410" height="985" alt="알림내역 관리 (2안) (1)" src="https://github.com/user-attachments/assets/3446e76a-f022-451e-ba67-ad2d6361bd44" />

  </p>

  </details>
  <!-- 토글 끝 -->
</div>



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
