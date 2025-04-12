# ⚽ Sport-Hub Frontend

조기축구 인원/용병/경기 모집을 위한 플랫폼 **Sport-Hub**의 프론트엔드 프로젝트입니다.  
**Vite + React + TypeScript + Tailwind CSS + shadcn** 기반으로 구축되었습니다.

---

## 🚀 기술 스택

- **Frontend**: React + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + shadcn/ui
- **State Management**: Zustand (도입 예정)
- **Routing**: React Router v6
- **API 요청**: Axios (with instance)
- **기타**: 모듈 alias 설정 (`@/` → `src/`)

---

## 📁 디렉토리 구조

```bash
src/
├── app/                      # 앱 진입점 관련 설정 (App.tsx, main.tsx 등)
├── components/               # 공통 컴포넌트
│   ├── layout/               # Header, Layout 등
│   ├── common/               # SearchBar, Card 등
│   └── ui/                   # shadcn에서 생성된 컴포넌트
├── features/                 # 도메인별 기능
│   ├── mercenary/            # 용병
│   ├── team/                 # 팀
│   └── match/                # 경기
├── routes/                   # 라우팅 정의
├── stores/                   # Zustand 등 상태관리
├── mock/                     # mock 데이터
├── constants/                # 상수 데이터 (지역 목록 등)
├── lib/                      # axiosInstance, utils 등
├── styles/                   # 전역 스타일 및 Tailwind 커스터마이징
├── assets/                   # 정적 리소스 (이미지, 아이콘 등)
├── index.css                 # Tailwind 엔트리
├── vite-env.d.ts             # Vite 타입 정의
