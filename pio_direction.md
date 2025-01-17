# 파이썬 가상환경 동기화
uv sync (platformio 및 다른 파이썬 패키지 설치)

uv 아니더라도 pyproject.toml을 통해 동기화 가능

# pio 패키지 동기화 및 리셋
pio pkg install (platformio에 적혀있는 패키지 및 보드매니저 설치)

pio pkg uninstall (반대로 삭제)

# 현재 폴더를 하나의 프로젝트로 인식
pio project init

# 라이브러리 및 패키지 검색 및 설치
pio home

설치하면 라이브러리는 `project`/.pio/libdeps/`boardmanager`/ 경로로 저장하고 `project`/에 예제도 저장(예제는 삭제해도 될 듯?)

근데 라이브러리는 ./pio 안에 있는데 보드매니저는 안보임 어디에 추가되는 건지 잘 모르겠음
