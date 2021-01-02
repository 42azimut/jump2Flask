
click here 
* [플라스크 질문게시판](https://pybo.kr/pybo/question/detail/368/)
* [플라스크 게시판](https://pybo.kr/pybo/question/list/qna/)
* [점프 투 플라스크 위키독스](https://wikidocs.net/book/4542)
* [git hub jump2flask](https://github.com/pahkey/flaskbook)

## 파이썬 Requirement.txt 생성 
- 파이썬 프로젝트에서 사용되고 있는 패키지들의 의존성 확보를 위해 requirement.txt 를 활용하는데, 해당 파일을 자동 생성하는 명령어는 다음과 같다.

>>`pip3 freeze > requirement.txt`

- 파이썬 라이브러리들의 버전 관리를 위하여 requirement.txt 라는 파일로 라이브러리를 설치한다. requirement.txt에는 각종 라이브러리 리스트와 라이브러리들의 버전 정보가 기재 되어있다.

이 라이브러리를 설치하는 방법은

>> `pip3 install -r requirement.txt`

## - 가상환경 설정 MacOS
```
python3 -m venv .proj
source ./proj/bin/activate

```

## - 기본앱 설정

### flask 는 기본앱으로 app.py 가 기본 셋이다. 

flask run 실행시 app.py가 자동 실행된다. 

만약 다른 네이밍을 기본으로 하려면 아래와 같이 환경변수를 설정한다!

1장 3단계 
* 윈도우 버전

set FLASK_APP=pybo  <<< 윈도우 버전:: 여기서 애먹었다! 난 맥인데.. 맥이네...

* 대신에 맥os는 

export FLASK_APP=pybo

```
export FLASK_APP=pybo
export FLASK_ENV=development
```


## - 쉘스크립트
```
#!/bin/bash

cd /Users/..경로../myproject
export FLASK_APP=pybo
export FLASK_ENV=development

source /Users/...경로.../venv/myproject/bin/activate
    
```
