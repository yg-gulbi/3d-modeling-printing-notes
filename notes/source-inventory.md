# Source Inventory

이 저장소에는 모든 원본 자료를 그대로 넣지 않았습니다. 직접 만든 것, 공개해도 되는 것, 학습 과정 설명에 필요한 것을 중심으로 선별했습니다.

## Included

| Type | Included examples | Why |
| --- | --- | --- |
| CAD exports | STL/STP files in `cad_exports/balancing-robot` | 바로 보기 좋은 대표 출력/교환 파일 |
| Organized model archive | `models/source-cad`, `models/stl-exports`, `models/assemblies` | 내가 주제별로 정리해 둔 모델링 파일을 최대한 보존 |
| Images | CATIA screenshots and robot process photos | 설계 의도와 조립 흐름을 설명하기 위한 가벼운 시각 자료 |
| Notes | workflow, print practice, publication policy | 나중에 다시 볼 수 있는 학습 기록 |

## Not Included

| Type | Reason |
| --- | --- |
| Unorganized or unclear folders | 직접 만든 것인지, 출력 연습용 외부 모델인지 맥락을 확인하기 어려운 경우 제외 |
| Download-only folders | 직접 만든 결과물과 혼동되지 않도록 `download_file`, 외부 모델 묶음은 제외 |
| G-code / slicer outputs | 프린터/필라멘트/설정 의존성이 커서 장기 보관 가치가 낮음 |
| Raw videos | 용량이 크고 학습 기록에는 가벼운 이미지가 충분함 |

## Current Inclusion Rule

- Include: organized modeling folders such as `SLDPRT`, `stl`, and `assemble`.
- Exclude: `download_file`, `g-code`, broad lab print-download folders, and clearly external downloaded models.
- Keep context: some assembly folders may contain reference component models used for fit-checking. They are kept as part of the modeling study context, not claimed as original product designs.
