# 집사의 역습 — 배포 폴더

정적 파일만 있으면 됩니다. 빌드 단계는 필요 없습니다.

- `index.html` — 게임 전체(HTML/CSS/JS 단일 파일)
- `icon.png` — 파비콘 및 홈 화면 아이콘
- `netlify.toml` — Netlify에서 이 폴더를 그대로 배포하도록 설정

## Netlify 배포

1. 이 `deploy` 폴더를 Netlify에 올립니다(Drop 또는 Git 연결 시 Base directory를 `deploy`로 지정).
2. Build command는 비우고, Publish directory는 `.`(또는 `deploy`)입니다.
3. 배포 후 루트 주소에서 바로 게임이 실행됩니다.
