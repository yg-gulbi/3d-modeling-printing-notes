# 3D Modeling and Printing Notes

Personal study and build notes for 3D modeling, CAD export, assembly review, and 3D printing practice.

이 저장소는 단순한 CAD/STL 파일 모음이 아니라, 프로젝트별로 **문제 정의, 설계 의도, assembly, 부품 파일, export, 캡처 이미지, 반복 노트**를 함께 보관하는 공개 학습 아카이브입니다.

## How To Read This Repository

가장 먼저 [portfolio/](portfolio/)를 보면 됩니다. 각 프로젝트 폴더 안에는 다음 단위가 함께 들어 있습니다.

| Folder | Meaning |
| --- | --- |
| `README.md` | 프로젝트의 문제, 설계 의도, 핵심 판단 |
| `assemblies/` | SolidWorks/CATIA assembly entry files |
| `parts/source-cad/` | 관련 원본 부품 CAD |
| `exports/` | STL/STEP 등 공개용 출력 파일 |
| `images/` | eDrawings 캡처, 모델 preview, 실제 사진 |
| `notes/` | 보조 설명, 케이스/마운트/반복 기록 |

이 구조의 목적은 한 프로젝트를 이해하기 위해 `models`, `images`, `projects`를 계속 오가지 않게 만드는 것입니다. 예를 들어 미세먼지 신호등은 [portfolio/dust-signal-light/](portfolio/dust-signal-light/) 안에서 assembly, 부품, 캡처, 설명을 함께 볼 수 있습니다.

## Portfolio Map

| Project | What it shows |
| --- | --- |
| [Balancing robot](portfolio/balancing-robot/) | 실제 로봇에 들어가는 보드 플레이트, 센서 케이스, 배터리/보드 배치, 내부 조립 계획 |
| [Dust signal light](portfolio/dust-signal-light/) | 내부 공간 부족 문제를 해결하기 위한 신호등 구조 개선, push-lock/push-latch 계열 실험 |
| [Cyclone systems](portfolio/cyclone-systems/) | 일반/신형/이중 사이클론 구조와 반복 설계 |
| [Passing elevator](portfolio/passing-elevator/) | 엘리베이터/캐빈/리니어 이동 구조 |
| [Intelligent chair](portfolio/intelligent-chair/) | 지능형 로봇 공모전 계열에서 파생된 의자형 몸체, 케이스, 센서 구조 |
| [Mechanical design exercises](portfolio/mechanical-design-exercises/) | 공차, 스프링, 링크, 판 부착장치 등 기계설계 연습 |
| [MAPXIII](portfolio/mapxiii/) | MAPXIII assembly와 관련 CAD 정리 |
| [Utility and mechanism models](portfolio/utility-and-mechanism-models/) | 책갈피, 컵받이, 왕복기관, 운동기구 등 소형 모델 |

## Why This Structure Changed

기존 구조는 파일 종류별이었습니다. assembly는 `models/assemblies`, 부품은 `models/source-cad`, 사진은 `images`, 설명은 `projects`에 흩어져 있었습니다. 보관에는 괜찮지만 GitHub에서 보는 사람에게는 서사가 끊겨 보였습니다.

이제는 프로젝트 단위로 묶었습니다. 한 폴더 안에서 “무엇을 만들었는가”, “어떤 부품과 assembly가 있었는가”, “어떻게 보이는가”, “왜 그렇게 바꿨는가”를 이어서 읽을 수 있게 했습니다.

## Archive

[archive/](archive/)에는 정리 과정에서 프로젝트 단위로 바로 넣기 애매한 mixed source나 예전 manifest를 보관합니다. 주 흐름은 `portfolio/`이고, `archive/`는 추적과 보존을 위한 보조 영역입니다.

## Related Project

- Main robot project: [Self-Balancing-Robot-with-Arduino-and-ROS](https://github.com/yg-gulbi/Self-Balancing-Robot-with-Arduino-and-ROS)
