# mySoccerApp

- powershell열고
  `(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python`

- cmd열고 `poetry --version`으로 설치된 것 확인하면 `poetry init`

  ```
  no
  Lisence -> MIT
  no
  no
  yes
  ```

- `pyproject.toml`생성된 것 확인되면 `poetry add django`로 django설치

- `django-admin startproject config .`으로 환경 만들어주고 `python manage.py runserver`를 입력하면 서버가 켜진다.

- extension에서 `sqlite viewer설치하면 db볼 수 있어서 좋음`
