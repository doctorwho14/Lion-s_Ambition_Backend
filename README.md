# Lion-s_Ambition_Backend

교내 해커톤 5팀 백엔드

## 개발환경 설정

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

Python 의존성 설치

```shell
pip install -r ambition/requirements.txt
```

Front End 팀의 작업물 불러오기. ([GitHub 링크](https://github.com/SMU-LIKELION-11TH/Lion-s_Ambition_Frontend))

```shell
git submodule update --remote --init
```

secrets.json 파일 생성하기

```shell
# Linux, MacOS
cp ambition/secrets.template.json ambition/secrets.json

# Windows
Copy ambition/secrets.template.json ambition/secrets.json
```

> secrets.json 파일에 적절한 세팅 값들을 사용한다.

서버 구동하기

```shell
cd ambition/
python manage.py runserver
```
