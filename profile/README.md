
## 📌 프로젝트 개요

**HANA**는 외국인 유학생을 위한 통합 플랫폼으로,  
AI 챗봇 기반으로 학사 정보, 학과 정보, 비자 안내, 생활 정보 등을 다국어로 제공합니다.

> 유학생들이 한국 생활에서 겪는 정보 파편화 문제를 해결하고,  
> 원활한 학업 및 생활 정착을 도와주는 것이 목표입니다.

- 🎯 대상: 한국 유학 중이거나 유학 준비 중인 외국인 유학생
- 🚀 개발 기간: 2025년 4월 ~ 6월

---

## 👥 팀 멤버 소개

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/yousrchive">
        <img src="https://github.com/yousrchive.png" width="100" style="border-radius: 50%"/><br/>
        <strong>yousrchive(이유정)</strong>
      </a><br/>
      프론트엔드 리드
    </td>
    <td align="center">
      <a href="https://github.com/harry-nb">
        <img src="https://github.com/harry-nb.png" width="100" style="border-radius: 50%"/><br/>
        <strong>harry-nb(김도현)</strong>
      </a><br/>
      PM
    </td>
    <td align="center">
      <a href="https://github.com/dmkang1225">
        <img src="https://github.com/dmkang1225.png" width="100" style="border-radius: 50%"/><br/>
        <strong>dmkang1225(강동민)</strong>
      </a><br/>
      백엔드 리드
    </td>
    <td align="center">
      <a href="https://github.com/EuiInSeong">
        <img src="https://github.com/EuiInSeong.png" width="100" style="border-radius: 50%"/><br/>
        <strong>EuiInSeong(성의인)</strong>
      </a><br/>
      AI 리드
    </td>
  </tr>
</table>

---

## 🧭 서비스 구성 안내

HANA는 프론트엔드와 백엔드가 분리된 구조로 구성되어 있으며, 각 레포지토리에 구현 상세 및 실행 방법이 정리되어 있습니다.

| 구분 | 레포지토리 | 주요 기술 | 설명 |
|------|-------------|-----------|------|
| 💻 프론트엔드 | [`frontend-hana`](https://github.com/HANA-by-teamname/frontend-hana) | Next.js 14, React, Tailwind CSS | 유학생이 직접 사용하는 웹 화면 (홈, 챗봇, 시간표 등) |
| ⚙️ 백엔드 | [`backend-hana`](https://github.com/HANA-by-teamname/backend-hana) | Node.js, Express, MongoDB, Python | 사용자 관리, 게시물 처리, 챗봇 API 등 서버 기능 구현 |

---

## 🚀 실행 흐름 요약

1. **프론트엔드**는 `Next.js` 기반 App Router 구조로 페이지를 구성하고, 로그인/챗봇/검색 등 UI를 제공합니다.
2. **백엔드**는 `Express.js + MongoDB` 기반 API 서버로, AI 챗봇(Python + Ollama + Pinecone)까지 통합되어 있습니다.
3. **배포 환경**:  
   - 프론트엔드: Vercel  
   - 백엔드: AWS EC2  
   - 데이터베이스: MongoDB Atlas  
   - LLM & 벡터 DB: Ollama, Pinecone

---

## 🔗 빠른 이동 링크

- 👉 [프론트엔드 실행 가이드 보기](https://github.com/HANA-by-teamname/frontend-hana#-실행-가이드)
- 👉 [백엔드 실행 가이드 보기](https://github.com/HANA-by-teamname/backend-hana#-설치-및-실행-방법)
- 👉 [Postman API 문서 보기](https://github.com/HANA-by-teamname/backend-hana#-api-문서)

---

## 🎥 서비스 데모 영상

<p align="center">
  <a href="https://youtu.be/uGVYhXbuHk0">
    <img src="https://img.youtube.com/vi/uGVYhXbuHk0/0.jpg" width="480" alt="서비스 데모 영상 썸네일"/>
  </a>
</p>

---

## 🎨 서비스 화면 미리보기

<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/sprint.png" width="300"/><br/>
      <b>스프린트</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/login.png" width="300"/><br/>
      <b>로그인 화면</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/error.png" width="300"/><br/>
      <b>오류 안내</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/signup_select.png" width="300"/><br/>
      <b>회원가입 선택 화면</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/signup_onboarding.png" width="300"/><br/>
      <b>회원가입 온보딩 화면</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/home.png" width="300"/><br/>
      <b>홈 화면</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/search.png" width="300"/><br/>
      <b>검색</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/search_filter.png" width="300"/><br/>
      <b>검색 필터</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/chatbot.png" width="300"/><br/>
      <b>챗봇</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/mypage_auth.png" width="300"/><br/>
      <b>마이페이지 - 재학생 인증</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/timetable.png" width="300"/><br/>
      <b>시간표 등록</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/HANA-by-teamname/frontend-hana/main/asset/kakao.png" width="300"/><br/>
      <b>카카오톡 연동</b>
    </td>
  </tr>
</table>
