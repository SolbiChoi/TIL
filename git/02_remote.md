# 원격 저장소(remote repository) 기초

## 기본 설정

* 로컬 git 저장소
* Github에 remote repository를 생성

## 명령어

### 원격 저장소 설정

```bash
$ git remote add origin add 저장소URL
```

* 깃, 원격저장소(remote) 추가해줘(add) origin 이라는 이름으로 저장소 URL을
  * origin은 원격저장소 이름!

### 원격 저장소 목록 보기

```bash
$ git remote -v
```

## 원격 저장소 설정 삭제하기

```bash
$ git remote rm origin
```

* 깃아,원격저장소(remote) 삭제해줘(rm:remove) origin을

### push

```bash
$ git push origin master
```

* 깃아, 푸쉬해줘 origin 원격저장소에 mater 브랜치!