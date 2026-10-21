# 모멘텀 작업실 · GitHub Pages 화면

이 저장소는 /hq/ 경로용으로 빌드한 공개 프런트엔드만 포함합니다.
GitHub Pages는 Node 서버, SQLite 저장소, CLI 워커를 실행하지 않습니다.
실제 작업과 개인 데이터는 별도로 연결한 인증 서버와 로컬 CLI 워커가 처리합니다.
서버에 연결하기 전에는 실제 작업 실행 완료로 표시하지 않습니다.

백엔드 소스, 비밀 설정, 사용자 기록, 조사 자료는 이 패키지에 포함하지 않습니다.
build-manifest.json은 게시한 빌드 파일의 크기와 SHA-256을 기록합니다.
원본 Git 저장소와 깨끗한 빌드 입력을 확인한 경우에만 sourceCommit을 기록합니다.
실제 GitHub Pages 게시 커밋은 배포 저장소의 Git 기록에서 확인합니다.
오픈소스 고지는 THIRD_PARTY_NOTICES.md를 확인하세요.
