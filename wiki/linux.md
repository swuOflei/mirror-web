Linux Kernel Git 镜像使用帮助
=============================

如需克隆 linux 代码，使用
```
git clone git://mirrors.tuna.tsinghua.edu.cn/linux.git
```

若要将 tuna mirror 加入已有代码库，可在已有仓库中运行
```
git remote add tuna git://mirrors.tuna.tsinghua.edu.cn/linux.git
```

或运行
```
git remote set-url origin git://mirrors.tuna.tsinghua.edu.cn/linux.git
```
将默认上游设置为 TUNA 镜像

