포트폴리오 사이트 (정적)

생성된 파일:
- `index.html` — 홈
- `about.html` — 소개
- `contact.html` — 연락처
- `css/styles.css` — 스타일

로컬에서 확인 (macOS):
```bash
# 파일 열기
open index.html
```

GitHub Pages로 배포 (빠른 방법):
1. GitHub에서 새 레포지토리를 만듭니다 (예: `my-portfolio`).
2. 로컬에서 아래 명령을 실행:
```bash
cd portfolio-site
git init
git add .
git commit -m "initial portfolio"
git branch -M main
# 원격 repo URL을 추가하세요
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```
3. GitHub 레포지토리의 Settings → Pages에서 Branch: `main` / Folder: `root` 선택 후 저장하면 몇 분 내에 사이트가 올라옵니다.

참고:
- 맞춤 도메인 사용 시 `CNAME` 파일을 추가하세요.
- 폼(백엔드)이 필요하면 Netlify Forms 또는 간단한 이메일 처리 서비스를 연결할 수 있습니다.
