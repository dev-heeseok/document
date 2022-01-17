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

## LFS 사용하기

Git 에서는 대용량 파일을 관리하기 위해 LFS(Large File Storage)를 지원하고 있다. Github 의 경우 50mb 는 warning, 100mb 는 error 가 발생하는데, Git LFS 를 사용하면 아주 큰 파일에 대해서도 Git push/pull 이 가능해진다.

```sh
# git lfs 초기화
git lfs install

# lfs tracking
git lfs track '$TRACK_PATTERN' # ex) git lfs track '*.zip'

# lfs tracking file 
git lfs ls-files
# echo > b21715d2a2 * Python/파이썬을 이용한 자동화 스크립트/과제/과제 3번.docx
```
