使用前需自行获取相应的api key填入 .env中喔。

感谢大家的支持和喜爱。

有任何问题欢迎联系我。

由衷感谢@肉冻の云雀舌的热心指导！大家启动成功了给@肉冻の云雀舌和up主@荒野Agent开发点点关注！双击！！！
我将指导后总结的启动步骤写在下面：
1、弄一个虚拟环境，要满足up的python3.13.3要求
2、弄好.env中需要的那些api
2、自己安装好Nodejs（前端需要），安装好MySQL（数据库需要）
3、以管理员身份打开pycharm，选择自己前面创建的虚拟环境，打开终端，安装好项目依赖，完了再运行一下以下命令：pip install --upgrade "langgraph-cli 【inmem】"，输入langgraph dev即可打开后端
4、再开一个终端，cd到前端的那个文件夹，在此处安装pnpm，完了运行一下以下命令：pnpm install，输入pnpm dev即可打卡前端。如果前端中聊天有问题，就是前端文件夹中的.env文件没弄好，这里的名字要看langgraph.json中写的名字（例如LangGraph_Agent-main项目中的名字为data_agent）
