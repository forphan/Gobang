## 简易的在线五子棋
---
最初使用C语言写了一个本地的两人游戏，然后移植到了Java，使用C/S模式,默认地址"localhost"，端口"7777"。


|命令|解释|
|---|---|
|help|打印帮助信息|
|list|列出当前在线用户|
|match n|和用户编号为n的账号匹配|
|accept|接受匹配|
|reject|拒绝匹配|
|adhere r c|在棋盘(r,c)落子|
|quit|退出游戏|

以后有空添加一个UI，移植到Android，现在只能命令行交互，请尽量按照规则输入命令，项目的鲁棒性不太好。