# 1�s�Ŋ��\�z
�T�[�o��`root`���O�C�����P�s�̃R�}���h�����s���邾����Magic3�̓�����\�z�ł���X�N���v�g�ł��B
Magic3�̃C���X�g�[�����N���ł���Ƃ���܂ł���C�ɍ\�z���܂��B

Magic3�^�p�ɕK�v�ȃ\�t�g�E�F�A�����ׂ�1��̃T�[�o�ɔ[�܂�悤�Ƀp�b�P�[�W������Ă��܂��B
���\�z�͓���A�����ւ񎞊Ԃ�������Ƃ��������������܂��B

## �Ώ�OS
- CentOS 7, Ubuntu18

# ���؊�
- Vagrant Box CentOS7�ucentos/7�v, Ubuntu18�uubuntu/bionic64�v
- ������VPS �uCentOS7�v(�W��OS), �uUbuntu18.04 amd64�v(�J�X�^��OS)

## ���C�Z���X

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

# ���s���e
���[�J����Ansible���C���X�g�[�����AAnsible Galaxy��Playbook����{�ɏ����J�X�^�}�C�Y���Ċ��\�z���Ă��܂��B
���̓��F������܂��B

- �ŐV�̃\�t�g�E�F�A��
- ���{��œK��

# �g����
�V�K��OS���C���X�g�[�������T�[�o��`root`�Ń��O�C�����A�\�z���������̃X�N���v�g�����s���܂��B
������͈�U�T�[�o���ċN�����Ă��������B

## Web�T�[�o(LEMP)���\�z (���v����: ��10��)
Linux(L),Nginx(N),MariaDB(M),PHP(P)��LEMP�����쐬���܂��B

### �o�[�W����
- Nginx 1.14.2
- PHP 7.3
- MariaDB 5.5.60(CentOS),MySQL 5.7.24(Ubuntu)

```
$ curl https://raw.githubusercontent.com/magic3org/oneliner-env/master/script/build_lemp_magic3.sh | bash
```

### ���\�z��̍��
���\�z���Magic3�̃C���X�g�[����Ƃ��I����Ă��Ȃ���Ԃł��B  
Web�u���E�U��Magic3�̃C���X�g�[�������s���C���X�g�[�������������܂��B

IP�A�h���X���Ńh�L�������g���[�g�ɃA�N�Z�X���܂��B
```
http://localhost
```

DB�ւ̐ڑ���񂪕K�v�ɂȂ�܂��B  
�f�t�H���g�ō쐬����Ă���DB�̏��͈ȉ��̒ʂ�ł��B

-DB���Ftestdb
-DB���[�U�Ftestuser
-�p�X���[�h�Ftest
