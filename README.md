## 环境

> Python 环境： 3.5

1. 系统依赖软件

        sudo apt-get install python-matplotlib ipython ipython-notebook

        sudo apt-get install python-pandas python-sympy python-nose

2. python机器学习库

        直接 pip install -r requirement.txt  即可

## 运行

        python3 waf.py

## 说明

可以先训练模型把模型实例序列化到文本中，下次直接读入文本的实例，避免每次执行程序都要再训练一次（确实比较慢）。