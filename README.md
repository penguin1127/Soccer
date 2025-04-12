# Soccer
src/
├── app/                      # 🆕 앱 진입점 관련 파일 이동
│   ├── App.tsx              # 👉 기존 src/App.tsx → 이동
│   └── main.tsx             # 👉 기존 src/main.tsx → 이동

├── components/              # 🆕 공통 컴포넌트 영역
│   ├── layout/              # Header, Layout 등 공통 레이아웃
│   │   └── Header.tsx       # 🆕 새로 생성 예정
│   ├── common/              # SearchBar, Card 등 재사용 컴포넌트
│   └── ui/                  # shadcn UI 라이브러리 컴포넌트 (자동 생성)

├── features/                # 🆕 도메인별 기능 영역
│   ├── mercenary/
│   │   ├── components/
│   │   └── pages/
│   ├── team/
│   └── match/

├── routes/                  # 🆕 라우터 구성
│   └── AppRouter.tsx        # 🆕 새로 생성

├── assets/                  # ✅ 그대로 유지 (이미지, 폰트 등)
│   └── (기존 이미지 파일)

├── constants/               # 🆕 지역, 포지션 등 상수 정의
├── mock/                    # 🆕 목업 데이터 파일 (JSON 또는 .ts)
├── stores/                  # 🆕 Zustand 등 전역 상태 관리
├── lib/                     # 🆕 axiosInstance, utils 함수 등
├── styles/                  # (선택) Tailwind 커스텀 정의용 파일 위치
│   └── (선택: tailwind.theme.ts 등)

├── index.css                # ✅ 그대로 유지
├── vite-env.d.ts            # ✅ 그대로 유지
