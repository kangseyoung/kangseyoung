<div align="center">

# kangseyoung

### DevOps Engineer in Progress

Linux | Infrastructure Operations | Monitoring | Troubleshooting | Automation

[English README](./README.md)

</div>

---

## 소개

홍익대학교 세종캠퍼스 영상애니메이션 전공으로 입학했고, 이후 컴퓨터공학을 복수전공하고 있습니다.

처음에는 영상/파이프라인 도구를 만들면서 개발을 시작했지만, 프로젝트를 진행할수록 도구 자체보다 그 뒤에서 움직이는 서버, 공유 스토리지, 로그, Worker 상태, 장애 원인 추적에 더 관심이 생겼습니다.

장기적인 목표는 DevOps 엔지니어입니다. 지금은 그 기반을 만들기 위해 SRE에 가까운 운영 경험을 먼저 쌓고 있습니다. 로그를 확인하고, 인프라 구성 요소를 이해하고, 시스템 상태를 모니터링하고, 문제가 생겼을 때 어떻게 확인하고 대응할지 문서화하는 일에 집중하고 있습니다.

## 추천 리뷰 순서

1. [Deadline Render Farm Automation](https://github.com/kangseyoung/deadline-renderfarm-automation)  
   PySide UI, MongoDB 예약/인증, Deadline 작업 제출, NAS workflow, troubleshooting 문서를 포함한 on-premise render farm automation 프로젝트입니다.  
   주요 public source snapshot: `src/`

## 사용 / 학습 중인 기술

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

## 현재 집중하는 분야

- Linux 운영과 Shell Script
- AWS 인프라 기초: VPC, EC2, ALB, Security Group, IAM, CloudWatch
- 모니터링, 로그 확인, 작업/Worker 상태 확인, troubleshooting
- 배포 흐름과 운영 문서화
- 장기적으로는 반도체 IT / FAB 인프라 운영

## 주요 프로젝트

### [AWS Thinkbox Deadline Render Farm Infrastructure](https://github.com/kangseyoung/deadline-renderfarm-automation)

대학교 실습실 환경에서 AWS Thinkbox Deadline 기반 on-premise render farm infrastructure를 구축하고 운영했습니다.

- 약 20대의 실습실 PC, 서버 PC, NAS, DCC 렌더링 라이선스를 사용했습니다.
- 학생들이 렌더 작업을 더 쉽게 제출하고 확인할 수 있도록 PySide UI를 만들었습니다.
- 작업 상태, Worker 상태, 실패한 작업, 에러 코드, 로그, MongoDB 작업 데이터를 확인했습니다.
- Worker 연결 문제, NAS 경로 문제, 포트/방화벽 문제, 라이선스 문제를 확인하고 대응했습니다.
- 졸업작품 기간에는 약 40명의 학생이 실제로 사용했습니다.
- 현재 1년째 이어지는 프로젝트로, 장기적으로 실습실에서 운영할 수 있도록 확장 중입니다.
- 다른 실습실 환경으로도 확장하기로 결정되었습니다.
- Ansible은 테스트했지만 최종 핵심 구조에는 포함하지 않았습니다.

이 프로젝트는 AWS 클라우드에 운영 서비스를 배포한 경험이 아닙니다. AWS Thinkbox Deadline을 사용한 on-premise render farm infrastructure 운영 경험입니다.

### AWS Infrastructure Practice

현재 AWS 인프라를 직접 구성해보면서 각 구성 요소가 어떤 역할을 하는지, 문제가 생겼을 때 어디를 확인해야 하는지 공부하고 있습니다.

- VPC, public/private subnet, routing, Security Group
- EC2, ALB
- IAM 기초
- CloudWatch 모니터링과 로그 확인
- 각 구성 요소의 역할을 이해하기 위한 수동 구성 연습

### [Phoenix Pipeline Tool](https://github.com/carlton368/phoenix_pipeline_tool)

Python / PySide 기반 VFX pipeline tool 프로젝트입니다.

- login, loader, publisher, saver UI 흐름을 작업했습니다.
- Maya/Nuke 환경 설정과 Linux `.desktop` 실행 흐름을 다뤘습니다.
- ShotGrid API 연동 구조를 살펴봤습니다.
- 실행, 확인, 유지보수가 쉬운 도구 구조를 만드는 데 집중했습니다.

### Pipeline Automation Tools

Netflix Academy 부트캠프와 대학교 프로젝트에서 Python, Shell, PySide를 사용한 Linux 기반 pipeline automation 프로젝트를 진행했습니다.

- DCC workflow, 렌더 제출, 공유 경로, 작업 메타데이터를 연결했습니다.
- 팀 프로젝트 리더 역할을 맡았습니다.
- 실제 학생들이 사용할 수 있는 작업 흐름을 만드는 데 집중했습니다.

### AI / Web Side Projects

AI 기반 도구와 Web UI 실험도 진행했지만, 현재 메인 방향은 DevOps / SRE / Infrastructure입니다.

- [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent): PDF 기반 학습 노트 생성 workflow
- [Landing Agent Harness](https://github.com/kangseyoung/landing-agent-harness): landing page workflow prototype
- [Capstone Repo Polisher](https://github.com/kangseyoung/capstone-repo-polisher): 저장소 정리와 문서화 workflow

## Tech Stack

**Programming Languages**  
C++, Python, C#, Bash / Shell Script

**Operations / DevOps**  
Linux, Shell Script, Git, GitHub

**Infrastructure / Cloud**  
AWS, VPC, EC2, ALB, Security Group, IAM, CloudWatch

**Monitoring / Troubleshooting**  
Log inspection, job/worker status tracking, error checking, operational notes

**Programming / Automation**  
Python, PySide6 / PySide2, JavaScript / TypeScript

**Render Farm / Pipeline**  
AWS Thinkbox Deadline, MongoDB, NAS-based workflow, Maya, Blender, Arnold

## GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kangseyoung&show_icons=true&hide_border=true&theme=default)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kangseyoung&layout=compact&hide_border=true&theme=default)

</div>

## 방향

DevOps 엔지니어로 성장하고 싶습니다. 그 전에 Linux 서버, 인프라 구성, 모니터링, 로그 확인, troubleshooting 같은 실제 운영 경험을 익히는 것이 먼저라고 생각하고 있습니다.

장기적으로는 반도체 IT / FAB 환경에서 서버와 장비 상태 모니터링, 로그 분석, 장애 대응, 운영 자동화 쪽에도 관심이 있습니다.
