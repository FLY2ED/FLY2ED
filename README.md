# 박성재 · Frontend Engineer

React와 TypeScript로 제품의 핵심 화면과 실시간 흐름을 만듭니다.  
채팅 SDK, 운영 어드민, 대량 발송/CRM, 모바일 앱처럼 사용자가 매일 반복해서 쓰는 기능을 설계하고 구현해 왔습니다.

공개 저장소와 운영 중인 제품, 비공개 클라이언트 작업 중 검증 가능한 신호만 골라 정리했습니다.

- Portfolio: https://portfolio.naldadev.com
- GitHub: https://github.com/FLY2ED
- Email: seongjae@naldadev.com

## 제가 잘 만드는 것

- 실시간 상태가 중요한 UI: WebSocket/Socket.io, 재연결, presence, 읽음 상태, optimistic UX
- 운영자가 매일 쓰는 도구: 권한, 정책 제어, 로그, 엑셀/CSV 내보내기, 개인정보 마스킹
- 제품형 프론트엔드: React/TypeScript 구조화, 상태 관리, 테스트, 배포, 장애 원인 추적
- AI-assisted workflow: Codex, Claude Code, Gemini를 코드 리뷰, 리팩터링, 테스트 보강에 연결

## 대표 작업

| 프로젝트 | 링크 | 핵심 |
| --- | --- | --- |
| carrot-chat | [Live](https://carrot.naldadev.com) · [Code](https://github.com/FLY2ED/carrot-chat) | React, TypeScript, Zustand, Cloudflare Durable Objects 기반 웹채팅 SDK 데모. WebSocket 자동 재연결, 하트비트, typed event, Playwright/Vitest, 서버측 연락처 마스킹. |
| artdata | [Service](https://artdata-edu.com) | Socket.io 기반 1:1 채팅, 읽음/타이핑/파일, 어드민 모니터링, 서버측 정책 마스킹, AI 리포트 운영. |
| NALDA Timer | [Live](https://timer.naldadev.com) · [Code](https://github.com/FLY2ED/face-timer) | 얼굴 인식 기반 시간 측정 서비스. React, TypeScript, WebGL human detection, 카메라 권한 처리, 생산성 UX. |
| KORI VOCA | [App Store](https://apps.apple.com/kr/app/kori-voca-learn-korean/id6751938864) | React Native 한국어 학습 앱. 간격 반복 학습, 접근성, App Store 출시, ST창업오디션 최우수상. |
| Desktop Dday | Portfolio | Electron/Vue와 React Native로 만든 D-Day 위젯. 데스크톱/모바일 4개 스토어 출시, 운영 후 매각. |
| Client systems | [Portfolio](https://portfolio.naldadev.com) | 대량 SMS/LMS 발송 플랫폼, 프랜차이즈 랜딩+어드민, 부동산 CRM 등 반복 운영 도구와 권한/정책 흐름. |

## 공개 저장소

- [carrot-chat](https://github.com/FLY2ED/carrot-chat): 실시간 웹채팅 SDK 데모
- [face-timer](https://github.com/FLY2ED/face-timer): 얼굴 인식 기반 시간 측정 서비스
- [wp-face-timer](https://github.com/FLY2ED/wp-face-timer): NALDA Timer 백엔드/API 설계 문서
- [nalda_camera_calibration](https://github.com/FLY2ED/nalda_camera_calibration): OpenCV 카메라 캘리브레이션 도구

## 기술 스택

React · TypeScript · Zustand · Vue · React Native · Node.js · Socket.io · Cloudflare Workers · Durable Objects · PostgreSQL · Prisma · Vitest · Playwright
