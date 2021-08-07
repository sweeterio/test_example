# 使用说明

本项目为 Sweet 体验版示例：

- 无需授权，可直接体验
- 每个测试计划最多可执行3个测试套件
- 每个测试套件最多可执行10个测试步骤
- 本期体验版本到期日为2021/12/31
- 到期后，重新发布最新体验版



## 二、快速启动

### 系统要求

1. Windows 10/Windows Server 2016
2. Python 3.9 (*必须)
3. 联网

### 1、安装 sweet.test

```
pip install sweet.test
```
> 注：体验版虽然包名为 sweet.test，实际安装包仍为 sweet

### 2、安装官方`关键字模块`

```
pip install sweet.web
pip install sweet.http
pip install sweet.mobile
pip install sweet.db
pip install sweet.file
```
> 备注：示例的测试用例有用到，请全部安装，后续可自行卸载

### 3. 启动 Web「测试报告」服务

在项目目录（test_example），用命令行执行如下命令：

```
python app.py
```

打开网页：http://127.0.0.1:80 查看测试报告


### 4. 执行自动化测试示例

在项目目录下（test_example），用命令行执行如下命令：

```
python start.py
```