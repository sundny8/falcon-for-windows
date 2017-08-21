# falcon-for-windows
monitor on windows platform
基于open—falcon构建windows平台的监控客户端程序。
## 依赖
python >= 2.6<br>
[psutil](https://pypi.python.org/pypi/psutil)<br>
[requests](https://pypi.python.org/pypi/requests)<br>

## 部署方法
*根据实际部署情况，修改脚本开头的配置参数。<br>
*修改 graph 的 mysql 编码为utf8，以支持中文的。由于 windows 的网卡有可能存在中文，所以这一步很重要！<br>
*测试：python Agent4windows.py<br>
*放入windows计划任务完事<br>
