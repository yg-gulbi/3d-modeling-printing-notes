# Printed Passing Elevator Build

이 노트는 `archive/passing_elevator_medio`에 있던 실제 제작 확인 자료를 passing elevator 프로젝트 안으로 묶은 기록입니다. CAD assembly와 STL만 따로 보는 대신, 실제로 출력한 부품이 어떤 식으로 움직임 확인까지 이어졌는지를 같이 남깁니다.

## Media

| File | Role |
| --- | --- |
| [printed-assembly-01.jpg](../images/media/printed-assembly-01.jpg) | printed assembly reference photo |
| [printed-assembly-02.jpg](../images/media/printed-assembly-02.jpg) | printed assembly reference photo |
| [passing.mp4](../images/media/passing.mp4) | passing motion check |
| [non-passing.mp4](../images/media/non-passing.mp4) | non-passing motion comparison |
| [physical-review.mp4](../images/media/physical-review.mp4) | additional physical review clip |

## Build Story

이 모델은 단순히 엘리베이터 형태를 만든 것이 아니라, 캐빈과 바닥 구조, 연결 부품, 리니어 이동 방향을 따로 나누어 설계하고 실제 출력물로 맞물림을 확인한 작업입니다. `assemblies/`와 `parts/source-cad/`는 설계 단계의 근거이고, `exports/stl/`은 출력 가능한 형상, `images/media/`는 출력 후 움직임을 확인한 결과물입니다.

특히 `패싱`과 `논패싱` 영상은 같은 기구 구조가 움직임 조건에 따라 어떻게 다르게 보이는지 비교하는 자료로 남겨둡니다. 이 프로젝트를 다시 볼 때는 CAD 파일만 열어보는 것보다, 먼저 이 노트와 영상을 보고 어떤 동작을 검증하려 했는지 확인하는 편이 좋습니다.
