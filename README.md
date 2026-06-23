# typography

SIHM 디자인 시스템의 **폰트 / 타이포그래피 규칙** 문서입니다. Pretendard 기준으로
타입 스케일(10토큰)과 굵기(4단계), line-height·자간 규칙을 한 페이지에 정리했습니다.

`index.html` 한 파일로 동작하며 별도 서버·빌드가 필요 없습니다. 노션에는 이 파일이
호스팅된 URL(GitHub Pages)을 embed 하세요.

## 노션 embed URL

```
https://doyeon-herlab.github.io/typography/
```

(GitHub → repo Settings → Pages → Branch `main` / root 로 한 번 켜면 활성화됩니다.)

## 구성

- **Typeface** — Pretendard, 4단계 굵기(Regular 400 / Medium 500 / SemiBold 600 / Bold 700)
- **Type scale** — Display, Heading 1~4, Body Large/Body/Body Small, Caption/Caption Small (총 10토큰)
- **원칙** — 굵기 4단계 고정, line-height(제목 130% / 본문 170% / 캡션 150%), 한글 자간(-1% 기본, ≥20px -2%), 소수점 크기 금지

## 토큰 요약

| 토큰 | size | weight | line-height | letter-spacing |
|------|------|--------|-------------|----------------|
| `text-display`     | 30px | 700 | 120% | -2% |
| `text-heading1`    | 24px | 700 | 130% | -2% |
| `text-heading2`    | 20px | 600 | 130% | -2% |
| `text-heading3`    | 18px | 600 | 130% | -1% |
| `text-heading4`    | 17px | 600 | 130% | -1% |
| `text-body-lg`     | 16px | 400 | 170% | -1% |
| `text-body`        | 15px | 400 | 170% | -1% |
| `text-body-sm`     | 14px | 400 | 170% | -1% |
| `text-caption`     | 12px | 400 | 150% | -1% |
| `text-caption-sm`  | 11px | 400 | 150% | -1% |

> 위 size는 ≥1600px(2xl) 기준입니다. base 크기와 마이그레이션 매핑은 페이지를 참고하세요.

Pretendard 웹폰트는 jsDelivr CDN에서 불러옵니다(설치 불필요).
