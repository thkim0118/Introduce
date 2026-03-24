# 김태형 | Android / FE Engineer

## Summary
플랫폼의 경계를 넘어 문제를 해결하는 7년 차 엔지니어입니다.
- **하드웨어 통신 제어:** Bluetooth/USB Serial 기반 안드로이드 개발 (전기전자제어공학 전공)
- **Android/C++:** 글로벌 1,000만 다운로드 서비스의 실시간 비디오 파이프라인 구축
- **앱 안정성:** 50만 다운로드 상용 앱 크래시프리 99.9% 달성
- **자동화:** CI/CD 파이프라인 구축, AI Agent 기반 워크플로우 자동화
- **웹 프론트엔드:** TypeScript/Next.js 기반 서비스 개발 및 운영

하드웨어부터 앱, 웹까지 기술 스택에 구애받지 않고 제품의 문제를 끝까지 해결합니다.

---

## 기술 스택
- **Language:** Kotlin, TypeScript, Dart (Flutter), C++
- **Android:** Jetpack Compose, Coroutines, Android App Architecture (MVVM, MVI)
- **Web:** Next.js, React
- **Infra:** Git, Jenkins, Firebase App Distribution, CI/CD
- **통신:** WebRTC, Bluetooth, USB Serial

---

## 경력

### (주)엘지유플러스
**Frontend 개발자** | 2024.06 - 현재 재직 중

- **글로벌 아이돌 팬 플랫폼 '디거스' 개발 및 서비스 종료**
  - ReactNative + WebView 기반의 글로벌 팬 플랫폼(10만-30만 다운로드) 서비스의 TypeScript/Next.js 웹 영역 신규 개발 및 유지보수.
  - 기존 네이티브-웹 브릿지 위에 Push 알림 및 추가 메시지 통신 환경을 확장 개발하고, 서비스 종료(sunset)까지의 전 과정을 주도.
- **U+One 신규 요금제 가입/개통 페이지 개발**
  - 웹과 앱 환경 모두에서 일관되게 동작하는 반응형 요금제 가입/개통 페이지 신규 개발.
  - 웹 유입 유저를 앱으로 전환시키는 인입 플로우 구현.
- **개발 프로세스 자동화**
  - AI Agent 기반 Jira 티켓 자동 처리 시스템 구축: 요구사항 티켓 → Agent Skill 문서 → 티켓 처리 플로우 자동화. 팀(10명) 전원이 사용하며 티켓당 처리 시간 15분 → 5분으로 66% 단축.
  - PR 병합 시 릴리즈 내용을 자동 요약하는 배포 문서 생성 시스템 개발. 모든 릴리즈 배포에 적용되어 배포 히스토리 추적성 확보.
- **코드 리뷰 문화 정착**
  - 개발 시간과 리뷰 시간을 1:1로 할당하여 팀 내 코드 리뷰를 적극 수행. PR 기반 리뷰를 통해 코드 품질 개선 및 팀 내 기술 공유에 기여.

### 주식회사 의식주컴퍼니 (런드리고)
**안드로이드 개발자** | 2021.10 - 2024.06 (2년 9개월)
- [런드리고](https://play.google.com/store/apps/details?id=com.laundrygo.android) - 비대면 세탁 서비스 (50만 다운로드)

- **앱 품질 및 아키텍처 개선**
  - **안정성 확보:** 세탁물 신청 과정에서의 크래시가 이탈 및 매출 감소로 직결되는 문제를 해결하기 위해 Android App Architecture 및 방어적 프로그래밍을 적용, 앱 강제 종료 비율 99.9% 무결성 달성.
  - **테스트 환경 구축:** 다수의 Deeplink가 단일 파일에서 관리되어 테스트와 유지보수가 어려운 구조를 개선. 각 UseCase 단위로 분리 리팩토링하고 Unit Test 환경을 구축하여 Domain layout 테스트 커버리지 0% → 16% 달성.
  - **사진첩 성능 개선:** 커스텀 사진 선택 UI에서 1만 장 이상의 이미지 로딩 시 발생하는 성능 문제를 Kotlin Coroutines 기반 비동기 처리로 개선.
- **CI/CD 기반 자동 배포 파이프라인 구축**
  - 수동 배포 시 발생하는 휴먼 에러와 리소스 낭비를 해소하기 위해 Jenkins Build Trigger + Bitbucket Web Hook + Firebase App Distribution + Slack 알림을 연동한 자동 배포 환경 구축.
- **신규 운송기사 앱 런칭**
  - 기존 웹 기반 운송기사 서비스를 모바일 네이티브 기능(GPS, 푸시 등) 활용을 위해 앱으로 전환. Flutter를 채택하여 iOS/Android 동시 제공하며, 프로젝트 초기 세팅부터 로그인(Token) 처리, 최종 배포까지 전 과정 주도.

### (주)볼트마이크로
**안드로이드 개발자** | 2020.07 - 2021.10 (1년 4개월)
- [카메라파이 라이브](https://play.google.com/store/apps/details?id=com.vaultmicro.camerafi.live) - 비디오 스트리밍 서비스 (글로벌 1,000만 다운로드)

- **실시간 인물 인식 필터 신규 개발**
  - 기존 비디오 필터에 실시간 인물 세그멘테이션 기능을 추가하기 위해, Google MediaPipe의 Graph 기반 파이프라인에서 Selfie Segmentation 모델 출력과 렌더링 사이에 커스텀 Calculator를 삽입하는 방식으로 C++ 코드를 직접 수정.
  - 인물을 제외한 배경 색상을 실시간으로 변경하는 기능을 구현하고 30fps 처리 POC 달성.
- **라이브 방송 멀티뷰 개발**
  - 단일 카메라만 송출 가능했던 라이브 방송에 다양한 각도의 화면 제공이 필요하여, WebRTC SDK를 활용해 외부 디바이스의 영상을 송출 카메라에 렌더링하는 멀티뷰 기능을 구현. 최대 5대 동시 연결, 30분 이상 안정적 유지 검증.

### (주)네톰
**안드로이드 개발자** | 2020.01 - 2020.06 (6개월)
- [Swing-U](https://play.google.com/store/apps/details?id=com.nethom.itemmanager) - B2B 물류/출입 관리 서비스

- **물류/출입 관리용 RFID 통신 모듈 개발**
  - RFID 리더기를 활용한 물류량 측정 및 출입 관리 POC 개발. 블루투스 및 USB Serial 통신을 이용한 실물 디바이스 RFID 데이터 수신 모듈 구현.
  - 물리적 노이즈로 인한 데이터 유실 문제를 필터링 로직으로 해결하여 RFID 데이터 수신 무결성 확보.

---

## 학력
- **한경대학교** 전기전자제어공학과 학사 (2013 - 2020)

---

## Current Focus
- Claude Code, Gemini 등 AI Agent를 활용한 바이브 코딩으로 프로덕트를 직접 설계·배포
  - 웹 서비스 배포 완료: https://julsae.com/
  - Android 앱 스토어 심사 중 (배포 예정)

---

## 주요 활동
- 개인 프로젝트: 촬영현장 구인구직 플랫폼 앱 (ComposeUI + Kotlin, Android App Architecture)
  - [GitHub](https://github.com/thkim0118/Film-job-searching) | [플레이스토어](https://play.google.com/store/apps/details?id=com.fone.filmone&hl=ko&gl=US)
- [알고리즘 스터디](https://github.com/thkim0118/Algorithm-Study)
- [안드로이드 기본기 스터디](https://github.com/thkim0118/AndroidStandardLevel)
- [안드로이드 스터디 모임](https://github.com/kangraemin/Android-Seminar-Study)
