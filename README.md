# WeChatPush
微信消息推送到消息接收或FarPush或WirePusher    

基于FarPash大佬修改的itchat以及唐大土土大佬的消息接收   
FarPash大佬的项目https://github.com/TSIOJeft/WeChatPush    
唐大土土大佬的软件https://www.coolapk.com/apk/top.tdtt.news    

感谢酷安的大佬 大鸟转转转酒吧（chase535） Away`LL （ll2594） 园花后的编小安酷（GentsunCheng） 三位的贡献。    
一共有三种接收方式。      
     
运行前先执行命令 pip3 install -r requirements.txt 安装库文件

程序配置文件config.py，首次配置完成后方可运行main.py。若程序正在后台运行，则更改配置后实时生效
  
服务器运行的话可以先python3 main.py登陆一下      
然后用   nohup python3 -u main.py > test.log 2>&1 &    命令后台运行      
