# Assembly Previews

`.SLDASM` 파일은 GitHub에서 바로 렌더링되지 않습니다. 이 폴더는 assembly 폴더를 시각적으로 확인하기 위한 미리보기 이미지를 모아둔 곳입니다.

## eDrawings Captures

`edrawings-captures/`에는 eDrawings에서 직접 열어 캡처한 assembly 화면을 조립체별로 정리했습니다.

| Capture folder | Related assembly |
| --- | --- |
| `edrawings-captures/balancing-robot-ver4/` | `models/assemblies/assemble/balancing-robot/balancing robot_ver4.SLDASM` |
| `edrawings-captures/mapxiii/` | `models/assemblies/assemble/MAPXIII/MAPXIII.SLDASM` |
| `edrawings-captures/dust-signal-light/` | `models/assemblies/assemble/미세먼지신호등/미세먼지신호등.SLDASM` |
| `edrawings-captures/dust-signal-light-internal-column-45deg/` | `models/assemblies/assemble/미세먼지신호등/미세먼지신호등_내부기둥45도버전.SLDASM` |
| `edrawings-captures/dust-signal-light-solution1-pushlack/` | `models/assemblies/assemble/미세먼지신호등 솔루션1/*.SLDASM` |
| `edrawings-captures/dust-signal-light-solution2-pushlack/` | `models/assemblies/assemble/미세먼지신호등 솔루션2/*.SLDASM` |
| `edrawings-captures/elevator/` | `models/assemblies/assemble/엘레베이터/엘레베이터.SLDASM` |
| `edrawings-captures/cabin-top/` | `models/assemblies/assemble/엘레베이터/캐빈위.SLDASM` |
| `edrawings-captures/double-cyclone/` | `models/assemblies/assemble/신형사이쿨론/이중 사이클론.SLDASM` |
| `edrawings-captures/intelligent-robot-combined-vr1/` | `models/assemblies/assemble/지능형로봇공모전/지능형로봇합체본_vr1.SLDASM` |
| `edrawings-captures/bookmark/` | `models/assemblies/assemble/책깔피/책깔피.SLDASM` |

![eDrawings capture contact sheet](edrawings-capture-contact-sheet.png)

## What Worked

Before eDrawings captures were added, these STL-based previews were used as lightweight substitutes.

| Preview | Related assembly / project | Source STL |
| --- | --- | --- |
| `double-cyclone.png` | `assemblies/assemble/신형사이쿨론/이중 사이클론.SLDASM` | `models/stl-exports/stl/이중사이클론/이중_사이클론_1.STL` |
| `elevator-assembly-related.png` | `assemblies/assemble/엘레베이터/*.SLDASM` | `models/stl-exports/stl/패싱 엘리베이터/케빈/리니어 연결장치.STL` |
| `intelligent-robot-assembly-related.png` | `assemblies/assemble/지능형로봇공모전/지능형로봇합체본_vr1.SLDASM` | `models/stl-exports/stl/지능형/몸체바디/몸체바디.STL` |
| `bookmark-assembly-related.png` | `assemblies/assemble/책깔피/책깔피.SLDASM` | `models/stl-exports/stl/책깔피/나무_책깔피_도안_up.STL` |

## What Did Not Work

일부 `.SLDASM` 파일에는 내부 preview 데이터처럼 보이는 바이트가 있었지만, 현재 환경에서는 완전한 이미지로 추출되지 않았습니다. SolidWorks나 eDrawings가 있는 환경에서는 더 정확한 assembly screenshot을 만들 수 있습니다.

## Contact Sheet

![Assembly preview contact sheet](assembly-preview-contact-sheet.png)
