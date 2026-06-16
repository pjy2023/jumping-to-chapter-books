# Jumping to Chapter Books

빛들을 위한 영어 리더스북 학습 사이트.
리더스북 자막을 기반으로 단어 카드, 영한 스토리, 퀴즈를 제공합니다.

## 배포 URL

> GitHub Pages 배포 후 아래에 URL을 입력하세요.
> `https://<GitHub-username>.github.io/<repo-name>/`

## 폴더 구조

```
/
├── index.html              # 메인 허브 (시리즈 선택)
├── arthur/
│   ├── index.html          # 아서 시리즈 목록
│   ├── arthur-big-snow.html
│   ├── arthur-birthday-surprise.html
│   ├── arthur-helps-out.html
│   ├── arthur-jelly-beans.html
│   ├── arthur-tells-a-story.html
│   └── arthur-workflow.html   # 내부 도구 (신규 권 생성기)
└── henry-mudge/
    ├── index.html          # 헨리앤머지 시리즈 목록
    ├── henry-mudge-big-test.html
    └── henry-mudge-long-weekend.html
```

## 시리즈 현황

| 시리즈 | 완성 | 총 권수 | 대표색 |
|--------|------|---------|--------|
| 아서 (Arthur) | 5 | 13 | #FF8C42 |
| 헨리앤머지 (Henry & Mudge) | 2 | 8 | #2EC4B6 |

## 학습 페이지 구성

각 권별 페이지는 3탭 구조:
- **Words** — 단어 카드 + TTS 발음 + 검색
- **Story** — 영한 나란히, 문장별 한국어 토글
- **Quiz** — 영어 객관식 10문제 + 점수

## 기술 스택

- 순수 HTML / CSS / JS (빌드 도구 없음)
- Google Fonts — Fredoka One, Nunito, Noto Sans KR
- Web Speech API (브라우저 내장 TTS)

## GitHub Pages 배포 방법

1. 이 저장소를 GitHub에 push
2. 저장소 Settings → Pages → Source: `main` 브랜치, `/ (root)` 폴더 선택
3. Save 후 1~2분 대기
4. 위 배포 URL에서 사이트 확인
