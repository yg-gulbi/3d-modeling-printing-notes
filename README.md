# 3D Modeling and Printing Notes

Personal study and build notes for 3D modeling, CAD export, and 3D printing practice.

이 저장소는 3D 모델링과 3D 프린팅을 공부하면서 직접 만들고 정리한 과정을 모아두는 공개 학습 기록입니다. 단순히 STL을 모아둔 저장소가 아니라, 부품 배치, 출력 가능성, 조립성, 센서/보드/배터리 장착, 실패 후 수정 과정을 한 흐름으로 남깁니다.

## Why This Repository

짧은 설명:

> CATIA/SolidWorks 기반으로 로봇 하드웨어 부품, 센서 케이스, 보드/배터리 플레이트를 모델링하고 STL/STEP로 출력 준비 및 조립 검증까지 수행했습니다.

## Highlights

| Result | What it shows | Evidence |
| --- | --- | --- |
| Self-balancing robot hardware parts | 실제 로봇에 들어가는 보드 플레이트, 케이스, 사이드 프레임, 센서 마운트 설계 | [balancing robot notes](projects/balancing-robot-hardware.md), [CAD exports](cad_exports/balancing-robot), [organized model archive](models) |
| Internal assembly planning | Arduino, ODrive, 배터리, 센서, 카메라 배치를 고려한 내부 구조 설계 | [assembly views](images/catia_internal_assembly_views.jpg) |
| Print and iteration notes | 출력 가능한 형상, 브라켓 보호, 장착 방향, 실패 후 수정 기준 정리 | [design-to-print workflow](notes/design-to-print-workflow.md), [lab print practice](prints/lab-print-practice.md) |

## Build Log

| Area | Notes |
| --- | --- |
| Robot body and plates | 밸런싱 로봇의 하드웨어 배치와 출력 부품을 중심으로 정리했습니다. |
| Cases and mounts | Gemini 335, LiDAR, receiver, board plate처럼 센서/전자부품을 고정하기 위한 케이스와 마운트 경험을 분리했습니다. |
| Print practice | 연구실 프린트 실습, 외부 다운로드 모델 검토, 출력 실패/개선 관찰은 출처와 공개 가능성을 구분했습니다. |

## Repository Layout

| Path | Purpose |
| --- | --- |
| `projects/` | 대표 제작 프로젝트별 설명 |
| `prints/` | 출력 실습, 실패/개선 노트 |
| `cad_exports/` | README에서 바로 볼 대표 STL/STEP export 일부 |
| `models/` | 정리된 원본 CAD, assembly, STL export 아카이브 |
| `images/` | README와 프로젝트 문서에 쓰는 가벼운 이미지 |
| `notes/` | 설계-출력 워크플로와 공개 정책 |

## What I Learned

- CAD 모델은 보기 좋은 형상보다 **조립 순서, 간섭, 케이블 공간, 출력 방향**이 더 중요하다는 점을 체감했습니다.
- 센서와 보드를 넣는 로봇 케이스는 외형보다 **유지보수 접근성**과 **부품 고정 방식**이 결과 품질을 좌우했습니다.
- 프린팅에서는 출력 실패 자체보다, 실패를 보고 **벽 두께, 지지대, 체결부, 보호 브라켓**을 어떻게 고치는지가 핵심이었습니다.

## Limitations

- 모든 원본 CAD를 공개하지 않습니다. 일부 파일은 연구실 맥락, 라이선스, 외부 모델 출처가 섞여 있어 공개용 export만 선별했습니다.
- 다운로드 모델은 직접 제작 산출물로 주장하지 않고, 출력 실습/참고 자료로만 기록합니다.
- 이 저장소는 제조용 공식 도면 세트가 아니라 개인 학습과 제작 과정을 정리한 공개 아카이브입니다.

## Related Project

- Main robot project: [Self-Balancing-Robot-with-Arduino-and-ROS](https://github.com/yg-gulbi/Self-Balancing-Robot-with-Arduino-and-ROS)
