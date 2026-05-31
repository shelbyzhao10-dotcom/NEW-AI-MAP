# 第一课
了解了有关python的一些基本函数，同时让llm接入了python。
## 接入本地大模型（Deep Seek)
### [打开大模型接入脚本](file:///D:/AI%20Map/DS大模型接入.py)
1. **环境准备**
在python环境里面安装openai的API库直接输入代码：pip install openai

2. **本地文件执行说明
- **脚本路径**：`D:\AI Map\DS大模型接入.py`（自己文件的路径）
    
- **执行方式**：在终端进入该文件夹后，使用命令 `python "DS大模型接入.py"` 即可运行。
    
- **调用技巧**：如果在 Jupyter 或其他脚本中复用该逻辑，直接使用 `from DS大模型接入（自己的文件名称） import get_llm_response` 即可调用其中的函数。

3.  **如何验证接入成功？**
 1.打开终端（CMD 或 PowerShell）。
 2.输入 `python` 进入交互模式。
 3.输入 `from DS大模型接入 import get_llm_response`。
 4.输入 `print(get_llm_response("测试连接"))`。
**如果屏幕返回了 AI 的回答，说明你的 Python 环境、API Key 以及网络连接全部配置成功。**

==**不懂得问AI**==
# 第一次作业
[📂 点击打开：我的 Python 第一次作业](file:///D:/AI%20Map/第一次作业.ipynb)