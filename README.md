# bolg-dep

linux系统专用

gunicorn main:app -b 0.0.0.0:8088 -w 4 -k uvicorn.workers.UvicornWorker

-w:指定fork的worker进程数 -D 守护启动 -c 配置文件 -k 工作进程类型

windows系统

直接启动main.py

###  安装python依赖
pip install -r requirements.txt
