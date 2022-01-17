# Git Document

Git �� ����ϸ鼭 �ʿ��� ������ �̷��� ����ϱ� ���� �����̴�. �ַ� ���� �ڵ带 �̿��Ͽ� ����� �����̸� Command line �� ��� window powershell �� ����� �����̴�.

## config Ȯ���ϱ�

```sh
# version Ȯ���ϱ�
git --version

# user.name Ȯ���ϱ�
git config user.name 
# echo > dev.heeseok

# user.email Ȯ���ϱ�
git config user.email
# echo > dev.heeseok@gmail.com
```

## config �����ϱ�

```sh
# user.name �����ϱ�
git config --global user.name dev.heeseok

# user.email �����ϱ�
git config --global user.email dev.heeseok@gmail.com
```

## LFS ����ϱ�

Git ������ ��뷮 ������ �����ϱ� ���� LFS(Large File Storage)�� �����ϰ� �ִ�. Github �� ��� 50mb �� warning, 100mb �� error �� �߻��ϴµ�, Git LFS �� ����ϸ� ���� ū ���Ͽ� ���ؼ��� Git push/pull �� ����������.

```sh
# git lfs �ʱ�ȭ
git lfs install

# lfs tracking
git lfs track '$TRACK_PATTERN' # ex) git lfs track '*.zip'

# lfs tracking file 
git lfs ls-files
# echo > b21715d2a2 * Python/���̽��� �̿��� �ڵ�ȭ ��ũ��Ʈ/����/���� 3��.docx
```
