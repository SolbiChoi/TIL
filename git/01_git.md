# Git

> 분산 버전 관리시스템(DVCS)

## 준비 사항

* [git bash](https://gitforwindows.org/) (원도우 사용하는 경우 필요)

## 기본 문법

### 0. git 저장소 생성

```bash
$ git init
# 비어있는 git 저장소(respository) 초기화했다..
# test 폴더에 (절대경로).git 폴더에..
Initialized empty Git repository in C:/Users/User/OneDrive/바탕 화면/TIL/.git/

```

* 폴더에 `git` 저장소를 초기화하면,
  * `.git` 폴더가 생성되고
  * bash에는 `(mater)`라고 표기 된다.

* 주의사항
  * git 저장소 내에 git 저장소를 만들지 말라.
    * `git init`명령어 입력할 때, `(master)`가 보이면 절대 입력하지 말것



### 1. `add`

```bash 
$ git add {디렉토리}
$ git add .  #  현재 디렉토리 (하위 디렉토리 포함)
$ git add a.txt  # 특정 파일
$ git add myfolder/  # 특정 폴더
```

* `working directory` 상태의 파일을 `staging area` 상태로 변경 (첫번째  통 -> 두번째 통)
* 커밋을 위한 파일들을 추가하는 명령어

### 예시

```bash
$ touch a.txt  # 파일을 만든다 +> 코드 작업을 했다
$ git status
```

```bash
```

### 2. `commit`

```bash
```

* 커밋을 통해 하나의 버전으로 기록 된다.
* 커밋 메세지는 현재 변경사항들을 잘 나타낼 수 있도록 작성하자.
* 커밋은 고유한 아이디인 해시값을 가진다.
  * SHA-1 알고리즘에 의해 생성
* 커밋 목록은 `git log` 명령어를 통해 확인할 수있다.

### 3. `log`

```bash
```

### 4. ` status`

* working directory, staging area 공간의 파일 상태를 확인할 수 있다.

```bash
```

