> **보관된 이전 연구 노트.** 이 저장소는 저자의 이전 연구 노트이며, 내용은 [7번 논문](https://github.com/inha20/7GroupTheoryBooleanUnification)(수학)과 [8번 논문](https://github.com/inha20/8StructuralThinkingInAIEra)(이론과 사례)으로 정리·정정되었습니다. 일부 서술과 옛 포털에는 정정 전 내용이 있을 수 있으니 인용은 7·8번을 사용해 주세요.

# 1KMapStructureInvariance

**논문 제목:** 생성형 AI 시대에서 인간 구조적 사고의 교육적 의미  
**부제:** 생성형 AI 언어 생성 구조와 카르노맵 시각적 패턴 해석 사례를 중심으로  
**GitHub Pages:** [포털 보기](https://inha20.github.io/1KMapStructureInvariance/)

---

## Keywords

Karnaugh map, Boolean function, XOR, XNOR, checkerboard pattern, visual pattern analysis, structural recognition, grid-symmetry group theory, equivalence class, variable arrangement, generative AI, human structural thinking, educational implications

---

## Abstract (초록 요약)

생성형 AI는 확률적 패턴을 재현하지만, 인간은 구조를 인식·재배열하며 의미를 발견한다.
본 연구는 카르노맵의 시각적 패턴 해석을 실증 사례로 삼아 이 차이를 분석하고,
생성형 AI 시대 교육이 사고 과정 중심으로 발전해야 함을 제안한다.

특히 5.5절에서는 4변수 카르노맵 변수 배치의 동치류 이론을 행·열 변수 교환, 축 교환, 순환 이동을 통해 수학적으로 전개하여,
독립 배치가 정확히 세 가지(AB/CD, AC/BD, AD/BC)로 한정됨을 증명한다.

---

## Key Contributions (핵심 기여)

- 생성형 AI 언어 생성 구조와 인간 구조적 사고의 본질적 차이 분석
- 카르노맵 XOR/XNOR 체커보드 패턴 — 인간 구조 인식의 관찰 사례 제시
- 변수 배치 동치류 이론: 24 → 6 → 3 축약 과정의 수학적 증명 (행·열 변수 교환, 축 교환, 순환 이동)
- 생성형 AI 시대 교육 방향 제안 (사고 과정 중심, 메타인지 강화, AI 리터러시)

---

## Repository Structure (저장소 구조)

```
1KMapStructureInvariance/
├─ README.md                          ← 이 파일
├─ index.html                         ← GitHub Pages 포털
│
├─ paper/
│  └─ 통합논문_제출준비본.md            ← 최신 정리본 (초기 연구 노트)
│
└─ images/
   ├─ coordinate_transformation_rows_column_swap.png  ← 카르노맵 좌표계·축 교환 그림 (PNG, 그림 5.5.1)
   ├─ ABCDXOR.png, ABCDXNOR.png ...  ← 변수 배치별 카르노맵 이미지
   └─ (카르노맵 관련 이미지 다수)
```

---

## Paper Files (논문 파일)

| 파일 | 상태 | 설명 |
|---|---|---|
| `paper/통합논문_제출준비본.md` | ✅ 최신 완성본 | 제출 준비 상태 |

---

## Chapter 5 — Table of Contents (5장 목차)

```
5장 사례 연구: 카르노맵 시각적 패턴 해석
  5.1 인간 구조적 사고와의 연결
  5.2 카르노맵 기존 방식의 한계
  5.3 NAND/NOR 게이트의 카르노맵 해석 및 범용성
  5.4 범용 게이트의 존재성에 관한 증명
  5.5 변수 배치의 수학적 분류: 동치류 이론
    5.5.1 좌표계 및 표기법
    5.5.2 변수 순서 교환과 거울 대칭성
    5.5.3 축 교환과 대각선 대칭성
    5.5.4 동치 변환의 정의 (격자 대칭군 W 해석 포함)
    5.5.5 변수 배치의 동치류 분류
    5.5.6 소결론
  5.6 변수 재배열 기반 해석 방법
  5.7 체커보드 패턴과 XOR/XNOR 구조
    5.7.1 XOR 체커보드 패턴 분석
    5.7.2 XNOR 체커보드 패턴 분석
    5.7.3 3변수 체커보드 패턴 및 무관 변수 패턴
  5.8 대칭성과 함수 불변식
  5.9 이것이 인간 구조적 사고의 사례인 이유
```

---

## Key Formulas (주요 수식)

| 정리 | 수식 | 위치 |
|---|---|---|
| 행 변수 순서 교환 | XY/ZW ≡ YX/ZW | 5.5.2 |
| 열 변수 순서 교환 | XY/ZW ≡ XY/WZ | 5.5.2 |
| 축 교환 | XY/ZW ≡ ZW/XY | 5.5.3 |
| 동치류 수 | C(4,2)/2 = 3 | 5.5.5 |
| 대표 배치 | AB/CD, AC/BD, AD/BC | 5.5.5 |
| y=-x 대칭 | F(A,B,C,D)=F(C,D,A,B) | 5.8 |
| y=x 보수 대칭 | F(A,B,C,D)=F(C̄,D,Ā,B) | 5.8 |

---

## GitHub Setup (GitHub 설정)

> ⚠️ **이미지 표시 확인 필수:** 논문 내 이미지는 저장소 내 상대 경로(`../images/`)로 연결되어 있습니다.
> 최종 제출 전 모든 이미지가 정상 표시되는지 브라우저에서 직접 확인하고,
> GitHub 저장소가 **public** 상태인지 점검하세요.

**GitHub Pages 활성화 방법:**
1. GitHub에서 이 저장소를 `public`으로 설정
2. Settings → Pages → Source: `main` 브랜치 `/` (root) 선택
3. `index.html`이 포털 페이지로 자동 배포됨
4. URL: `https://inha20.github.io/1KMapStructureInvariance/`

---

## Future Work (향후 연구)

카르노맵 패턴 분석 → 대칭성 분석 → 변수 재배열 연구 → 구조 불변성 연구
→ 군론(D₄, S₄) 기반 해석 → 인간 구조 이해 연구 → AI와 인간 비교

---

## Research Program Links

This repository is part of the **Structure Recognition Research Program**.

| Repository | Role |
|---|---|
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | Program Hub |
| [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Empirical Case Study 1 ← You are here |
| [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Empirical Case Study 2 |
| [3VariableRearrangementInvarianceMinorThesis](https://github.com/inha20/3VariableRearrangementInvarianceMinorThesis) | Empirical Case Study 3 |
| [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory) | Theoretical Hub |

**AI 단일 진입점:** [SESSION_START.md](https://github.com/inha20/inha20/blob/main/SESSION_START.md)

---

## Author

Choi Jonghun  
Independent researcher · Graduate of Inha Technical College
