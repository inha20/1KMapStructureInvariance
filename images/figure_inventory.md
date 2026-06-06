# Figure Inventory — 1KMapStructureInvariance

**Date:** 2026-06-05  
**Status:** Phase 2 — Figure Standardization  
**Maintainer:** Choi Jonghun / ANTIGRAVITY

---

## 중요 주의사항

논문(`paper/통합논문_제출준비본.md`) 내 그림 5.1~5.16은 **GitHub user-attachments URL**로 참조됩니다.  
로컬 `images/` 폴더는 (1) 일부 그림의 로컬 백업, (2) 5.5절 보조 시각자료로 구성됩니다.  
**최종 제출 전 모든 GitHub URL의 404 여부를 브라우저에서 직접 확인해야 합니다.**

---

## A. 논문 본문 그림 (Figure 5.1–5.16)

| 논문 그림 번호 | 내용 | 로컬 파일 | 로컬 파일 상태 | 표준 파일명(안) |
|---|---|---|---|---|
| 5.1 | XOR/XNOR 체커보드 예시 | 없음 | ❌ 로컬 없음 | `Figure01_xor_xnor_checkerboard.png` |
| 5.2 | NAND 카르노맵 예시 | `fig5_2_nand_kmap.png` | ✅ 있음 | `Figure02_nand_kmap.png` |
| 5.3 | NOR 카르노맵 예시 | `fig5_3_nor_kmap.png` | ✅ 있음 | `Figure03_nor_kmap.png` |
| 5.4 | NAND-only XOR 회로도 | `fig5_4_nand_xor_circuit.png` | ✅ 있음 | `Figure04_nand_xor_circuit.png` |
| 5.5 | NOR-only XOR 회로도 | `fig5_5_nor_xor_circuit.png` | ✅ 있음 | `Figure05_nor_xor_circuit.png` |
| 5.6 | 변수 재배열 — XNOR 3종 | `ABCDXNOR.png`, `ACBDXNOR.png`, `ADBCXNOR.png` | ✅ 있음 (3분할) | `Figure06_variable_rearrangement_xnor.png` |
| 5.7 | 변수 재배열 — XOR 3종 | `ABCDXOR.png`, `ACBDXOR.png`, `ADBCXOR.png` | ✅ 있음 (3분할) | `Figure07_variable_rearrangement_xor.png` |
| 5.8 | XOR 평면체커 (2종) | `xor_plane_checkerboard_example_1_and_2.png` | ✅ 있음 | `Figure08_xor_plane_checkerboard.png` |
| 5.9 | XOR 라인체커 | 없음 | ❌ 로컬 없음 | `Figure09_xor_line_checkerboard.png` |
| 5.10 | XOR 대각체커 | 없음 | ❌ 로컬 없음 | `Figure10_xor_diagonal_checkerboard.png` |
| 5.11 | XNOR 평면체커 (2종) | `xnor_plane_checkerboard_example_1_and_2.png` | ✅ 있음 | `Figure11_xnor_plane_checkerboard.png` |
| 5.12 | XNOR 라인체커 | 없음 | ❌ 로컬 없음 | `Figure12_xnor_line_checkerboard.png` |
| 5.13 | XNOR 대각체커 | 없음 | ❌ 로컬 없음 | `Figure13_xnor_diagonal_checkerboard.png` |
| 5.14 | y=-x 대칭 A (2종) | 없음 | ❌ 로컬 없음 | `Figure14_symmetry_neg_slope_a.png` |
| 5.15 | y=-x 대칭 B (2종) | 없음 | ❌ 로컬 없음 | `Figure15_symmetry_neg_slope_b.png` |
| 5.16 | y=x 보수 대칭 | `fig5_16_complement_kmap.png` | ✅ 있음 | `Figure16_complement_symmetry_kmap.png` |

**로컬 백업 현황:** 9/16개 확보, 7개 미확보 (GitHub URL만 존재)

---

## B. 5.5절 보조 시각자료 (5.5절 전용)

이 파일들은 논문 본문 그림 번호와 별도로, 5.5절(`변수 배치의 수학적 분류: 동치류 이론`) 생성 시 작성된 보조 이미지입니다.

| 현재 파일명 | 관련 절 | 내용 | 표준 파일명(안) |
|---|---|---|---|
| `fig5_5_1_coordinate_system.svg` | 5.5.1 | 카르노맵 좌표계 정의 (SVG) | `FigureS01_coordinate_system.svg` |
| `row_variable_swap_kmap_comparison.png` | 5.5.2 | 행 변수 순서 교환 전후 비교 | `FigureS02_row_var_swap_comparison.png` |
| `column_variable_swap_kmap_comparison.png` | 5.5.2 | 열 변수 순서 교환 전후 비교 | `FigureS03_col_var_swap_comparison.png` |
| `greycode_index_conversion_xy_to_yx.png` | 5.5.2 | XY→YX 그레이코드 인덱스 변환 | `FigureS04_greycode_xy_to_yx.png` |
| `greycode_index_conversion_zw_to_wz.png` | 5.5.2 | ZW→WZ 그레이코드 인덱스 변환 | `FigureS05_greycode_zw_to_wz.png` |
| `coordinate_transformation_rows_column_swap.png` | 5.5.3 | 행열 교환 좌표 변환 | `FigureS06_rows_col_swap_transform.png` |
| `alphabet_array_diagonal_symmetry.png` | 5.5.3 | 알파벳 배열 대각선 대칭 | `FigureS07_alphabet_diagonal_symmetry.png` |
| `greycode_array_diagonal_symmetry.png` | 5.5.3 | 그레이코드 배열 대각선 대칭 | `FigureS08_greycode_diagonal_symmetry.png` |
| `dihedral_group_d4_symmetry_operations.png` | 5.5.4 | D₄ 군론 대칭 연산 목록 | `FigureS09_d4_symmetry_operations.png` |
| `kmap_equivalence_transformation_generators.png` | 5.5.4 | 동치 변환 생성도 | `FigureS10_equiv_transform_generators.png` |
| `kmap_variable_arrangement_equivalence_class.png` | 5.5.5 | 변수 배치 동치류 6→3 분류 | `FigureS11_var_arrangement_equiv_class.png` |

---

## C. 기타 파일

| 파일명 | 종류 | 처리 권고 |
|---|---|---|
| `프레젠테이션1.pptx` | PowerPoint 발표자료 | `docs/` 폴더로 이동 권고 |
| `desktop.ini` | 시스템 파일 | `.gitignore`에 추가 후 무시 |

---

## 표준화 작업 계획

### Phase 2 실행 전 체크리스트

- [ ] `images/originals/` 폴더 생성
- [ ] 현재 파일 전체를 `originals/`에 복사 (원본 보존)
- [ ] A 표의 파일들을 표준 파일명으로 복사본 생성
- [ ] B 표의 파일들을 표준 파일명으로 복사본 생성
- [ ] `프레젠테이션1.pptx`를 `docs/`로 이동
- [ ] GitHub URL 7개(5.1, 5.9~5.13, 5.14~5.15)에 대해 로컬 백업 파일 확보

### 로컬 미확보 그림 — 복구 우선순위

| 우선순위 | 그림 번호 | 복구 방법 |
|---|---|---|
| 🔴 필수 | 5.9, 5.10 | XOR 라인·대각체커 — GitHub URL에서 다운로드 또는 재생성 |
| 🔴 필수 | 5.12, 5.13 | XNOR 라인·대각체커 — 동일 |
| 🟡 권장 | 5.1 | XOR/XNOR 체커보드 예시 — GitHub URL에서 다운로드 |
| 🟡 권장 | 5.14, 5.15 | y=-x 대칭 A, B — GitHub URL에서 다운로드 |

---

*Last Updated: 2026-06-05*  
*Next review: Phase 2 figure standardization execution*
