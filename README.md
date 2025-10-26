# 星弦科幻协会资料汇总网站

> Warning 正在建设中

## 本地搭建

* 安装包管理工具

```shell
# 安装 Python3 核心包
$ sudo apt install python3 -y
# 安装 pip3（Python 包管理器）
$ sudo apt install python3-pip -y
# 安装 Python 编译依赖（避免后续安装插件报错）
# sudo apt install python3-dev build-essential -y
$ python3 --version  # 显示版本号即成功（需 ≥3.8）
$ pip3 --version     # 验证 pip3 可用
```


* 安装依赖

```shell
pip install -r requirements.txt
```

* 开启本地预览服务

```shell
$ mkdocs serve # Serving on http://127.0.0.1:8000/
```