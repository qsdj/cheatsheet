# 基础知识
涉及sed，awk，curl，wget等基础命令。

## 工具推荐表
| 工具名称      | 描述 |
| ----------- | ------------------    |
| [jq](jq.md)          | 最好用的json文件处理工具  |
| [tcpdump](tcpdump.md) | 最基础的网络抓包分析工具 |
 

# 任务场景
* 根据进程名称列出PID
```bash
pgrep <pro>
```
或者
```bash
ps aux | grep <pro>
```

* 如何获取运行程序的目录？
```bash
pwdx <PID>
```
或者
```bash
ls -l /proc/<PID>/cwd
```

* 添加用户
```bash

```


# 常见问题