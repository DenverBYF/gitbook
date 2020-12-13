---
description: 描述
---

# 命令行操作手册

## 写在前面

*  如果你想用命令行操作，首先得确保已经有一个创建好的工作空间，工作空间中和一个项目。工作空间和项目的创建可以通过DFSV工具界面创建，也可以手动创建。通过DFSV工具界面创建的方式请参考界面操作手册，下面是一个手动创建工作空间和项目的例子。

  可将一下脚本复制到命令行，理论上可以在任意位置创建工作空间和项目。

![883250@1590316569@2.png](https://i.loli.net/2020/12/13/FuVoU6L18aA4NiB.png)

```text
#创建工作空间，名字可以是任意的字符串
mkdir workspace
cd workspace/
#创建文件夹path
mkdir path
cd path/
#在path文件下创建6个.txt文件
touch depth.txt
touch project.txt
touch pycparser.txt
touch SecretOrIntegrity.txt
touch synthesisChoiceSet.txt
touch time.txt
cd ..
#创建项目,项目名称可以是任意字符串
mkdir hhhh
cd hhhh/
#项目中有必要的文件夹，下面创建这些文件夹
mkdir meta_data
mkdir pilot_src
mkdir result
cd meta_data/
mkdir com_veri
mkdir Soure_copy
mkdir temp
cd com_veri/
mkdir sec_cert
cd ..
cd ..
cd pilot_src/
mkdir Source
cd ..

```

