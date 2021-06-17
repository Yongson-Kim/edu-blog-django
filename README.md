# 파이썬 사용자를 위한 웹개발 입문 A to Z Django + Bootstrap

인프런, Python, Djnago, Bootstrap, Blog

## 기존 소스를 받을 경우

가상환경 생성 (프로젝트 루트에서 실행)  
local dev venv -> `venv`

```bash
$ python3 -m venv devenv
$ source ./venv/bin/activate
```

package 복원 (가상환경에서 실행)

```bash
(venv) $ pip install -r requirements.txt
```

데이터베이스 초기화 (django project 폴더에서)

```bash
(venv) $ cd pragmatic
(venv) pragmatic $ python3 manage.py makemigrations
(venv) pragmatic $ python3 manage.py migrate
```

## 새로운 모듈을 설치한 경우

package 목록 저장 (가상환경/프로젝트 루트에서 실행)

```bash
(venv) $ pip freeze > requirements.txt
```
