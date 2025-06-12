# 불쑥 (Bulssuk) - Frontend 🌱

불쑥은 사용자의 분리수거 실천을 돕기 위한 AI 기반 환경 보호 앱입니다.  
Flutter 기반으로 제작되었으며, 쓰레기 분류 인식, 배출 일정 확인, 나무 키우기 등의 기능을 제공합니다.

---

## 🧭 주요 기능

- 📷 **AI 분리수거 인식** (카메라 기반 쓰레기 종류 분류)
- 🗓️ **캘린더 기반 배출일 알람 설정**
- 🌳 **Gamification: 나무 키우기**
- 🧾 **JWT 로그인 / 회원가입 / 마이페이지 관리**
- 📊 **활동 시각화 대시보드**

---

## 📂 폴더 구조

```
lib/
├── auth/        # 로그인, 회원가입, 비밀번호 찾기 등 인증 관련
├── calendar/    # 분리수거 배출일 캘린더 기능
├── dashboard/   # 활동 요약 대시보드
├── home/        # 홈 화면
├── info/        # 분리배출 가이드, 환경 정보
├── mypage/      # 마이페이지 (회원정보 수정, 비밀번호 변경)
├── mytree/      # 나무 키우기 gamification 기능
├── widgets/     # 공통 UI 위젯 컴포넌트
└── main.dart    # 앱 진입점 및 라우팅
```

---

## 📦 주요 패키지

| 패키지 | 용도 |
|--------|------|
| `flutter_secure_storage` | JWT 저장 및 인증 처리 |
| `http` | REST API 통신 |
| `shared_preferences` | 사용자 설정, 캐시 저장 |
| `flutter_dotenv` | API URL 등 환경변수 관리 |
| `table_calendar` | 배출일 달력 기능 |
| `jwt_decoder` | JWT 토큰 파싱 |
| `intl`, `url_launcher` | 날짜 포맷 처리, 외부 링크 이동 |

---

## ⚙️ 실행 환경

`.env` 파일 생성:
```env
URL=https://your-api-url.com
```

---

## 👥 기여자 및 역할 분담

| 이름     | 담당 영역                          |
|----------|-------------------------------------|
| **정현지** | 인프라 구축, 전체 프로젝트 총괄, DB 설계 |
| **안동규** | Flutter 프론트엔드 개발, Node.js 백엔드, DB |
| **이혜연** | Node.js 백엔드 개발, DB |
| **최민경** | Flutter 프론트엔드 개발, Node.js 백엔드, DB |
| **심건우** | Python 기반 AI (LLM), MLflow 모델 관리 |

---

## 📄 개발 정보

- **플랫폼:** Flutter (Android, iOS, Web, Windows 등 멀티플랫폼 지원)
- **백엔드 연동:** [recycle_back_dk](https://github.com/ahndongkyu/recycle_back_dk)

---

## 📄 라이선스

MIT License
