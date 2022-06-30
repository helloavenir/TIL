# 2022년 6월 30일

## 오늘 학습& 복습한 git commands




```shell
$ git remote add origin {원격저장소 주소}
```


> - git 명령어로 git과 연결되는 원격저장소를 생성(등록).
> - 이름은 origin(통상적)이고, 주소는 { } 안의 주소.




```shell
$ git push origin main
```


> git 명령어로 이름이 origin이라는 원격저장소의  main 브랜치에 업로드(push).




```shell
$ git config --global core.autocrlf input            (macOS)

$ git config --global core.autocrlf true              (Windows)
```


> git이라는 명령어로 환경설정(config, configuration)을 해주는데 옵션(--)은 전역(global)에서 사용하도록 하고,
> crlf(개행 문자, New Line) 설정을
> 운영체제에 따라 input이나 true로 설정해주면 자동으로 변환할 수 있게 등록. 
> cf. -(하이픈 1개)나 --(하이픈 2개)가 붙은 옵션은 플래그(flag)라고 한다.




```shell
$ git config --global user.name '사용자 이름(원격 저장소에 등록된 이름과 동일하게 설정하기를 권장)'

$ git config --global user.email '사용자 이메일(원격 저장소에 등록된 이메일과 동일하게 설정하기를 권장)'
```


> - 커밋(버전 생성)을 위한 정보 등록.
> - 커밋을 생성할 때마다 이 이메일 주소를 가진 사용자의 이름으로 생성되었음을 체크할 수 있는 용도로 사용됨.




```shell
$ git config --global --list
```


> 위에 내용들이 잘 설정되었는지 확인해볼 수 있음.




```shell
$ git init
```


> - 현재 프로젝트에서 변경사항 추적(버전 관리)을 시작.
> - main이라는 브랜치에서 프로젝트가 시작 됨.




```shell
$ git add index.htmll
```


> - 변경사항을 추적할/버전 관리를 시작할 특정 파일(index.html)을 지정.
> - 폴더 안에 여러 파일이 있을 때,  여러 파일중에서 어떤 파일을 버전관리할지 지정 혹은 추적하도록 지정하는 과정.
> - 모든 파일을 버전관리할거라면 add + 특정파일명이 아닌
>   add +  . (반드시 공백하나 두고 온점)으로 명령
>   staging하는 과정/ git에 업로드하는 과정을 add 명령으로 실행. 
> - add를 하고 나면 이 파일은 버전으로 만들 준비를 하고 있는 상태임.




```shell
$ git commit 

$ git commit -m '메시지'
```


> (-m 메시지와 함께; 버전 이름이나 변경내용 관련 등의 메모) 버전을 만들어 줌.




```shell
$ git push origin main
```


> - origin이라는 별칭의 원격 저장소로 mian이라는 브랜치를 밀어넣음(push), 즉 버전 내역을 전송.
> - 이 버전 내역은 원격 저장소에 잘 저장되어있기 때문에,
>   내 로컬 저장소에 문제가 생겨 사용하지 못하게 되도,
>   원격 저장소로부터 다시 가져와서 사용할 수 있다.



## 오늘의 생각
- 깃과 깃헙에 직접 실습해 볼 수 있도록 스타벅스 프로젝트를 부지런히 작성해 나가보자.
- 깃헙에 올린 파일들 내용 확인하고 보기 좋게 정리해보자. 불필요한 것은 제거
- 마크다운 문법은 틈나는대로 챙겨보고 조금씩 적용해보자.




