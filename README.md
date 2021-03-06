# StudyNote
初学 Flask 作品，存档备份。  
轻量级笔记 Web APP，移动端支持。目前自己也在使用，用于学习英语以及其他一部分文化课。  

## 简介
一个简单的记事本 Web 应用，练手项目，现在滋磁 Markdown。

## 运行环境
1. Python 3.6.2
2. Flask 1.10.1
3. Python Markdown 模块

## 前端框架
1. Bootstrap
2. jQuery

## 发布版本
*Ver 0.0.1* 最早版本，仅仅有使用 Markdown 发布笔记功能  
*Ver 0.0.2* 使用 SQLite 存储笔记  
*Ver 0.0.3* 支持修改以及删除笔记，优化性能  
*Ver 0.0.4* **优·化·性·能**，在自己家里服务器跑了一会儿，发现有时候`get`和`post`很慢，就再优化了一下

## 预计加入功能
- 笔记文件夹
- 笔记分类，Tag，以及搜索笔记（名字，或者 Tag）
- 表格形式整理笔记
- 用户，每个用户有单独的笔记，可以类似于 Git 的 fork 功能
- 保存至 PDF（打算使用一个现有的 HTML to PDF API，不过在国内性能可能不是很好）

## 使用方法
首先，确保你有 Python 解释器、Python 的包管理工具 pip 以及 Git。
然后在命令行输入下面的命令：
```
  git clone https://www.github.com/irook/StudyNote
  cd StudyNote
  pip install flask
  pip install markdown
  python StudyNote.py
```
**如果你的系统有 Python 3 以下版本的解释器，将`python StudyNote.py`更换为`python3 StudyNote.py`。**
然后在浏览器地址栏输入：
```
  localhost:3000
```
即可访问网站。  
如果需要变更端口，更改`StudyNote.py`第144行的 port=?，?为你要的端口号;)
