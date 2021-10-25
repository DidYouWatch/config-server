# config-server

개발 환경에서는 프로젝트 내의 /config-repo 디렉터리를 '로컬 파일(native)' 방식의 config-repository로서 활용합니다.


운영 환경에서는 /config-repo의 내용들을 기반으로 kubernetes config-map을 생성해, config-server의 volume에 부착합니다.
