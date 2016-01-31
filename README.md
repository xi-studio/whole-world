集成数据服务
===========

如何准备环境
-----------

准备软件包

```bash
sudo apt-get -y install build-essential git curl apache2-utils util-linux zlib1g-dev
sudo apt-get -y install python-setuptools python-dev libffi-dev
sudo apt-get -y install gfortran libopenblas-dev liblapack-dev
sudo apt-get -y install libjpeg8-dev libpng12-dev libtiff5-dev libfreetype6-dev liblcms2-dev libwebp-dev
sudo apt-get -y install tcl8.5-dev tk8.5-dev python-tk
sudo easy_install pip
sudo pip install virtualenv
```

第一次安装 Python 包

```bash
. hello
deactivate
```


如何启动API服务
--------------

```bash
. hello
bin/start game
```

如何启动数据更新脚本
------------------

```bash
. hello
bin/update game
```


