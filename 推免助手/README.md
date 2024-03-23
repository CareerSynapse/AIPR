# AIPR（推免助手）

## 概述

本项目基于Langchain和streamlit，构建了简单的[推免助手问答助手](http://49.232.147.232:8501/)平台。

## 文件结构

```
├── data/ #推免经验贴材料
├── docs/ #向量数据库存放路径
│   ├── chroma/ # 向量数据库
│   │   ├── chroma.sqlite3
│   │   └── ...
├── flagged
├── Chatbot.py # 基于streamlit搭建的推免助手小T
├── Demo.ipynb # 基于Langchain搭建的推免助手小T&入门教程
└── requirements.txt #环境配置
```

## 需求

### 环境配置

要运行我们的代码，请使用以下命令配置环境并安装所有依赖包：

```
conda create -n baoyan python=3.10
conda activate baoyan
pip install -r requirements.txt
```

**注意**: 如果未安装conda环境，也可通过virtualenv创建环境并安装所有依赖包

```bash
virtualenv baoyan #创建一个新的Python环境，这里我们把环境命名为baoyan
source baoyan/bin/activate #激活这个刚刚创建的Python环境
pip install -r requirements.txt #使用pip来安装需要的Python包
```

### API获取

[百度千帆](https://console.bce.baidu.com/qianfan/ais/console/applicationConsole/application)

[GLM4](https://maas.aminer.cn/usercenter/apikeys)

[OpenAI](https://platform.openai.com/docs/introduction)
