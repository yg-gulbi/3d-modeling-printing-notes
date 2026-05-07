# Organized Model Archive

이 폴더는 `D:\06_3D_모델링`에서 정리 구조가 분명한 모델링 파일을 옮겨 온 아카이브입니다.

## Included Roots

| Folder | Source meaning |
| --- | --- |
| `source-cad/SLDPRT` | SolidWorks/CATIA 중심 원본 모델링 폴더 |
| `stl-exports/stl` | 프로젝트별 STL export 폴더 |
| `assemblies/assemble` | assembly 중심으로 정리해 둔 SolidWorks assembly 폴더 |

## Assembly Organization

GitHub에서는 `.SLDASM`과 `.CATProduct`를 바로 미리보기로 열 수 없기 때문에, 조립 파일은 `assemblies/assemble/`에 따로 모으고 사람이 찾아보기 쉬운 index를 붙였습니다. 원본 CAD 폴더는 부품 참조 관계를 보존하기 위해 그대로 두고, GitHub 정리용 복사본만 assembly archive에 모았습니다.

대표 조립체는 eDrawings에서 직접 캡처한 이미지도 함께 정리했습니다. 파일만 있는 아카이브가 아니라, 조립 상태와 전체 형상을 빠르게 확인할 수 있는 공개 포트폴리오용 기록으로 보강한 것입니다.

STL export 기반 이미지는 단일 부품의 형태를 빠르게 보여줄 때는 쓸 수 있지만, assembly의 설계 의도와 부품 관계를 보여주기에는 부족했습니다. assembly preview 쪽은 eDrawings 캡처를 기준 이미지로 사용합니다.

## Excluded Roots

| Folder or pattern | Reason |
| --- | --- |
| `download_file` | 외부 다운로드/참고 모델이 섞여 있어 직접 제작 아카이브에서 제외 |
| `g-code` | 프린터별 출력 명령 파일이라 모델링 원본으로 보지 않음 |
| broad lab print-download folders | 출력 연습용 외부 모델과 직접 제작물이 섞여 있어 제외 |
| clearly external model names | 예: Thingiverse/게임 모델처럼 직접 제작 맥락이 아닌 파일 |

## File Manifest

- [model-file-manifest.md](model-file-manifest.md) lists the included files by relative path, extension, and size.
- [project index](../projects/README.md) gives the human-readable grouping by project and learning theme.
- [assembly index](assemblies/README.md) lists the curated assembly entry files.
- [assembly previews](../images/assembly-previews/README.md) shows eDrawings capture sets and representative assembly views.

## Note

일부 assembly 폴더에는 실제 조립 간섭 확인을 위해 사용한 보드/센서/모터 reference component가 포함될 수 있습니다. 이 파일들은 전체 설계 맥락을 보존하기 위해 남겨 두지만, 모든 reference component를 직접 설계한 제품으로 주장하지 않습니다.

`.SLDASM` 파일은 GitHub에서 바로 렌더링되지 않습니다. 그래서 assembly 파일 목록은 [assembly index](assemblies/README.md)에 정리하고, eDrawings에서 직접 캡처한 화면은 [assembly preview images](../images/assembly-previews/README.md)로 따로 보강했습니다.
