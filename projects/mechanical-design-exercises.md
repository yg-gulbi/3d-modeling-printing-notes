# Mechanical Design Exercises

기계설계2 관련 폴더는 공차, 스프링, 팔, 판 부착장치처럼 기본 기계 요소를 모델링하며 버전을 비교한 연습 기록입니다. 같은 과제 흐름 안에서 미세먼지 신호등의 내부 작업 공간 문제를 해결하는 설계도 함께 다뤘습니다. 여기서 `미세먼지신호등`, `미세먼지`, `솔루션1`, `솔루션2`, `내부기둥45도버전`은 따로 떨어진 과제가 아니라 한 제품 안에서 구조를 계속 바꿔 본 흐름으로 연결합니다.

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

기본이 되는 일반 `미세먼지신호등`은 실제 모형에 가까운 구조였고, `미세먼지` 계열은 그 신호등 자체 안에서 안쪽 판의 형태를 바꿔 내부 공간을 넓히려던 시도였습니다. `내부기둥45도버전`은 안의 판을 45도로 돌리면 작업이 더 쉬워질지 확인한 안이었지만, 효율이 떨어졌고 기존 구조에도 적용이 쉽지 않았습니다.

이후 `솔루션1`, `솔루션2`는 push latch / push-lock 계열 아이디어를 참고한 후속안입니다. `솔루션1`은 형태가 다소 흐물흐물하다고 판단되어, 보다 단단한 방향으로 `솔루션2`로 바뀐 흐름으로 정리합니다. 자세한 내용은 [dust signal light](dust-signal-light.md)에 함께 정리했습니다.

## Open Notes

- `솔루션2`가 `솔루션1`보다 실제로 어떻게 더 단단해졌는지 세부 차이 추가 가능
