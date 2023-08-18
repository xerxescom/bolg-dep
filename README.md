# bolg-dep
这是一个Fastapi的启动示例



### linux系统专用

```shell
gunicorn main:app -b 0.0.0.0:8088 -w 4 -k uvicorn.workers.UvicornWorker
```

> -w:指定fork的worker进程数
>
> -D 守护启动
>
> -c 配置文件
>
> -k 工作进程类型



### windows系统（使用uvicorn启动）

python main.py





###  安装python依赖

pip install -r requirements.txt
