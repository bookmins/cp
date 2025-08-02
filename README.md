ModuleNotFoundError: No module named 'plotnine'
	包未安装 / 包名错误	重新 pip install，注意大小写与拼写

3	忘了 import	在代码顶部添加 import plotnine
4	缺少 __init__.py	确保自定义包目录下含有 __init__.py
5	版本不兼容	指定包版本：pip install 'plotnine==0.8.0'
6	包名冲突	重命名自定义模块，避免与官方包同名
7	PYTHONPATH 未设置	在环境变量中添加项目路径
8	相对导入使用不当	使用绝对导入或正确的相对路径
9	pip 版本过低	pip install --upgrade pip
10	虚拟环境解释器不一致（PyCharm）	在 PyCharm Settings 中重新指定 Interpreter
11	系统权限问题	使用 sudo（macOS/Linux）或管理员权限
12	其他可能性	查看 C 语言扩展依赖、Mac M1/M2 架构兼容问题等
