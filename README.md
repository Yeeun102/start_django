# start_django
Django를 사용한 블로그 웹사이트

Django로 제작한 블로그 웹사이트 입니다. 게시글 작성, 수정, 삭제 기능을 포함하고 있습니다.

## 실행 방법

1. 가상환경 설정 및 패키지 설치
아래 명령어를 실행하여 가상환경을 만들고 필요한 패키지를 설치합니다.

'''bash
python -m venv venv
source venv/Scripts/activate  # Windows (Git Bash, WSL, macOS, Linux는 source venv/bin/activate)
pip install -r requirements.txt


2. 데이터베이스 마이그레이션
python manage.py migrate

3. 관리자 계정 생성
python manage.py createsuperuser

4. 서버 실행
python manage.py runserver

이후 브라우저에서 아래 주소로 접속하여 웹사이트를 확인할 수 있습니다.
http://127.0.0.1:8000/

관리자 페이지는 다음 링크에서 접속할 수 있습니다.
http://127.0.0.1:8000/admin

관리자 계정으로 로그인하여 게시글을 관리할 수 있습니다.