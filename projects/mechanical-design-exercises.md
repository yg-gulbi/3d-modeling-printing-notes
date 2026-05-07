# Mechanical Design Exercises

기계설계2 관련 폴더는 공차, 스프링, 팔, 판 부착장치처럼 기본 기계 요소를 모델링하며 버전을 비교한 연습 기록입니다. 같은 과제 흐름 안에서 미세먼지 신호등의 내부 작업 공간 문제를 해결하는 설계도 함께 다뤘습니다.

![Mechanical design spring preview](../images/model-previews/mechanical-design-spring.png)

## Model Groups

| Group | Where |
| --- | --- |
| Source CAD | `models/source-cad/SLDPRT/기계설계2*`, `models/source-cad/SLDPRT/너트볼트공차Test` |
| STL exports | `models/stl-exports/stl/기계설계2_1`, `models/stl-exports/stl/기계설계2_2` |
| Related assignment model | `models/source-cad/SLDPRT/미세먼지신호등`, `models/assemblies/assemble/미세먼지*` |

## What This Captures

- 스프링, 팔, 판 부착장치, 바디처럼 부품 단위로 나눠 모델링한 흐름
- `scale`, `square`, `vr2`, `solution`처럼 조건을 바꾸며 비교한 흔적
- 출력/조립 공차를 감각적으로 익힌 기록
- 미세먼지 신호등 내부 공간이 부족해서 작업자의 작업 시간이 늘어나는 문제를 구조적으로 개선하려 한 과제 맥락

## Assignment Link

미세먼지 신호등 과제의 핵심 문제는 내부 공간이 부족해 배선, LED 판, 내부 부품 작업 시간이 늘어난다는 점이었습니다. 단순히 선을 정리하는 방식보다, 옆 LED 판을 쉽게 탈착할 수 있게 만들어 작업자가 빠르게 접근하고 조립할 수 있는 구조를 목표로 잡았습니다.

이 접근은 기존 push latch / push-lock 장비의 원리를 참고하되, 과제 모델에 맞게 직접 변형한 구조로 정리합니다. 자세한 내용은 [dust signal light](dust-signal-light.md)에 따로 정리했습니다.

## Open Notes

- `solution1`, `solution2`가 구체적으로 어떤 push-lock 구조 차이를 가졌는지 추가 확인 필요
