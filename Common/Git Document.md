# Git Document

Git 을 사용하면서 필요한 문법과 이론을 기록하기 위한 문서이다. 주로 예제 코드를 이용하여 기록할 예정이며 Command line 의 경우 window powershell 을 사용할 예정이다.

## config 확인하기

```sh
# version 확인하기
git --version

# user.name 확인하기
git config user.name 
# echo > dev.heeseok

# user.email 확인하기
git config user.email
# echo > dev.heeseok@gmail.com
```

## config 수정하기

```sh
# user.name 수정하기
git config --global user.name dev.heeseok

# user.email 수정하기
git config --global user.email dev.heeseok@gmail.com
```
