# Solepli Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Google Cloud](https://img.shields.io/badge/google%20cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

<br>

### sole + place/play + list, 혼놀러를 위한 장소 추천 및 큐레이션 서비스 Solepli

<br>

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f776a9c3-382d-439f-8cc1-dc9d327995b3" />

<br>

## 📋 목차

- [📖 프로젝트 개요](#-프로젝트-개요)
- [👤 팀원](#-팀원)
- [💡 주요 기능](#-주요-기능)
- [🖥️ 화면 UI](#️-화면-ui)
- [⚙️ 기술 스택 & 아키텍처](#️-기술-스택--아키텍처)
- [🧪 QA & UT](#-qa--ut)
- [⭐ 설치 및 실행](#-설치-및-실행)

---

# 📖 프로젝트 개요

> [!IMPORTANT]
> Solepli(쏠플리)는 '혼놀러'가 혼자 방문하기 좋은 장소를 쉽고 편리하게 찾을 수 있도록 만든 장소 추천 및 큐레이션 서비스입니다.

2-30대를 중심으로 혼자 시간을 즐기는 활동이 일상화되고 있지만, 기존 지도 서비스는 '1인 이용자'라는 상황을 충분히 고려하지 않아 혼자 방문하기 좋은 곳인지 판단하기 어렵다는 문제에서 출발했습니다. <br>
사용자는 장소를 탐색하고 저장할 수 있으며, 자신의 경험을 글과 사진으로 기록하고 공유할 수 있습니다. 또한 나만의 혼놀 코스를 직접 생성하거나 다른 사용자가 만든 코스를 활용할 수 있습니다.

<br>

---

## 👤 팀원

<table align="center">
  <tr>
    <td align="center" width="200">
      <a href="https://github.com/sky121016">
        <img src="https://github.com/sky121016.png" width="120" height="120" style="border-radius: 50%;" alt="sky121016"/>
      </a>
      <br />
      <a href="https://github.com/sky121016"><strong>홍수민</strong></a>
      <br />
      <sub><b>Frontend Leader</b></sub>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/DandelionQZ">
        <img src="https://github.com/DandelionQZ.png" width="120" height="120" style="border-radius: 50%;" alt="양희정"/>
      </a>
      <br />
      <a href="https://github.com/DandelionQZ"><strong>양희정</strong></a>
      <br />
      <sub><b>Frontend Dev</b></sub>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/lth-1026">
        <img src="https://github.com/lth-1026.png" width="120" height="120" style="border-radius: 50%;" alt="이태호"/>
      </a>
      <br />
      <a href="https://github.com/lth-1026"><strong>이태호</strong></a>
      <br />
      <sub><b>Frontend Dev</b></sub>
    </td>
  </tr>
</table>

<br>

---

## 💡 주요 기능

### 🗂️ Sollect - 사용자 경험 기반의 큐레이션 커뮤니티

- 지역·장소·카테고리별로 쏠렉트(큐레이션 게시물)를 검색하고 열람
- 다녀온 장소에 대한 경험을 글과 사진으로 기록
- 다른 사용자의 쏠렉트를 저장하거나, 쏠렉트 속 장소들을 쏠루트로 한 번에 저장

### 🗺️ Solmap - 혼자 방문하기 좋은 장소만 담은 맞춤형 지도

- 네이버 지도 API 기반 커스텀 마커 렌더링 및 카테고리 탐색
- 1인 방문자 리뷰 기반의 분위기·1인 이용 태그로 장소 정보 요약 제공
- 키워드/지역 검색, 현재 위치 기반 주변 장소 추천

### 🧭 Solroute - 나만의 혼놀 코스 리스트 생성 및 조회

- 쏠맵·쏠렉트에서 모은 장소로 나만의 혼놀 코스 생성
- 장소 추가 시 동선을 지도에 실시간 시각화, 장소별 메모 작성
- 추가한 장소 근처의 인기 장소 추천

### ❤️ Solmark - 저장한 쏠렉트 및 장소 모아보기

- 저장한 장소·쏠렉트·작성한 쏠렉트를 한 곳에서 관리
- 리스트를 만들어 저장 항목을 폴더처럼 그룹화

<br>

---

## 🖥️ 화면 UI

> 혼자 방문하기 좋은 장소를 탐색·기록·공유하는 쏠플리의 핵심 화면입니다.

### Sollect
| SOLLECT_HOME | SOLLECT_WRITE | SOLLECT_DETAIL |
| :--: | :--: | :--: |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/534a8868-4381-4eaa-9863-902151d68cb7" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d63ca86-47a1-412b-a0a0-d0e17e9bc7e7" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5ffaf7b8-ca3f-4420-85a0-9591345c6f8e" /> |

### Solmap
| SOLMAP_HOME & SOLMAP_SEARCH | SOLMAP_DETAIL | SOLMAP_REVIEW |
| :--: | :--: | :--: |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/127f2aed-8b97-4af7-bd25-69756f6b2500" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/001e6700-5148-43cc-8ed4-70e4cf07c0bd" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/37138790-8cda-454d-a3ba-ae743bcc69fe" /> |

### Solroute
| SOLROUTE_LIST & SOLROUTE_DETAIL | SOLROUTE_CREATE |
| :--: | :--: |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4fdce937-34d5-429c-a344-48cd7d057543" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/63c327ae-30c8-49bc-9849-fda263ebef12" /> |

### Solmark & Profile
| SOLMARK_HOME | PROFILE | 
| :--: | :--: | 
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35a2d472-8731-4384-8f47-58ceb8161546" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0eacf9d6-5384-4e7b-982a-af58ce66f6ff" /> | 

<br>

---

# ⚙️ 기술 스택 & 아키텍처

## 📦 기술 스택

> [!TIP]
> Vite 기반의 가벼운 빌드 환경 위에서, Zustand와 React Query로 클라이언트/서버 상태를 분리해 관리했습니다.

### ⚡ Framework & Language

- **Vite**: 빠른 HMR과 빌드 속도를 위한 번들러
- **React 19 / TypeScript**: 컴포넌트 기반 UI 및 타입 안정성 확보

### 🎨 Styling & State

- **Tailwind CSS v4**: 유틸리티 클래스 기반의 빠른 스타일링
- **Zustand**: 마커, 검색, 바텀시트 등 도메인별 클라이언트 상태 관리
- **React Query**: 서버 상태 캐싱 및 API 연동 (`@tanstack/react-query`)
- **Axios**: API 통신 클라이언트

### 🗺️ Map & 기타 라이브러리

- **Naver Maps API**: 지도 렌더링, 커스텀 마커, bounds/zoom 제어
- **@hello-pangea/dnd**: 쏠루트 장소 순서 변경 드래그앤드롭
- **yet-another-react-lightbox**: 이미지 라이트박스
- **react-router-dom**: 클라이언트 라우팅

### 🛠️ Code Quality & Tools

- **ESLint & Prettier**: 코드 품질 유지 및 팀 컨벤션 자동 적용
- **vite-plugin-svgr**: SVG를 React 컴포넌트로 변환하여 관리

<br>

## 📁 디렉토리 구조

```text
src
├── api          # 도메인별 API 모듈 (mapApi, placeApi, reviewApi, solrouteApi ...)
├── auth         # 인증 관련 로직
├── components   # 공통/도메인 컴포넌트
├── hooks        # 커스텀 훅
├── layout       # 레이아웃 컴포넌트
├── pages        # 라우트 단위 페이지 (Solmap, SollectPage, SolmarkPage ...)
├── routes       # 라우터 설정 및 인증 가드
├── store        # Zustand 스토어 (mapStore, markerStore, searchStore ...)
└── utils        # 유틸 함수
```

<br>

## 🏗️ System Architecture (Front-end)

Naver Cloud Map API와 통신하는 React + TypeScript 애플리케이션을 GitHub Actions로 빌드해 Docker 이미지로 만들고, Google Cloud Platform(Workload Identity Federation 기반 인증)의 Cloud Run에 배포하는 구조입니다.

<img width="1920" height="1080" alt="2026-06-30_16-11-43" src="https://github.com/user-attachments/assets/bfbd6860-d896-4987-86ba-5ee73ec99c97" />

- **CI/CD**: GitHub Actions로 Docker 이미지를 빌드해 Artifact Registry에 Push, Cloud Run으로 배포
- **인증**: Workload Identity Federation을 통해 별도의 키 파일 없이 GitHub Actions에서 GCP 리소스에 접근
- **배포 리전**: `asia-northeast3`

<br>

---

# 🧪 QA & UT

서비스 정식 배포 전, 기능별 QA 점검표와 함께 실제 사용자를 대상으로 한 UT(User Test)를 진행해 화면별 개선사항을 도출했습니다.

- **Sollect**: 쏠렉트 가로 스크롤 시 클릭되는 듯한 모션 개선, 검색 결과 썸네일과 주소 매칭 오류 수정 등
- **Solmap**: 지도 이동 시 '이 지역에서 검색' 버튼 가시성 개선, 바텀시트 스크롤 중 지도 새로고침 방지, 검색 결과 없음 시 추천 장소 노출 수정, 주요 아이콘 크기 확대 등
- **Solroute / Profile**: 화면별 우선순위·개발 난이도를 함께 기록해 백로그로 관리

발견된 문제는 우선순위와 개발 난이도를 함께 기록해 백로그로 관리했으며, 이는 추후 개선 작업의 기준이 되었습니다.

<br>

---

# ⭐ 설치 및 실행

## 📋 필수 환경

> [!WARNING]
> 프로젝트 실행 전에 반드시 아래 환경을 확인해주세요.

- **Node.js 18** 이상
- **npm**

```bash
# 환경 확인
node -v
npm -v
```

<br>

## 💾 설치 과정

1. Repository 클론

```bash
git clone https://github.com/Solepli/Solepli-frontend.git
cd Solepli-frontend
```

2. 의존성 설치

```bash
npm install
```

3. 개발 서버 실행

```bash
npm run dev
```

<br>

> [!NOTE]
> 네이버 지도 API 등 외부 서비스 연동을 위한 환경 변수(.env) 설정이 별도로 필요합니다.

<br>

## 📜 기타 명령어

```bash
npm run build     # 타입 체크 + 프로덕션 빌드
npm run lint       # ESLint 검사
npm run preview    # 빌드 결과 미리보기
```

---

<div align="center">

<img width="1920" height="1080" alt="2026-06-30_16-14-56" src="https://github.com/user-attachments/assets/2e2b7a1d-a441-4305-a0d1-28bff5ab253b" />

</div>
