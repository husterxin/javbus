# javbus
### javbus论坛每日签到 <br>
根据https://github.com/leeairw/Enshan 项目修改而来


### 使用方法<br> 
Github Actions版本<br>
1.点击项目右上角的Fork，Fork此项目<br>
2.到自己Fork的项目点击Setting→Secrets→New secrets<br>
3.Name填写cookie_javbus，Value填写 获取到的cookie<br>
4.在"Actions"中的"run"下点击"Run workflow"即可手动执行签到，后续运行按照schedule，默认在每天凌晨0:30自动签到，可自行修改<br>
### 地址:https://www.javbus.com/forum/home.php?mod=spacecp&ac=credit (用来登录获取cookie)
#### 以EDGE浏览器为例：
确保在登录状态下打开上述链接，右键点击网页空白页，在菜单中选择最底部的检查并单击进入，点击源代码右边的"》"，然后点击网络，接着刷新一下当前网页，点击名称栏第一个home.php开头的，在右边翻一下就能看见cookie。

### 如需使用免翻墙网址，请自行在javbus.py中查找javbus.com（总共三处）并替换为免翻墙网址
