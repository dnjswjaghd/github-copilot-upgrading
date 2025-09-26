# upgraded 폴더 구조 설명

이 디렉터리는 레거시(legacy) 프로젝트의 모든 파일과 폴더를 복사하여 최신 Python 환경에서 업그레이드 작업을 진행하기 위한 공간입니다.

## 주요 파일 및 폴더

- MANIFEST.in, README.rst, distribute_setup.py, setup.py, distribute-0.6.10.tar.gz: 프로젝트 메타 정보 및 설치 관련 파일
- guachi/: 주요 Python 모듈 및 서브모듈, tests/ 폴더에 테스트 코드 포함
- guachi.egg-info/: 패키징 정보 및 의존성 관련 파일
- docs/: Sphinx 기반 문서화 폴더
    - build/: 빌드 결과물 (doctrees, html)
    - source/: 문서 원본 및 설정 파일, _static/에 CSS 등 포함

## 활용 목적
- 레거시 코드를 최신 Python 문법 및 패키징 방식으로 변환
- 테스트 코드와 문서까지 포함하여 전체 프로젝트를 현대화
- 업그레이드 과정에서 각 파일의 역할과 변경 내역을 추적 가능

이 폴더에서 모든 업그레이드 작업을 진행하며, 원본 레거시 코드는 legacy 폴더에 보존됩니다.
