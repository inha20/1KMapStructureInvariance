# REPOSITORY_CLEANUP_PLAN

## 목적

이 문서는 이미 완료된 리팩토링 작업과 아직 남아 있는 저장소 정리 작업을 구분하기 위해 작성되었다.

주의:

- RepositoryRefactoringReport.md에 기록된 주요 구조 개편은 대부분 완료되었다.
- 동일한 작업을 반복 수행하지 말 것.
- 앞으로는 구조 개편보다 최종 정리 및 통폐합에 집중할 것.

---

## 이미 완료된 작업 (재실행 금지)

- paper/ 폴더 생성
- research/ 폴더 생성
- docs/ 폴더 생성
- archive/ 폴더 생성
- PlusOnMinorThrsis.md → research/KMapEquivalenceTheory.md 이동
- HANDOVER_antigravity 계열 문서 통합
- HANDOVER_MASTER.md 생성
- GitHub Pages용 index.html 구축
- README 구조 정비
- 논문 최신본 분리 관리

위 작업들은 이미 수행되었으므로 다시 반복하지 말 것.

---

## 최우선 정리 작업

### 1. images 폴더 정리

확인 대상:

- desktop.ini
- 프레젠테이션1.pptx

원칙:

- images/ 에는 이미지 파일만 존재해야 한다.
- pptx는 docs/ 이동 검토
- desktop.ini는 삭제

---

### 2. papers 폴더 처리

현재 papers/ 폴더는 역할이 불명확하다.

확인 대상:

- desktop.ini
- 스크린샷 파일

조치 후보:

- archive 이동
- docs 이동
- 폴더 삭제

최종 판단 후 단일 구조 유지.

---

### 3. archive 파일명 개선

현재:

- a.md
- aa.md

문제:

파일명만으로 내용을 알 수 없음.

권장:

- ResearchProgramNotes.md
- CompletedTaskList.md

또는 실제 내용에 맞는 이름으로 변경.

---

### 4. 이미지 로컬화

현재 일부 이미지가 외부 링크 또는 GitHub user-attachments 링크에 의존할 가능성이 있다.

목표:

- images/ 폴더 내부 저장
- 논문 내 링크 수정
- 외부 링크 의존성 제거

---

## 연구 명칭 통일 작업

현재 다음 명칭이 혼재한다.

- KMap Equivalence Theory
- Structure Invariance
- Variable Rearrangement Invariance

향후 작업:

- 용어 간 관계 정리
- 대표 명칭 선정
- README 및 문서 전체 일관성 검토

---

## 삭제 후보 문서

다음 문서는 내용이 다른 문서에 완전히 흡수되었는지 확인 후 삭제 후보로 분류한다.

- archive/HANDOVER_antigravity.md
- archive/HANDOVER_antigravity1.md

반면 아래 문서는 삭제하지 말 것.

- docs/HANDOVER_MASTER.md
- docs/RESEARCH_PROGRAM_HANDOVER.md
- docs/RepositoryRefactoringReport.md

RepositoryRefactoringReport.md는 현재 구조가 왜 만들어졌는지 설명하는 역사 문서이다.

---

## 문서 체계

HANDOVER_MASTER.md
→ 프로젝트 인수인계

RESEARCH_PROGRAM_HANDOVER.md
→ 연구 프로그램 인수인계

REPOSITORY_CLEANUP_PLAN.md
→ 저장소 정리 인수인계

---

## 다음 AI에게

이 저장소의 주요 문제는 더 이상 대규모 구조 개편이 아니다.

남은 과제는:

1. 최종 청소
2. 파일 통폐합
3. 명칭 통일
4. 이미지 독립성 확보

이다.

새로운 폴더를 만드는 것보다 기존 구조를 단순화하는 방향을 우선하라.