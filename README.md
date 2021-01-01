## - 가상환경 설정 MacOS
click here 
* [플라스크 질문게시판](https://pybo.kr/pybo/question/detail/368/)
* [플라스크 게시판](https://pybo.kr/pybo/question/list/qna/)
* [점프 투 플라스크 위키독스](https://wikidocs.net/book/4542)
* [git hub jump2flask](https://github.com/pahkey/flaskbook)


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