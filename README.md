# Looply
Looply는 반복적인 **루틴을 기록하고 추적**할 수 있는 웹 기반 습관 트래커입니다.  
매일 해야 하는 일들을 정리하고, 체크하면서 **연속 달성**과 간단한 **통계 대시보드**를 통해 꾸준함을 유지하는 데 도움을 줍니다.

<br></br>


## ✨ Features (MVP)

- **루틴 관리**
  - 루틴 생성, 수정, 삭제
  - 이름, 설명, 주기(매일 / 특정 요일) 설정

- **오늘의 루틴**
  - 오늘 해야 할 루틴 리스트 보기
  - 완료 체크/해제

- **기록 & 통계**
  - 습관별 완료 히스토리 저장
  - 최근 N일 기준 간단한 통계
  - 연속 달성(streak) 표시

<br></br>

> ✅ 아직 개발 초기 단계입니다. 기능과 UI는 계속해서 변경될 수 있습니다.


<br></br>


## 🛠 Tech Stack

**Frontend**
- [Next.js](https://nextjs.org/) (App Router) 16.0.7
- React 19.2.0
- TypeScript ^5

**Backend / API**
- Next.js API Routes (`/app/api/**`)

**Database**
- [Prisma](https://www.prisma.io/)
- PostgreSQL

**Etc**
- 패키지 매니저: `npm`
- 스타일링: `Tailwind CSS` ^4
