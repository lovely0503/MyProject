---
title: 포트폴리오 Vercel 배포 안내
date: 2026-10-30
tags:
  - 포트폴리오
  - Vercel
  - GitHub
---

# 포트폴리오 Vercel 배포 안내

2026-10-23에 Vercel로 배포한 파일을 2026-10-30에 현재 폴더에 저장하고 GitHub에 반영했습니다.

## 웹사이트 열기

- [포트폴리오](https://lovely0503-portfolio.vercel.app)
- [크론잡 실습 정리](https://lovely0503-portfolio.vercel.app/2026-10-23-cronjob-github-telegram.html)
- [QA 공고 웹페이지](https://lovely0503-portfolio.vercel.app/qa-board.html)

## 로컬 파일

| 파일 | 내용 |
| --- | --- |
| [index.html](index.html) | 배포한 포트폴리오 본문 |
| [2026-10-23-cronjob-github-telegram.html](2026-10-23-cronjob-github-telegram.html) | 10월 23일 자동 업로드·알림 구성 실습 기록 |
| [qa-board.html](qa-board.html) | 포트폴리오에서 연결하는 QA 공고 작업물 |
| [vercel.json](vercel.json) | 공개 배포 설정 |

저장 위치는 `C:\kang\10_Projects\포트폴리오`입니다. `C:\kang`은 옵시디언 보관함이므로 VS Code와 옵시디언에서 같은 파일을 사용합니다. HTML 화면은 브라우저에서 확인할 수 있습니다.

GitHub 위치: [lovely0503/MyProject — 포트폴리오](https://github.com/lovely0503/MyProject/tree/main/10_Projects/포트폴리오)

## 현재 운영 상태

- 텔레그램 알림은 사용자 요청으로 해지했습니다. 크론잡 HTML은 당시 실습 기록입니다.
- 로컬 파일을 수정해도 Vercel 사이트에 자동으로 반영되지는 않습니다. 변경 후 별도 재배포가 필요합니다.
- 배포 인증정보와 `.env.local`, `.vercel` 폴더는 공개 파일에 포함하지 않습니다.
