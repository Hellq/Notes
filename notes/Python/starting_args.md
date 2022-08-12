# 获取启动参数
```python
import os
print(os.argv)
```
`os.argv`储存了脚本的启动参数（实际上是python.exe的启动参数），`argv[0]`是脚本名称（路径），后续是脚本的参数