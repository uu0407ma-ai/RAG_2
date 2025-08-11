# RAG项目

## 环境配置

```bash
# 创建虚拟环境
python -m venv .venv

# 激活虚拟环境
source .venv/bin/activate  # Linux/Mac
# 或
# .venv\Scripts\activate  # Windows

# 更新pip
pip install --upgrade pip

# 安装依赖
pip install -r requirements.txt
```

## 运行应用

```bash
python app.py
```
访问 http://localhost:8000/static/chat.html


## 脚本说明

### 文件目录说明

- **step1 **: 基础RAG示例，会话过程采用内存模拟的方式保存。

- **step2 **: 改进版RAG，支持SQLite数据库， 支持会话持久保存。

- **stream_test **: 流式输出的简单demo




## 开发工具

### SQLite工具
推荐使用 Navicat Premium Lite（免费版）  
下载地址：https://www.navicat.com.cn/download/navicat-premium-lite



### Vue3互动教程

https://cn.vuejs.org/tutorial/#step-1

### 主界面
![Sample Image](https://raw.githubusercontent.com/uu0407ma-ai/RAG_2/master/23-project-rag-b/main.png)

### 文档上传界面(外部知识)
![Sample Image](https://raw.githubusercontent.com/uu0407ma-ai/RAG_2/master/23-project-rag-b/up_file.png)
