在Linux上不能直接使用pip安装Cartopy，需要首先安装跟地理处理相关的依赖
```
apt-get install libgeos-dev
apt-get install libgeos++-dev
apt-get install proj-bin
apt-get install libproj-dev

pip install cartopy
```