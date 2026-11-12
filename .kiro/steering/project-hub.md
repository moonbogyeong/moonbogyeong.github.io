# PLAYON 프로젝트 — 기록 허브 안내 (Steering)

이 파일은 Kiro가 새 대화를 시작할 때 **프로젝트 기록 허브의 위치**를 바로 찾도록 돕는 steering 메모입니다.

## 내 기록 허브 (Notion)

- 허브 페이지 이름: **🎮 PLAYON 프로젝트 기록 (허브)**
- 허브 페이지 URL: https://app.notion.com/p/409c12f04b8281ae8fe6fa5285419426
- 허브 페이지 ID: `409c12f0-4b82-81ae-8fe6-fa5285419426`

새 대화에서 "Steering에서 허브 위치를 확인하고 실제 페이지를 읽어 줘"라고 하면,
위 Notion 페이지 ID를 `notion-fetch`로 읽어 현재 상태·다음 할 일을 파악한 뒤 이어서 작업합니다.

## 프로젝트 기본 정보

- 프로젝트: **PLAYON** — 브라우저에서 바로 즐기는 레트로 미니게임 아케이드
- 로컬 폴더: `moonbogyeong.github.io`
- 첫 화면 파일: `index.html` (단일 파일에 대부분의 게임·UI·로직이 들어 있음)
- 독립 게임 파일(iframe으로 로드): `star.html`, `arena.html`, `pizza.html`, `pacman.html` — **삭제 금지**
- GitHub 저장소: https://github.com/moonbogyeong/moonbogyeong.github.io
- 공개 사이트:
  - GitHub Pages: https://moonbogyeong.github.io/
  - Vercel: https://moonbogyeonggithubio.vercel.app
  - Netlify: https://incredible-sprinkles-106e36.netlify.app

## 작업 규칙

- 개인정보(이메일·학번 등)와 비밀 키(Supabase secret key 등)는 코드·기록에 넣지 않는다.
  - Supabase publishable key(`sb_publishable_…`)는 브라우저 노출이 전제된 저권한 키라 index.html에 있어도 됨.
- 커밋/푸시는 사용자가 요청할 때만 수행한다.
- 작업을 마치면 사용자가 요청할 경우 Notion 허브의 **작업 로그 / 현재 상태 / 다음 할 일**을 갱신하고,
  저장 후 같은 페이지를 다시 읽어(`notion-fetch`) 반영 여부를 확인한다. 원래 기록은 지우지 말고 날짜로 추가한다.
