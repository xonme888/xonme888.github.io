# xonme888.github.io

나승후의 개인 포트폴리오 사이트입니다.

🔗 **Live**: https://xonme888.github.io

## 구성

- 단일 `index.html` 정적 페이지 — 빌드 단계 없음
- Tailwind CSS Play CDN
- Pretendard Variable 한글 폰트
- 다크 테마 기본, 반응형, IntersectionObserver 기반 reveal 애니메이션

## 콘텐츠 수정

`index.html` 한 파일만 편집하면 됩니다. 주요 수정 지점:

| 섹션 | 위치 |
|------|------|
| 한 줄 소개 / hero 텍스트 | `<!-- Hero -->` 블록 |
| 자기소개 본문 | `<!-- About -->` 블록 |
| 프로젝트 카드 | `<!-- Project N: ... -->` 블록 |
| 기술 스택 | `<!-- Skills -->` 블록 |
| 연락처 | `<!-- Contact -->` 블록 |

## 배포

`main` 브랜치 루트의 `index.html`을 GitHub Pages가 자동으로 서빙합니다.

```bash
git add .
git commit -m "update content"
git push origin main
```

푸시 후 1~2분 뒤 https://xonme888.github.io 에 반영됩니다.
