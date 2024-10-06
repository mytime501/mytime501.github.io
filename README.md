승준의 포트폴리오 웹사이트

이 저장소는 Hugo를 사용하여 제작한 개인 포트폴리오 웹사이트의 코드를 포함하고 있습니다. Hugo는 빠르고 유연한 정적 사이트 생성기입니다.

프로젝트 개요

프레임워크: Hugo

목적: 나의 기술, 프로젝트 및 경험을 소개하는 포트폴리오 사이트

주요 기능:

프로젝트, 경험, 연락처 정보를 별도의 섹션으로 구성

이미지 및 커스텀 CSS/JS 파일을 assets 및 static 폴더에 관리

layouts/partials/views에 있는 부분 레이아웃을 통해 모듈화된 테마 커스터마이징

content 폴더 내의 파일로 콘텐츠를 쉽게 편집 가능



파일 구조

.github: GitHub 관련 설정 파일

assets: 사이트 에셋 (이미지, 스타일시트, 스크립트 등)을 저장하는 폴더

config/_default: 사이트 구조 및 설정을 위한 Hugo 설정 파일

content: 웹사이트의 콘텐츠 (블로그 포스트, 프로젝트 설명 등)

data: 동적 콘텐츠에 사용되는 추가 데이터 파일

layouts/partials/views: 페이지 디자인을 커스터마이징하는 레이아웃 템플릿 및 부분 파일

static/uploads: 정적 파일 (이미지 또는 다운로드 가능한 콘텐츠)

.editorconfig: 다양한 에디터에서 일관된 코드 스타일을 유지하기 위한 설정

.gitignore: Git에서 무시할 파일 목록

README.md: 저장소에 대한 설명서 (이 파일입니다)


설치 방법

로컬에서 사이트를 실행하려면:

1. 이 저장소를 클론합니다:

git clone https://github.com/mytime501/portfolio.git


2. 저장소 디렉토리로 이동합니다:

cd portfolio


3. Hugo가 설치되어 있지 않다면 설치합니다:

brew install hugo


4. 웹사이트를 로컬에서 실행합니다:

hugo server


5. 브라우저에서 http://localhost:1313/로 이동하여 사이트를 확인합니다.



배포

이 웹사이트는 GitHub Pages, Netlify 또는 기타 정적 호스팅 서비스에 배포할 수 있습니다. 배포 단계는 해당 플랫폼의 문서를 참조하세요.

기여

개선 사항 제안이나 버그 신고는 자유롭게 이슈를 열거나 Pull Request를 제출해 주세요. 기여는 언제나 환영입니다!

라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.
