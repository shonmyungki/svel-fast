front - svelte

frontend/.env

에서 백엔드 주소 명시가능.

현재 192.168.254.10:8000 으로 되어있음

node:20에서 빌드후 생성된 dist폴더의 정적파일을

nginx 컨테이너로 옮기도록 구성됨.

백엔드 - fastapi

DB사용자=user

DB암호=1234

DB이름=db

DB주소=192.168.254.10

DB포트=3306

database.py 에서 주소 수정가능

