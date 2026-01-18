# 👻 온라인 페르소나 테스트

> 현실의 나와 온라인의 나, 얼마나 다를까?

오프라인 MBTI는 알겠는데, 온라인에서의 나는 어떤 유형일까요?  
12개 질문으로 알아보는 나의 **디지털 페르소나** 테스트입니다.

![Online Persona Test](https://img.shields.io/badge/version-1.0.0-purple)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ 기능

- 🎯 **16가지 온라인 페르소나 유형** - MBTI처럼 4글자 코드 (L/G, R/A, F/P, D/S)
- 📊 **MBTI 갭 분석** - 오프라인 vs 온라인 성격 차이 측정
- 💚💔 **궁합 & 상극** - 나와 찰떡/상극인 유형 확인
- 🔥 **팩트 폭격** - 각 유형별 직설 코멘트
- 📈 **유형 통계** - 전체 중 몇 %가 이 유형인지

## 🎮 유형 미리보기

| 코드 | 유형명 | 설명 |
|------|--------|------|
| LRFS | 스토리 폭격기 📸 | 오늘 뭐 먹었는지 다 알려줌. 24시간이 모자란 인스타그래머 |
| GAPS | 디지털 유령 👻 | 접속은 하는데 아무 흔적 없음. 존재 자체가 미스터리 |
| LAFD | 키보드 워리어 ⚔️ | 부캐로 논쟁 참전. 댓글창 검투사 |
| GRPD | 아카이브 수집가 🗂️ | 저장만 500개. 언젠간 볼 거야 (안 봄) |
| ... | ... | 총 16가지 유형 |

## 🚀 배포 방법

### 방법 1: Netlify Drop (가장 쉬움)
1. [Netlify Drop](https://app.netlify.com/drop) 접속
2. `index.html` 파일을 드래그 앤 드롭
3. 생성된 URL 공유!

### 방법 2: GitHub Pages
1. 이 저장소를 Fork
2. Settings → Pages → Source: main branch
3. `https://[sunworl].github.io/[my-online-persona-test]` 에서 확인

### 방법 3: Vercel
```bash
npm i -g vercel
vercel
```

## 🛠 기술 스택

- React 18
- Vanilla CSS (styled-components 스타일)
- 별도 빌드 과정 없음 (CDN 방식)

## 📁 파일 구조

```
├── index.html          # 메인 앱 (단일 파일)
├── README.md           # 이 파일
└── LICENSE             # MIT 라이선스
```

## 🎨 4가지 분류 축

| 축 | 설명 | 유형 |
|----|------|------|
| **존재감** | 온라인 활동량 | L (Loud) / G (Ghost) |
| **정체성** | 실명 vs 익명 | R (Real) / A (Alter) |
| **갈등대응** | 논쟁 참여도 | F (Fighter) / P (Peace) |
| **콘텐츠** | 소비 깊이 | D (Deep) / S (Scroll) |

## 📝 라이선스

MIT License - 자유롭게 사용, 수정, 배포 가능합니다.

## 🤝 기여하기

이슈와 PR 환영합니다!

- 새로운 유형 코멘트 제안
- UI/UX 개선
- 버그 리포트

---

Made with 💜 by sunworl & Claude
