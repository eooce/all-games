Telegram交流群: https://t.me/eooceu

# all-games
* Garry's Mod运行文件为srcds_run,上传Garry's Mod.tar.gz压缩包至根目录解压后在srcds_run文件中修改变量，保存文件类型为shell，否则无法运行，节点文件保存在Steam文件夹中的sub.txt。
  
* PocketMine-MP类型说明参考https://github.com/eooce/PocketMine-MP
  
* Bedrock启动文件文件为bedrock_server,需先将原bedrock_server游戏文件改名为LICENSE，否则无法启动游戏，再上传压缩包bedrock.tar.gz解压，在bedrock_server修改参数，保存文件类型为shell，默认节点目录在worlds中的sub.txt

* Teamspeak3-server启动文件为ts3server，上传文件前先将原ts3server游戏文件改名为LICENSE(如果已经存在LICENSE文件可以先删除，其他文件不要删)，再上传压缩包并解压得到ts3server文件，如需添加固定隧道或哪吒等，双击ts3server文件添加即可，保存时需选择shell保存(通常在保存按钮的左边)，保存后给权限777，然后即可点击start开机，节点保存在tsdns文件夹里的sub.txt。

* java类游戏下载java.tar.gz压缩包，先将原来的server.jar改名为LICENSE.jar,然后上传压缩包解压，start.sh需赋权777，在start.sh修改变量即可运行，其他不同类型的java游戏，startup里的启动文件名应和压缩包里的文件名对应，原版游戏文件应和start.sh最后面的倒数第二句游戏运行命令中的文件名对应，否则无法启动原版游戏，sub.txt节点信息默认在world文件夹内，控制台输出的base64编码过的那一段的也是节点信息

* python环境项目：https://github.com/eooce/python-xray-argo

* Go环境项目：https://github.com/eooce/Go-xray-argo

* rust.zip为rust环境使用的。

* muse-bot.zip为ts-bot环境使用的，将 /src/scripts/migrate-and-start.ts文件改为migarte-and-start.ts，将run-with-database-url.ts和start.sh文件上传进 /src/scripts/目录后赋权777，run-with-database-url.ts第4行修改订阅端口，不使用订阅功能可忽略，然后即可运行。

* 更多游戏持续更新中.......
