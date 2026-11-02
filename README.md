# 프레시카트 업무 포털

구매팀 업무 포털 — 부진재고 · 거래처 마진율 · 마감 업로드 · 업무일지

- 화면: `index.html` (GitHub Pages로 배포)
- 로그인·자료 저장: Firebase (Authentication, Firestore)
- 보안 규칙: `firestore.rules` — Firebase 콘솔의 Firestore Database → 규칙 탭에 붙여넣어 게시

회사 자료(재고·단가·매핑표 등)는 이 저장소에 두지 않고 Firebase에만 저장합니다.
