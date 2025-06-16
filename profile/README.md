# 💸 BeRich – 쓰는 재미, 모으는 습관, 부자가 되

**BeRich**는 사용자의 소비 기록을 통해 캐릭터가 성장하고, 자연스럽게 금융 습관을 만들어주는 감성 재테크 플랫폼입니다.  



## ✨ 주요 기능

- 📊 가계부 기록 (수입/지출)
- 🌱 캐릭터 성장 시스템
- 🎯 금융 미션 도전
- 🪙 포인트 보상 및 리워드
- 📈 소비 통계 및 대시보드



## 🧱 프로젝트 구조

```
BeRich/  
├── backend/ # Spring Boot API 서버  
├── frontend/ # React 기반 사용자 클라이언트  
├── .github/README.md # Organization 설정  
└──   
```

## ⚙️ 기술 스택

| 항목         | 내용                              |
|--------------|-----------------------------------|
| **Backend**  | Java 17, Spring Boot 3.x, JWT, JPA |
| **Frontend** | React Native, TypeScript, Vite, Tailwind |
| **DB**       | MySQL 8                    |
| **Infra**    | AWS (EC2, RDS), Docker            |
| **CI/CD**    | GitHub Actions                    |
| **문서화**   | Swagger (OpenAPI 3.0)             |


## 🚀 실행 방법

### 백엔드

```bash
cd backend
./gradlew bootRun
```

### 프론트엔드
```bash
cd frontend
npm install
npm run dev
```

### 🧪 Swagger API 문서
http://localhost:8080/swagger-ui/index.html

### 🔀 Git 브랜치 전략
| 브랜치         | 설명                              |
|--------------|-----------------------------------|
| main | 프로덕션 배포용 |
| dev	| 개발 통합 브랜치 |
| feat/* | 기능 개발 브랜치 |
| fix/*	| 버그 수정 브랜치 |
| chore/*	| 설정/문서 수정 등 |

> Pull Request는 dev 브랜치 기준으로 하고, 리뷰어 최소 1인 지정 필수입니다.

### 👨‍👩‍👧‍👦 팀 구성
| 이름 | 역할 |
|-----|-----|
| 김지성 | PM / 프론트엔드 개발 |
| 신진욱 | 프론트엔드 개발 |
| 류 건 | 백엔드 개발 / 인프라 |
| 한준교 | 백엔드 개발 |


### 📝 License
MIT License
