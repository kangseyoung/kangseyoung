# kangseyoung

VFX 파이프라인과 Python 자동화를 중심으로 프로젝트를 정리하고 있습니다.  
반복되는 파일 처리, 렌더 제출, 데이터 연결, 문서화 흐름을 줄이는 데 관심이 있습니다. 최근에는 기존 자동화 작업에 LLM API를 보조 도구로 연결하는 방식을 실험하고 있습니다.

## 관심 분야

- VFX pipeline automation
- Python scripting / CLI tools
- API 연동과 데이터 처리
- PySide 기반 데스크톱 툴
- Deadline, Maya, Blender 작업 흐름
- LLM API를 활용한 문서화와 반복 작업 보조

## Tech Stack

- **Language:** Python, Shell script, JavaScript 기초
- **VFX / DCC:** Maya, Arnold, Blender, Nuke 기초, AWS Thinkbox Deadline
- **UI / App:** PySide6 / PySide2, Qt Designer, Next.js, React, TypeScript
- **Data / API:** MongoDB, ShotGrid API, Google Sheets API, Supabase 클라이언트 패턴, OpenAI API
- **Environment:** Linux, Windows, Git / GitHub, NAS shared path

## 주요 프로젝트

### [Lecture Companion Agent](https://github.com/kangseyoung/Lecture-Companion-Agent)

영어 강의 PDF를 페이지별 한국어 학습 노트와 주석 PDF로 변환하는 로컬 CLI 도구입니다.  
PDF 텍스트 추출, 페이지 이미지 생성, Markdown 중간 산출물, 최종 PDF 렌더링 흐름을 다룹니다.  
OpenAI API는 학습 노트 생성을 돕는 선택 기능이며, API 키 없이도 렌더링 흐름을 테스트할 수 있습니다.

**주요 작업**

- Python CLI로 PDF 입력, 페이지 처리, 출력 폴더 구조 구성
- Markdown 노트 기반 PDF 렌더링 흐름 정리
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

캡스톤 렌더팜 프로젝트를 공개 포트폴리오용 저장소로 정리하기 위한 리팩토링/문서화 작업 공간입니다.  
기존 코드, 비공개 참고자료, 보안 위험 요소를 점검하고 공개 가능한 문서 구조를 설계했습니다.  
실제 삭제나 민감정보 정리는 별도 승인 후 진행해야 하는 항목으로 구분했습니다.

**주요 작업**

- 저장소 구조, entry point, 중복 패키지, 생성 파일 상태 감사
- 민감정보와 공개 문서 redaction 기준 정리
- README, architecture, troubleshooting 등 공개 문서 방향 제안

### [Deadline Renderfarm Automation](https://github.com/kangseyoung/deadline-renderfarm-automation)

공유 실습실 환경을 위한 Deadline 기반 렌더팜 자동화 프로젝트입니다.  
PySide 제출 UI, MongoDB 사용자/예약 데이터, Google Sheets 예약 흐름, NAS 공유 경로, Maya/Arnold와 Blender 제출 흐름을 다룹니다.  
공개 저장소에는 제출 측 코드와 문서 중심의 안전한 스냅샷을 정리했습니다.

**주요 작업**

- Deadline job/plugin info 생성과 MayaBatch/Blender 제출 흐름 정리
- MongoDB 기반 로그인/예약 조회와 Google Sheets 데이터 연동 흐름 구성
- 경로, 라이선스, OCIO, Worker 상태 등 운영 이슈 문서화

## 현재 공부 중

- Maya/Python 툴 구조 개선
- API 응답 데이터 처리와 저장 구조
- Deadline 제출 자동화와 운영 문서화
- LLM API를 활용한 로그 분석, 문서화, 반복 작업 보조

## 정리 방향

큰 표현보다 실제로 다뤄본 문제를 기준으로 기록합니다. 자동화, 시스템 연결, 데이터 처리, 문서화를 중심으로 작업 흐름을 조금씩 개선해 나가고 있습니다.
