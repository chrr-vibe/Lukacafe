# Café Stille

루카스와 그의 작은 카페 · 2층 집 생활 게임 (도트, 한 파일).

## GitHub Pages 로 올리기
1. 새 저장소를 만들고 이 폴더 안의 파일을 전부 올립니다 (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `.nojekyll`).
2. 저장소 **Settings → Pages** 에서 Branch 를 `main` / `(root)` 로 저장합니다.
3. 잠시 후 `https://<아이디>.github.io/<저장소이름>/` 에서 열립니다.

## 오프라인
- 한 번 접속하면 서비스 워커가 파일을 저장해서, 그다음부터는 인터넷 없이도 열립니다.
- 휴대폰 브라우저 메뉴의 **홈 화면에 추가** 를 누르면 앱처럼 쓸 수 있어요.
- 그림·글꼴은 모두 `index.html` 안에 들어 있습니다.

## 업데이트할 때
`index.html` 을 바꾸면 `sw.js` 맨 위 `VERSION` 숫자를 하나 올려야 새 버전이 받아집니다.
저장 데이터는 브라우저 localStorage (`cafe-stille-game-v1`) 에 남아 있어서 업데이트해도 지워지지 않아요.

글꼴: Galmuri11 (SIL Open Font License 1.1, quiple).
