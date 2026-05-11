# Source Inventory

이 저장소에는 모든 원본 자료를 무작정 넣지 않고, 직접 만든 것, 공개해도 되는 것, 학습 과정 설명에 필요한 것을 중심으로 선별했습니다.

## Included

| Type | Included examples | Why |
| --- | --- | --- |
| Portfolio project folders | `portfolio/<project>/README.md`, `assemblies/`, `parts/`, `exports/`, `images/` | 한 프로젝트의 설명, 부품, assembly, preview를 함께 읽을 수 있게 하기 위해 |
| CAD exports | `portfolio/*/exports/` | GitHub에서 바로 확인하거나 다운로드하기 쉬운 STL/STEP 파일 |
| Source CAD | `portfolio/*/parts/source-cad/` | assembly와 부품 맥락을 보존하기 위해 |
| Images | `portfolio/*/images/edrawings/`, `portfolio/*/images/previews/` | 설계 의도와 조립 흐름을 설명하기 위한 시각 자료 |
| Archive | `archive/` | 프로젝트 단위로 바로 묶기 애매한 mixed source와 legacy manifest 보존 |
| Notes | `notes/` | workflow, print practice, publication policy, iteration notes |

## Not Included

| Type | Reason |
| --- | --- |
| Unorganized or unclear folders | 직접 만든 것인지, 출력 연습용 외부 모델인지 맥락을 확인하기 어려운 경우 제외 |
| Download-only folders | 직접 만든 결과물과 혼동되지 않도록 `download_file`, 외부 모델 묶음은 제외 |
| G-code / slicer outputs | 프린터/필라멘트/설정 의존성이 커서 장기 보관 가치가 낮음 |
| Raw videos | 용량이 크고 학습 기록에는 가벼운 이미지가 충분함 |

## Current Inclusion Rule

- Include: project-level folders where the design story, assembly, source parts, exports, and images can be read together.
- Archive: mixed or uncertain source folders that should be preserved but are not yet narratively organized.
- Keep context: some assembly folders may contain reference component models used for fit-checking. They are kept as part of the modeling study context, not claimed as original product designs.
