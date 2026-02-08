# sonic-state

```
src/
├── components/          # 공통 UI 컴포넌트 (UI만 담당, 로직 X)
│   ├── PlayerBar.tsx
│   ├── SongList.tsx
│   └── VolumeControl.tsx
├── app/
│   ├── page.tsx         # 메인 (라이브러리 선택 페이지)
│   ├── redux/           # Redux Toolkit 구현 페이지
│   ├── zustand/         # Zustand 구현 페이지
│   ├── recoil/          # Recoil 구현 페이지
│   └── jotai/           # Jotai 구현 페이지
└── stores/              # 라이브러리별 스토어 로직 분리
    ├── reduxSlice.ts
    ├── useZustandStore.ts
    ├── recoilAtoms.ts
    └── jotaiAtoms.ts
```
