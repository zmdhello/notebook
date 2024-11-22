windows系统直接去官网安装ollama框架
打开powershell命令行
ollama run qwen
ollama run llama3.1
等等ollama支持的大模型，几个G，
可以看到，系统正在下载qwen的模型（并保存在C盘，C:\Users<username>.ollama\models 如果想更改默认路径，可以通过设置OLLAMA_MODELS进行修改，然后重启终端，重启ollama服务。）

setx OLLAMA_MODELS "D:\ollama_model"

先在浏览器输入：http://127.0.0.1:11434

确保ollama在运行中。

再浏览器输入：http://127.0.0.1:11432
终端运行ollama ls

可以看到目前你下载的所有模型
