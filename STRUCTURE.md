# STRUCTURE — cherishon-sample

## 배포
- 레포: github.com/Daorl8/cherishon-sample → Cloudflare 연결(사용자 단계) → cherishon-sample.lgt3232.workers.dev
- 단일 파일 정적 사이트. wrangler.toml(name=cherishon-sample, [assets] directory="./") + .assetsignore(실내용).

## 파일
- index.html — 전체 사이트(CSS·JS 인라인).
- ch-hero.jpg — 히어로(벽돌 간판 brunch & coffee). ch-store.jpg — 오시는 길 외관.
- ch-01.jpg ~ ch-16.jpg — 메뉴/갤러리/마퀴 공용 브런치·공간 컷. 매핑=_manifest.json(원본 IG 파일명, 서빙 제외).
- ch-logo.png — 손그림 로고(셰프+체리+CHERISH ON) 투명. ch-mark.png — 셰프 일러스트 크롭(헤더/파비콘).
- pretendard-sub.woff2 — Pretendard 서브셋(한글 self-host).
- CHANGELOG.md / STRUCTURE.md / _manifest.json — 문서(서빙 제외).

## 섹션
헤더 → #top/히어로 → 마퀴 → #about → #menu → #gallery → #info → #location → 푸터 → 모바일 퀵바.

## 색 / 폰트
- bg #FBF8F1 / brick #a85d50(brick-d #8c4a3f) / sage #7f8b6a / ink #2b2521 / line #e7dfd0.
- Fraunces(라틴, Google CDN) + Pretendard(한글, self-host 서브셋). 폴백 안전 산세리프.

## 원본 소스
- IG 원본(hash 파일명)은 상위 cherishon-sample/ 폴더 보관, 레포엔 ch-*만 커밋.
