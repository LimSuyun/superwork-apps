# superwork 앱 모아보기

Superwork Workflow로 만든 앱을 소개하는 단일 페이지입니다. (출시 13종 + 출시 예정 2종)

## 구성
- `index.html` — 페이지 전체 (HTML/CSS/JS 한 파일). 폰트(Pretendard)만 CDN에서 불러옵니다.
- `assets/icons/` — 앱 아이콘
- `assets/shots/` — 앱 썸네일(스크린샷)
- `assets/qr/` — 앱별 QR 코드

## 로컬에서 보기
`index.html`을 더블클릭하거나 브라우저로 열면 됩니다.

## GitHub Pages 배포
1. GitHub에서 새 저장소 생성 (예: `superwork-apps`)
2. 이 폴더를 push
   ```bash
   git remote add origin https://github.com/<사용자명>/<저장소명>.git
   git push -u origin main
   ```
3. 저장소 → **Settings → Pages** → Source를 `main` 브랜치 `/ (root)`로 지정
4. 잠시 뒤 `https://<사용자명>.github.io/<저장소명>/` 에서 공개됩니다.

> 자산 경로가 모두 상대경로(`assets/...`)라 저장소 이름과 상관없이 그대로 동작합니다.
