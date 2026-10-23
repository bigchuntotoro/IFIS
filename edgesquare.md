# EdgeSquare 사용자 가이드 (EdgeSquare User Guide)

## 1. 개요 (Overview)

**EdgeSquare Suite**는 엣지 컴퓨팅 기술을 활용하여 업무용 단말 및 디바이스 환경을 모니터링하고 관리하는 솔루션입니다. 중앙 관리 모니터링을 통해 장애 및 문제점을 사전에 파악하고, 단말 오류 시 선제적 자동 조치 및 대용량 프로그램 배포 기능을 제공합니다.

---

## 2. 주요 구성요소 (Architecture & Components)

EdgeSquare는 다음과 같은 핵심 모듈로 구성되어 있습니다.

| 모듈명 | 주요 기능 |
| :--- | :--- |
| **EdgeAgent** | • 사용자 단말 내 배포 수행<br>• 시스템/앱 로그 수집<br>• 파일 및 데이터 정합성 점검 |
| **EdgeManager** | • 기기 전체 등록 및 관리<br>• 원격 제어 및 명령 전달<br>• 실시간 장애 알림(Alert) 설정 |
| **EdgeMonitor** | • 대시보드 기반 단말 실시간 모니터링<br>• 정합성 점검 현황 및 장애 예측 분석 |
| **EdgeDeployer** | • 대용량 파일 및 프로그램 배포 관리<br>• 그룹별/단말별 배포 스케줄링 및 상태 관리 |

---

## 3. 핵심 기능 (Key Features)

### 3.1. 엣지 디바이스 모니터링 (Device Monitoring)
* **실시간 성능 수집**: CPU, 메모리, 네트워크, 프로세스 등 단말 자원 모니터링
* **장애 감지 및 예측**: 오류 발생 시 관리자 알림 송신 및 선제적 이상 징후 분석
* **비대면 통제**: 원격 제어 기능으로 비대면 환경에서의 단말 관리 지원

### 3.2. 정합성 관리 및 자동 복구 (Integrity Management & Auto Recovery)
* **정합성 점검**: 단말 내 OS, Application 파일 및 설정값 유효성 검증
* **선제적 오류 자동 조치**: 변조되거나 오류가 발생한 파일 자동 복구/재배포

### 3.3. 대용량 배포 시스템 (File & Software Deployment)
* **대용량 파일 배포**: 업무용 소프트웨어, 보안 패치, 서식 파일 등의 안정적 전송
* **그룹 및 스케줄 배포**: 부서/지점/기종별 그룹 배포 및 지정 시간 실행 제어

---

## 4. 모니터링 및 관리 대시보드 (Dashboard Usage)

### 4.1. 로그인 및 메인 대시보드
1. **로그인**: 관리자 계정으로 EdgeSquare Web Console 접속
2. **대시보드 확인**:
   * 전체 등록 단말 접속 현황 (온라인/오프라인)
   * 이상 징후 단말 리스트 및 에러 등급별 알림
   * 진행 중인 배포 작업 현황

### 4.2. 단말 관리 (Device Management)
* **단말 검색**: IP, Hostname, 부서명 기반 검색
* **원격 명령 실행**: 프로세스 종료, 에이전트 재시작, 정합성 재점검 요청

### 4.3. 배포 작업 관리 (Deployment Job)
* **배포 정책 생성**: 대상 파일 업로드 $\rightarrow$ 대상 그룹 선택 $\rightarrow$ 실행 조건/시간 설정
* **배포 결과 확인**: 성공/실패 단말 수 확인 및 실패 단말 재시도(Retry) 처리

---

## 5. 시스템 요구사항 (System Requirements)

* **서버 (Server Side)**: Java 기반 웹 애플리케이션 서버 (WAS), RDBMS 지원
* **에이전트 (Agent Side)**: Windows XP/7/10/11, macOS, Linux 등 다양한 OS 지원
* **웹 브라우저**: Chrome, Edge, Safari, Firefox 등 최신 멀티 브라우저 지원

---

## 6. 문의 및 지원 (Support)

* **제조사**: (주)인스웨이브시스템즈 (Inswave Systems)
* **공식 웹사이트**: [https://www.inswave.com](https.www.inswave.com)
