### 가상환경 실행 경로
cd ~/venvs/mysite/bin
. activate

### 중복 실행을 방지하기 위해 killall
cd /home/ubuntu/venvs/ killall python

### 장고 서버 기본실행
python manage.py runserver 0:8000

### 장고 prod 파일로 서버 실행
python manage.py runserver 0:8000 --settings=config.settings.prod

### 가상환경 자동화 파일 생성 (nano 에디터 통해 생성)
cd venvs
. mysite.sh

### AWS
### AWS lightsail
### MobaXterm
### Gunicorn
### Ngnix

### 다시시작!