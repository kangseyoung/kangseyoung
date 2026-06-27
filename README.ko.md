# kangseyoung

## SRE 기반을 쌓아가는 DevOps 엔지니어 지망생

Linux 운영, 모니터링, 트러블슈팅, 자동화를 바탕으로 안정적인 시스템을 이해하고 만들고 싶습니다.

저는 홍익대학교 세종캠퍼스 영상애니메이션 전공으로 입학했고, 이후 컴퓨터공학을 복수전공하고 있습니다. 영상/파이프라인 환경에서 렌더 작업, 공유 스토리지, 사용자용 도구, Linux 기반 자동화, 실제 학생들이 사용하는 인프라 문제를 다루면서 운영과 인프라에 관심을 갖게 되었습니다.

최종 목표는 DevOps 엔지니어입니다. 다만 단순히 배포 도구만 다루기보다, 먼저 SRE 관점의 운영 경험을 쌓고 싶습니다. 서버와 네트워크가 어떻게 연결되는지, 로그와 상태값으로 장애 원인을 어떻게 추적하는지, 모니터링과 런북을 어떻게 구성하는지에 관심이 있습니다.

## 현재 집중하는 방향

- DevOps 기본기: Linux, 네트워크, 배포 흐름, 자동화, 운영 안정성
- SRE 기반: 모니터링, 로그 확인, 장애 원인 분석, 런북 작성
- Observability: CloudWatch, 작업/Worker 상태, 대기/진행/실패 상태, 에러 코드, 운영 로그
- Linux 운영: Shell Script, 프로세스/로그 확인, 서비스 설정, 트러블슈팅
- AWS 인프라 기초: VPC, EC2, ALB, Security Group, IAM, CloudWatch
- DevOps 도구: Docker, Nginx, Git/GitHub workflow, 배포 구조
- 장기 관심사: 반도체 IT / FAB 환경의 서버·장비 상태 모니터링, 로그 분석, 장애 대응, 운영 자동화

## 주요 경험 / 프로젝트

### [AWS Thinkbox Deadline Render Farm Infrastructure](https://github.com/kangseyoung/deadline-renderfarm-automation)

학교 실습실 환경에서 AWS Thinkbox Deadline 기반 on-premise 렌더팜 인프라를 구축하고 운영했습니다.

- 약 20대의 실습실 PC, 서버 PC, NAS 공유 스토리지, DCC 렌더링 라이선스를 활용해 렌더 작업 제출/관리 흐름을 만들었습니다.
- 학생들이 렌더 작업을 쉽게 제출하고 확인할 수 있도록 PySide 기반 UI를 만들었습니다.
- 작업 상태, Worker 상태, 대기/진행/실패 상태, 에러 코드, 로그, MongoDB에 연결된 작업 데이터를 확인했습니다.
- Worker 연결 문제, NAS 공유 경로 문제, 포트/방화벽 문제, 라이선스 문제 등을 로그와 상태값을 보며 대응했습니다.
- 학기 말 졸업작품 기간에 약 40명의 학생들이 실제로 사용했습니다.
- Ansible은 여러 PC 설정 관리를 위해, Docker는 CPU 코어 단위 컨테이너 분리와 Ubuntu 환경 운영 가능성을 보기 위해 테스트했습니다. 최종 핵심 구조에는 포함하지 않았고, 시행착오와 확장 가능성으로 남겼습니다.

> 이 프로젝트는 AWS 클라우드에 운영 서비스를 배포한 경험이 아닙니다. AWS Thinkbox Deadline을 사용한 on-premise render farm infrastructure 운영 경험입니다.

### AWS Infrastructure / DevOps-SRE Practice

AWS 인프라 구성 요소가 어떻게 연결되고, 모니터링되고, 보안 설정되며, 장애 상황에서 어떻게 확인되는지 학습하고 있습니다.

- VPC, public/private subnet, routing, Security Group
- EC2, Docker, Nginx, ALB
- IAM 권한과 기본 보안 경계
- CloudWatch 기반 모니터링과 로그 확인
- 각 구성 요소의 역할을 이해하기 위한 수동 인프라 구성 연습

### [Phoenix Pipeline Tool](https://github.com/carlton368/phoenix_pipeline_tool)

Python / PySide 기반 VFX 파이프라인 도구 프로젝트입니다. 아티스트용 UI, DCC 환경, 프로덕션 데이터 흐름을 연결하는 데 초점을 두었습니다.

- login, loader, publisher, saver 흐름을 위한 PySide UI 모듈을 구성했습니다.
- Maya/Nuke 환경 설정, Linux `.desktop` 실행 흐름, 경로/설정 처리를 다뤘습니다.
- 프로젝트 및 프로덕션 데이터 접근을 위한 ShotGrid API 연동 구조를 탐색했습니다.
- 반복 가능한 실행 환경, 사용자 작업 흐름, 에러/로그 확인, 유지보수 가능한 도구 구조를 중요하게 봤습니다.

### Pipeline Automation Tools with Python / PySide

Netflix Academy 부트캠프와 학교 프로젝트에서 Python, Shell, PySide를 활용해 Linux 기반 파이프라인 자동화 프로젝트를 진행했습니다.

- DCC workflow, 렌더 제출, 예약/로그인 데이터, 공유 경로, 작업 메타데이터를 연결하는 도구를 만들었습니다.
- 팀 프로젝트 리더 역할을 맡았고, 실제 프로덕션 스타일 환경에서 사용할 수 있는 도구 흐름에 집중했습니다.
- UI, 파일 시스템 경로, 데이터베이스 기록, 렌더 작업 상태를 하나의 작업 흐름으로 연결했습니다.

### AI / Web Automation Side Projects

AI 기반 도구와 Web UI 실험도 진행했지만, 현재 메인 방향은 DevOps / SRE / Infrastructure입니다.

- [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent): PDF 기반 학습 노트 생성 workflow
- [Landing Agent Harness](https://github.com/kangseyoung/landing-agent-harness): agent 기반 landing page workflow prototype
- [Capstone Repo Polisher](https://github.com/kangseyoung/capstone-repo-polisher): 저장소 정리와 공개 문서화 workflow

## Tech Stack

**DevOps / Operations**  
Linux, Shell Script, Docker, Nginx, Git, GitHub, deployment flow, operational automation

**Infrastructure / Cloud**  
AWS, VPC, EC2, ALB, Security Group, IAM

**SRE / Observability Foundation**  
Monitoring, log inspection, troubleshooting, runbook thinking, CloudWatch, job/worker status tracking

**Programming / Automation**  
Python, PySide6 / PySide2, JavaScript / TypeScript

**Render Farm / Pipeline**  
AWS Thinkbox Deadline, MongoDB, NAS-based workflow, Maya, Blender, Arnold, DCC render licenses

## Career Direction

서버와 네트워크 구성부터 모니터링, 로그 확인, 장애 원인 분석, 자동화까지 운영 흐름 전체를 이해하는 엔지니어가 되고 싶습니다.

단기적으로는 SRE 관점의 운영 경험을 쌓는 데 집중하고 있습니다. Observability, Linux 운영, AWS 인프라 기초, 장애 트러블슈팅, 런북 기반 자동화가 현재 학습 방향입니다. 장기적으로는 인프라, 배포, 모니터링, 자동화를 안정적인 운영 흐름으로 연결하는 DevOps 엔지니어로 성장하고 싶습니다.

또한 반도체 IT / FAB 환경의 서버·장비 상태 모니터링, 로그 분석, 장애 대응, 운영 자동화에도 관심이 있습니다.
