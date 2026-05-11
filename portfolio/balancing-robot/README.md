# Balancing Robot

밸런싱 로봇 프로젝트의 모델링 자료입니다. 핵심은 로봇 안에 Arduino Mega, ODrive, BNO055, Gemini 335, receiver, 배터리와 보조 회로를 실제로 배치하고, 출력 가능한 하드웨어 구조로 나누는 것이었습니다.

![CATIA body design](images/balancing-robot/catia_body_design.jpg)

## Contents

| Folder | Content |
| --- | --- |
| `assemblies/` | SolidWorks/CATIA assembly entry files |
| `parts/source-cad/` | robot body, plates, sensor cases, board references |
| `exports/public-cad/` | selected STL/STEP files for public viewing |
| `exports/stl/` | STL export sets |
| `images/balancing-robot/` | CATIA screenshots and real robot photos |
| `images/edrawings/` | eDrawings assembly captures |
| `notes/` | cases and mounts note |

## Representative Exports

| File | Role |
| --- | --- |
| `exports/public-cad/balancing_robot_board_plate.stl` / `.stp` | board mounting plate |
| `exports/public-cad/balancing_robot_package_ver2.stl` | electronics package experiment |
| `exports/public-cad/balancing_robot_side_ver2.stl` | side frame / protection structure |
| `exports/public-cad/battery_plate.stl` | battery mount |
| `exports/public-cad/gemini335_case.stl` | RGB-D camera case |
| `exports/public-cad/lidar_case_ver2.stl` | LiDAR / sensor mount |
| `exports/public-cad/robot_neck.stl` | upper sensor head connection |

## Assembly Thinking

![Internal assembly views](images/balancing-robot/catia_internal_assembly_views.jpg)

이 프로젝트에서 중요한 것은 부품 하나의 모양보다 조립 후 유지보수 가능성이었습니다. 배터리 무게중심, 센서 시야, 케이블 라우팅, 보드 접근성, 넘어졌을 때 보호 구조가 함께 맞아야 했습니다.

## Related Notes

- [Cases and mounts](notes/cases-and-mounts.md)
