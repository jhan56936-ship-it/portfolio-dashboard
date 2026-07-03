# AICS 포트폴리오 대시보드

기말평가 제출용 웹 대시보드입니다. `index.html` 파일 하나로 동작합니다 (빌드 불필요).

## 미리 보기

`index.html`을 더블클릭하면 브라우저에서 바로 열립니다.

## 내용 수정하기

`index.html`을 메모장/VS Code로 열고 `▼▼▼ 여기만 수정하면 됩니다 ▼▼▼` 부분을 찾으세요.

- **결과물 추가**: `PROJECTS` 배열에 항목 추가 (주석 처리된 템플릿 복사)
- **스크린샷 넣기**: `images` 폴더에 사진을 넣고 항목의 `img: "images/파일명.png"` 로 지정
- **성장 기록 수정**: `GROWTH` 객체의 배운 점 / 아쉬운 점 / 다음 목표 문장 수정
- **목표 개수**: 신규 학생은 `GOAL = 5`, 기존 팀프 학생은 `GOAL = 15`

## GitHub Pages 배포 (제출용 링크 만들기)

1. https://github.com/new 에서 새 저장소 생성 — 이름: `portfolio-dashboard`, Public 선택
2. 저장소 페이지에서 **Add file → Upload files** 로 이 폴더의 `index.html`(과 `images` 폴더)을 업로드 후 Commit
3. 저장소 **Settings → Pages** 이동
4. "Build and deployment" 에서 Source: **Deploy from a branch**, Branch: **main** / **(root)** 선택 후 Save
5. 1~2분 뒤 접속 확인:

   **https://jhan56936-ship-it.github.io/portfolio-dashboard/**

이 링크가 제출용 대시보드 주소입니다.

## 채점 기준 체크리스트 (안내문 기준)

- [x] 결과물 개수 — 카드 개수가 상단에 자동 표시됨 (현재 5개 ✅)
- [ ] 링크 접속 — GitHub Pages 배포 후 링크 확인
- [x] 결과물 확인 — 카드마다 플레이 링크 / GitHub 링크 / 썸네일
- [x] 짧은 설명 — 카드마다 1~2문장 설명
- [x] 성장 기록 — 배운 점 / 아쉬운 점 / 다음 목표
