# kangseyoung

Python 기반 자동화와 API 연동, 데이터 처리 흐름을 중심으로 프로젝트를 정리하고 있습니다.  
이전에는 렌더팜과 작업 도구 자동화처럼 여러 시스템을 연결하는 문제를 다뤘고, 최근에는 LLM API와 Web UI를 활용한 작은 서비스 흐름을 실험하고 있습니다.

## 관심 분야

- Python scripting / CLI tools
- API 연동과 JSON, PDF 데이터 처리
- LLM API를 활용한 간단한 기능 구현
- 프롬프트 기반 문서화와 반복 작업 보조
- 사용자 요청을 기능 흐름으로 연결하는 구조
- Next.js / React 기반 Web UI

## Tech Stack

- **Language:** Python, JavaScript / TypeScript, Shell script
- **App / UI:** Next.js, React, PySide6 / PySide2, Qt Designer
- **Data / API:** OpenAI API, MongoDB, Google Sheets API, Supabase 클라이언트 패턴, ShotGrid API
- **Automation:** CLI tools, PDF processing, Markdown workflow, Git / GitHub
- **Previous project context:** Deadline, Maya, Blender, Arnold, NAS shared path

## 주요 프로젝트

### [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent)

영어 강의 PDF를 페이지별 한국어 학습 노트와 주석 PDF로 변환하는 로컬 CLI 도구입니다.  
PDF 텍스트 추출, 페이지 이미지 생성, Markdown 중간 산출물, 최종 PDF 렌더링 흐름을 다룹니다.  
OpenAI API는 학습 노트 생성을 돕는 선택 기능이며, API 키 없이도 렌더링 흐름을 테스트할 수 있습니다.

**주요 작업**

- Python CLI로 PDF 입력, 페이지 처리, 출력 폴더 구조 구성
- OpenAI API 호출을 통한 페이지별 학습 노트 생성 흐름 구현
- 참고자료 매칭은 키워드 기반으로 구현, 벡터 DB RAG는 미구현으로 명시

### [Landing Agent Harness](https://github.com/kangseyoung/landing-agent-harness)

랜딩페이지 제작 과정을 기획, 카피, UI, 구현, QA, 개선 단계로 나눈 워크플로우 하네스입니다.  
역할별 agent prompt와 산출물 문서를 정리하고, Next.js 데모 앱을 함께 포함했습니다.  
관리자 인증, 권한 분리, 운영 보안 검토는 아직 완료 기능이 아니라 Future Work로 구분했습니다.

**주요 작업**

- 단계별 agent prompt, project brief, QA/report 문서 구조화
- Next.js / TypeScript 기반 랜딩페이지와 관리자 화면 데모 구성
- Supabase 스키마와 설정 문서를 리드 수집 흐름 관점에서 정리

### [Capstone Repo Polisher](https://github.com/kangseyoung/capstone-repo-polisher)

캡스톤 프로젝트 저장소를 공개 포트폴리오용으로 정리하기 위한 문서화 작업 공간입니다.  
기존 코드, 비공개 참고자료, 보안 위험 요소를 점검하고 공개 가능한 문서 구조를 설계했습니다.  
실제 삭제나 민감정보 정리는 별도 승인 후 진행해야 하는 항목으로 구분했습니다.

**주요 작업**

- 저장소 구조, entry point, 중복 패키지, 생성 파일 상태 감사
- 민감정보와 공개 문서 redaction 기준 정리
- README, architecture, troubleshooting 등 공개 문서 방향 제안

### [Deadline Renderfarm Automation](https://github.com/kangseyoung/deadline-renderfarm-automation)

공유 실습실 렌더 작업을 자동화하기 위한 Deadline 기반 시스템 프로젝트입니다.  
PySide 제출 UI, MongoDB 사용자/예약 데이터, Google Sheets 예약 흐름, NAS 공유 경로, Maya/Blender 제출 흐름을 연결했습니다.  
현재 관심사는 VFX 자체보다 여러 도구와 데이터를 연결해 실제 작업 흐름을 자동화한 경험에 가깝습니다.

**주요 작업**

- Deadline job/plugin info 생성과 MayaBatch/Blender 제출 흐름 정리
- MongoDB 기반 로그인/예약 조회와 Google Sheets 데이터 연동 흐름 구성
- 경로, 라이선스, Worker 상태 등 운영 이슈 문서화

## 현재 공부 중

- LLM API를 활용한 기능 구현과 응답 개선
- 사용자 요청을 적절한 기능으로 분기하는 구조
- JSON / CSV 데이터 정제와 가공
- 모델 응답 비교와 평가 방법
- 모델 학습과 fine-tuning 기본 개념
- Web UI와 AI 기능 연결

## 정리 방향

자동화와 시스템 연결 프로젝트를 하면서 API, 데이터 처리, 문서화 흐름에 관심을 가져왔습니다. 지금은 이 경험을 바탕으로 LLM 기반 기능을 작게 구현해 보고, Web UI와 연결하는 방식을 공부하고 있습니다.
