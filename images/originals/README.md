# originals/ — 원본 파일 보존 디렉터리
## 1KMapStructureInvariance

**생성일:** 2026-06-05 (Phase 2 실행)  
**목적:** Phase 2 표준화 작업 전 모든 원본 이미지 파일의 변경 불가 복사본을 보존합니다.  
**규칙:** 이 폴더의 파일은 **절대 수정·삭제 금지**. 읽기 전용으로 취급.

---

## ⚠️ 복사 필요 — 아직 미완료

이 폴더를 생성한 AI 세션은 PNG(이진 파일)를 텍스트 도구로 복사할 수 없어,  
실제 파일 복사는 **연구자가 직접** 수행해야 합니다.

### 복사 대상 파일 (images/ → images/originals/)

논문 본문 그림 (로컬 확보분 전부 복사):
```
fig5_2_nand_kmap.png
fig5_3_nor_kmap.png
fig5_4_nand_xor_circuit.png
fig5_5_nor_xor_circuit.png
fig5_16_complement_kmap.png
ABCDXOR.png     ABCDXNOR.png
ACBDXOR.png     ACBDXNOR.png
ADBCXOR.png     ADBCXNOR.png
xor_plane_checkerboard_example_1_and_2.png
xnor_plane_checkerboard_example_1_and_2.png
```

5.5절 보조 시각자료:
```
fig5_5_1_coordinate_system.svg
row_variable_swap_kmap_comparison.png
column_variable_swap_kmap_comparison.png
greycode_index_conversion_xy_to_yx.png
greycode_index_conversion_zw_to_wz.png
coordinate_transformation_rows_column_swap.png
alphabet_array_diagonal_symmetry.png
greycode_array_diagonal_symmetry.png
dihedral_group_d4_symmetry_operations.png
kmap_equivalence_transformation_generators.png
kmap_variable_arrangement_equivalence_class.png
```

기타:
```
프레젠테이션1.pptx  → originals/ 보존 후 docs/ 폴더로 이동
desktop.ini         → .gitignore에 추가 후 무시
```

### 복사 방법

**PowerShell (images/ 폴더에서 실행):**
```powershell
Copy-Item *.png originals\
Copy-Item *.svg originals\
Copy-Item *.pptx originals\
```

---

## 표준 파일명 대응표

### A. 논문 본문 그림 (확보분)

| 현재 파일명 | 표준 파일명 | 논문 그림 번호 |
|---|---|---|
| (GitHub URL) | `Figure01_xor_xnor_checkerboard.png` | 5.1 |
| `fig5_2_nand_kmap.png` | `Figure02_nand_kmap.png` | 5.2 |
| `fig5_3_nor_kmap.png` | `Figure03_nor_kmap.png` | 5.3 |
| `fig5_4_nand_xor_circuit.png` | `Figure04_nand_xor_circuit.png` | 5.4 |
| `fig5_5_nor_xor_circuit.png` | `Figure05_nor_xor_circuit.png` | 5.5 |
| `ABCDXNOR.png`+`ACBDXNOR.png`+`ADBCXNOR.png` | `Figure06_variable_rearrangement_xnor.png` | 5.6 |
| `ABCDXOR.png`+`ACBDXOR.png`+`ADBCXOR.png` | `Figure07_variable_rearrangement_xor.png` | 5.7 |
| `xor_plane_checkerboard_example_1_and_2.png` | `Figure08_xor_plane_checkerboard.png` | 5.8 |
| (GitHub URL) | `Figure09_xor_line_checkerboard.png` | 5.9 |
| (GitHub URL) | `Figure10_xor_diagonal_checkerboard.png` | 5.10 |
| `xnor_plane_checkerboard_example_1_and_2.png` | `Figure11_xnor_plane_checkerboard.png` | 5.11 |
| (GitHub URL) | `Figure12_xnor_line_checkerboard.png` | 5.12 |
| (GitHub URL) | `Figure13_xnor_diagonal_checkerboard.png` | 5.13 |
| (GitHub URL) | `Figure14_symmetry_neg_slope_a.png` | 5.14 |
| (GitHub URL) | `Figure15_symmetry_neg_slope_b.png` | 5.15 |
| `fig5_16_complement_kmap.png` | `Figure16_complement_symmetry_kmap.png` | 5.16 |

### B. 5.5절 보조 시각자료

| 현재 파일명 | 표준 파일명 |
|---|---|
| `fig5_5_1_coordinate_system.svg` | `FigureS01_coordinate_system.svg` |
| `row_variable_swap_kmap_comparison.png` | `FigureS02_row_var_swap_comparison.png` |
| `column_variable_swap_kmap_comparison.png` | `FigureS03_col_var_swap_comparison.png` |
| `greycode_index_conversion_xy_to_yx.png` | `FigureS04_greycode_xy_to_yx.png` |
| `greycode_index_conversion_zw_to_wz.png` | `FigureS05_greycode_zw_to_wz.png` |
| `coordinate_transformation_rows_column_swap.png` | `FigureS06_rows_col_swap_transform.png` |
| `alphabet_array_diagonal_symmetry.png` | `FigureS07_alphabet_diagonal_symmetry.png` |
| `greycode_array_diagonal_symmetry.png` | `FigureS08_greycode_diagonal_symmetry.png` |
| `dihedral_group_d4_symmetry_operations.png` | `FigureS09_d4_symmetry_operations.png` |
| `kmap_equivalence_transformation_generators.png` | `FigureS10_equiv_transform_generators.png` |
| `kmap_variable_arrangement_equivalence_class.png` | `FigureS11_var_arrangement_equiv_class.png` |

---

## 긴급: 로컬 미확보 그림 복구

아래 7개 그림은 GitHub user-attachments URL로만 존재합니다.  
최종 제출 전 반드시 해당 URL에서 다운로드하여 여기에 보존하세요:

- `Figure01_xor_xnor_checkerboard.png` (논문 5.1)
- `Figure09_xor_line_checkerboard.png` (논문 5.9)
- `Figure10_xor_diagonal_checkerboard.png` (논문 5.10)
- `Figure12_xnor_line_checkerboard.png` (논문 5.12)
- `Figure13_xnor_diagonal_checkerboard.png` (논문 5.13)
- `Figure14_symmetry_neg_slope_a.png` (논문 5.14)
- `Figure15_symmetry_neg_slope_b.png` (논문 5.15)

URL 확인 방법: `paper/통합논문_제출준비본.md`에서 해당 그림 번호 검색

---

*참조: ../figure_inventory.md*
