# Assembly File Index

This folder collects the assembly entry files found in the model archive.

The original files under `models/source-cad/` are intentionally preserved in place. CAD assemblies often depend on relative part references, so this archive keeps a curated copy in `models/assemblies/assemble/` without breaking the original source folders.

이 정리는 GitHub에서 조립 파일을 설명하기 위한 공개용 색인입니다. 원본 CAD 폴더에 흩어져 있던 assembly entry file을 한곳에서 찾을 수 있게 모으고, 실제 조립 상태는 eDrawings 캡처와 연결했습니다.

이 폴더를 보는 순서는 파일명보다 설계 흐름에 가깝습니다. 먼저 assembly entry file로 어떤 조립체가 있었는지 확인하고, 그 다음 preview 이미지에서 전체 형상과 주요 방향을 봅니다. 마지막으로 프로젝트 노트에서 왜 그런 구조를 시도했는지 읽을 수 있게 연결하는 것이 목표입니다.

## Current Count

| Type | Count |
| --- | ---: |
| SolidWorks assembly `.SLDASM` | 18 |
| CATIA product `.CATProduct` | 5 |

## Visual Previews

eDrawings screenshots for the main assemblies are organized at `../../images/assembly-previews/edrawings-captures/`.

These screenshots are useful because the raw assembly files do not render on GitHub. They show the overall shape, orientation, and visible part relationships before someone downloads the CAD files.

The top-level preview images in `../../images/assembly-previews/` now use eDrawings captures rather than the older STL-derived substitutes.

## Project Groups

| Group | Assembly files |
| --- | --- |
| `balancing-robot/` | `balancing robot_No_wheel.SLDASM`, `balancing robot_ver4.SLDASM`, CATIA product versions in `catia/`, and `new-balancerobot/balence_robot.SLDASM` |
| `MAPXIII/` | `MAPXIII.SLDASM` |
| `미세먼지신호등/` | `미세먼지신호등.SLDASM`, `미세먼지신호등_내부기둥45도버전.SLDASM` |
| `미세먼지신호등 솔루션1/` | `.SLDASM`, `어셈블리2.SLDASM` |
| `미세먼지신호등 솔루션2/` | `미세먼지 신호등 어셈블_솔루션2.SLDASM`, `미세먼지솔루션2.SLDASM` |
| `신형사이쿨론/` | `신형사이클론 초안.SLDASM`, `이중 사이클론.SLDASM` |
| `엘레베이터/` | `엘레베이터.SLDASM`, `캐빈위.SLDASM`, `kabin.SLDASM` |
| `운동기구/` | `chair bar.SLDASM` |
| `지능형로봇공모전/` | `지능형로봇합체본_vr1.SLDASM` |
| `책깔피/` | `책깔피.SLDASM` |

## Copied Into This Index

| Source | Curated copy |
| --- | --- |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_No_wheel.SLDASM` | `models/assemblies/assemble/balancing-robot/balancing robot_No_wheel.SLDASM` |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_ver4.SLDASM` | `models/assemblies/assemble/balancing-robot/balancing robot_ver4.SLDASM` |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_ver1.CATProduct` | `models/assemblies/assemble/balancing-robot/catia/balancing robot_ver1.CATProduct` |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_ver2.CATProduct` | `models/assemblies/assemble/balancing-robot/catia/balancing robot_ver2.CATProduct` |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_ver3.CATProduct` | `models/assemblies/assemble/balancing-robot/catia/balancing robot_ver3.CATProduct` |
| `models/source-cad/SLDPRT/balancing robot/balancing robot_ver4.CATProduct` | `models/assemblies/assemble/balancing-robot/catia/balancing robot_ver4.CATProduct` |
| `models/source-cad/SLDPRT/balancing robot/Modeling_lks/balancing_assemble_ver1.CATProduct` | `models/assemblies/assemble/balancing-robot/catia/balancing_assemble_ver1.CATProduct` |
| `models/source-cad/SLDPRT/new_balencerobot/assemble/balence_robot.SLDASM` | `models/assemblies/assemble/balancing-robot/new-balancerobot/balence_robot.SLDASM` |
| `models/source-cad/SLDPRT/passing elevator/kabin.SLDASM` | `models/assemblies/assemble/엘레베이터/kabin.SLDASM` |
| `models/source-cad/SLDPRT/운동/chair bar.SLDASM` | `models/assemblies/assemble/운동기구/chair bar.SLDASM` |
