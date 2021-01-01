## - 가상환경 설정 MacOS

```
python3 -m venv .mypro
source ./mypro/bin/activate

```

## - 기본앱 설정

1장 3단계

set FLASK_APP=pybo  <<< 윈도우 버전

대신에 맥은 

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