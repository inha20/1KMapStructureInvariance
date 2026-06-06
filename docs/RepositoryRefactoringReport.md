# Repository Refactoring Report

## 목적

본 문서는 CarnomapMinorThesis 저장소의 구조를 정리하고,
연구 문서와 관리 문서를 분리하기 위한 리팩토링 계획을 기록한다.

---

# 현재 상태

루트 폴더에 다음 종류의 문서가 혼재되어 있다.

- 논문 원고
- 연구 확장 문서
- AI 인수인계 문서
- 이미지 복구 문서
- 저장소 관리 문서

이로 인해 저장소의 목적이 즉시 드러나지 않는다.

---

# 권장 구조

```text
CarnomapMinorThesis

README.md

paper/
 └─ 통합논문_최종완성본.md

research/
 └─ KMapEquivalenceTheory.md

docs/
 ├─ HANDOVER_MASTER.md
 ├─ MissingImages.md
 ├─ UpgradePlan.md
 └─ RepositoryRefactoringReport.md

images/
references/

archive/
 └─ 통합논문_최종완성본1.md
```

---

# 파일 분류

## 메인 논문

### 통합논문_최종완성본.md

역할:
- 저장소의 핵심 결과물

조치:
- 유지

---

## 이전 버전

### 통합논문_최종완성본1.md

역할:
- 이전 원고
- 백업

조치:
- archive 이동

---

## 연구 확장 문서

### PlusOnMinorThrsis.md

주요 내용:
- 변수 배치 동치류
- D4 군
- 24→6→3 축약
- 구조 보존 해석

권장 이름:

KMapEquivalenceTheory.md

조치:
- research 폴더 이동

---

## 인수인계 문서

### HANDOVER_antigravity.md
### HANDOVER_antigravity1.md

주요 내용:
- 연구 진행 상황
- 향후 작업
- 이미지 복구 계획
- D4 관련 작업

조치:
- HANDOVER_MASTER.md로 통합

---

## 작업 문서

### missingImages.md

역할:
- 이미지 복구 체크리스트

조치:
- docs 이동

---

### upgrade.md

역할:
- 향후 개선 계획

조치:
- docs 이동
- UpgradePlan.md로 변경

---

# 연구 프로그램 관점

현재 연구는 다음과 같이 발전하고 있다.

카르노맵 패턴 분석
→ 대칭성 분석
→ 변수 재배열
→ 구조 불변성
→ 군론(D4, S4)
→ 인간의 구조 이해
→ AI와 인간의 구조 이해 비교

카르노맵은 연구 대상이며,
장기적인 연구 주제는 구조 불변성 연구로 발전하고 있다.

---

# 우선순위

1. README 정비
2. 이미지 복구
3. 폴더 구조 정리
4. GitHub Pages 구축
5. 변수 재배열 논문 독립화
6. 구조 불변성 연구 확장
