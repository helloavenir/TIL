# 2022년 6월 29일

## 오늘 수업의 학습목표

- git을 사용하기 위해 CLI(Command Line Interface) Shell command와 Vim editor를 다룰 수 있다.
- 코드 관리를 위한 git의 사용법을 정확히 이해한다.
- git의 저장소 개념을 이해하고, 원격 저장소 서비스의 차이를 인식한다.
- git을 사용하면서 발생하는 다양한 상황을 해결할 수 있다.
- commit의 보편적인 작성법을 이해하고 이를 활용하여 commit을 작성할 수 있다.


## 수업을 통해 배운 내용

> Shell Command
```shell
$ cd {directory name}         // change directory
$ mkdir {directory name}      // make directory
$ cd ..                       // 상위 디렉터리로 이동
$ pwd                         // print working directory 현재 위치 확인
$ touch {file name}           // make file 파일 생성
$ mv {file name} {옮길 장소}  // move 이동
$ cp {file name} {복사 장소}  // copy file
$ cp {file name} {file name}  // file을 다른 이름으로 바꾸어 복사
$ mv {file name} ./{file name}// 이름바꾸기(Rename)
$ rm {file name}              // remove file 
$ rm -rf {directory name}     // 내부 파일 다 삭제 후 디렉토리 삭제(rf; recursive, force)
$ cat {file name}             // catenate file 텍스트라인을 취합해 쉘에 출력
$ ls                          // list segments 지정한 파일, 디렉토리의 정보를 리스트 형태로 
```



> Vim Command mode
```shell
:q    //quit 종료
:wq   // write and quit 저장후 종료
```




> git Process Flow and Command(순방향만 우선 배움)
  
  Local - git,    Remote - gitHub(클라우드 저장소)

  
  working directory에서 stage로 올려줄 때 : "git add"   ... ex) git add hello.md
  
  stage에서 localrepo로 저장할 때 : "git commit"

  localrepo에서 remoterepo로올려줄 때 : "git push"  ... ex) git push -u origin main (첫번째 푸쉬)  
                                                           git push origin main (두번째 푸쉬부터)
  
  gitHub에서 repo 생성한 후, repo 주소를 갖고와서 git에 복제해줄 때 : "git clone"  ... ex) git clone https://주소 




> Conventional Commits
  
  1. commit 제목은 commit을 설명하는 하나의 구나 절로 작성
  2. 영어로 작성시 Capitalizing
  3. prefix(소문자로) 꼭 달기
    - feat : 기능 개발 관련 내용
    - fix : 오류 개선 혹은 버그 패치
    - docs : 문서화 작업
    - test : test 관련
    - conf : 환경설정 관련
    - build : 빌드 관련
    - ci : Continuous Integration 관련
  



## 오늘의 생각

- 배운 내용을 다시 한번 key-in하며 Vim 작업환경과 command에 익숙해져보자.
- 기존에 있던 깃헙의 repo를 다시 보고 정리를 시작해보자.
- 깃헙 기술 블로그 작성을 당분간 Vim으로 매일 작성해보자.
- 온라인 강의로 오늘 배운 내용과 관련된 부분 시청하며 복습하자. 



