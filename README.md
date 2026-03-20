# CodeCompose Main Site

코드컴포즈 앱 포트폴리오 사이트 — 완전 커스텀 Hugo 테마

- **URL**: <https://codecompose.net/>
- **테마**: 커스텀 (Things-inspired, 테마 없음)
- **호스팅**: GitHub Pages
- **배포**: GitHub Actions (자동)

## 로컬 개발

### Docker (권장)

```bash
docker compose up
```

`http://localhost:1313` 에서 확인. 파일 수정 시 라이브 리로드 자동 적용.

### Hugo 직접 실행

```bash
hugo server -D --bind 0.0.0.0 --port 1313 --baseURL http://localhost:1313
```

## 프로젝트 구조

```text
.
├── .github/workflows/hugo.yml   # CI/CD
├── assets/css/main.css          # 전체 스타일
├── layouts/
│   ├── _default/                # baseof, single, list
│   ├── apps/section.html        # 앱 랜딩 페이지 (Things-style)
│   ├── partials/                # nav, footer
│   └── index.html               # 홈 페이지
├── content/
│   ├── apps/
│   │   ├── flowstate-ai/        # 랜딩 + Privacy + Terms
│   │   └── focus-capsule/       # 랜딩 + Privacy
│   └── about/
├── static/img/                  # 로고, 앱 아이콘
└── hugo.toml
```

## 앱 페이지 추가하기

`content/apps/새앱/` 폴더를 만들고 `_index.en.md`에 front matter로 features, pricing, highlights를 정의하면 레이아웃이 자동으로 Things-style 랜딩 페이지를 생성합니다.

## 배포

`main` 브랜치에 push → GitHub Actions 자동 빌드·배포

### 최초 설정

1. Settings → Pages → Source: **GitHub Actions**
2. (나중에) Custom domain: `codecompose.net`
