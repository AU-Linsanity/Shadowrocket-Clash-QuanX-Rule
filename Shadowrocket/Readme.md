# Shadowrocket小火箭 解锁网易云灰色歌曲+带脚本懒人配置
**Linsanity 懒人配置：（本配置可更新,包含常见策略组和分流规则，可去youtube广告,解锁网易云音乐灰色歌曲,常用签到定时任务、获取 Cookie 等脚本-脚本默认不开启）**

解锁网易云音乐功能设置教程:

解锁网易云音乐功能, iOS设备还需安装 CA 证书。首先复制链接到IOS设备Safari浏览器中点击：https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/UnblockNeteaseMusic/ca.crt   添加证书，随后在 设置 > 通用 > 关于本机 > 证书信任设置 下，手动开启证书即可．


**整体操作步骤:**

**1.复制配置文件链接加载小火箭懒人配置**

**2.添加解锁网易云音乐节点**

**3.将网易云节点分组到一个组中**

**4.开启代理, 打开网易云音乐的周杰伦<摩羯座>专辑验证破解是否生效**


**1.复制配置文件链接, 加载小火箭懒人配置方法,配置文件如下:**
**[\[Shadowrocket_Linsanity.conf\]](https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Shadowrocket_Linsanity.conf)          
https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Shadowrocket_Linsanity.conf**

**1).打开小火箭点击下方配置后,点击右上角'+'添加按钮,将懒人配置文件链接复制**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image1.png" width="35%">

**2).在下面对话框窗口处粘贴 复制好的链接地址,然后点击下载**

**https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Shadowrocket_Linsanity.conf** 

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image2.png" width="35%">

**3).点击生成的远程文件,然后点击使用配置,此时生成并选择了本地文件Shadowrocket_Linsanity.conf,记住此后不要更改选择其他配置,否则解锁网易云会失效**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image3.png" width="32%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image4.png" width="32%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image5.png" width="32%">

**2.添加解锁网易云音乐节点的方法:**

**1).点击小火箭首页左上角的扫描按钮,对以下6个二维码进行扫描生成节点**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image6.png" width="35%">

**节点1: 订阅类型**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image7.png" width="15%">

**节点2:**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/节点2.jpg" width="15%">


**2).添加节点后,首页显示5个单独的节点和一个新增的订阅**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image13.jpg" width="35%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image14.jpg" width="35%">

**3.将网易云节点分组到一个组中:**

**1).主页点击全局路由,选择 配置**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image15.jpg" width="35%">

**2). 选择 配置 并 点击分组 然后点击,添加分组或者右上角+号**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image16.png" width="35%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image17.jpg" width="35%">

**3).新建分组  网易云音乐   注意一定是要这个名字 因为配置文件里默认这个名字, 并且可选择性将负载均衡点开(最好不要打开),把我们添加的网易云音乐节点一一加入该小组(最新版小火箭取消负载均衡,那请在网易云音乐分组中选择固定节点)**

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image18.jpg" width="32%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image19.jpg" width="32%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image22.jpg" width="32%">




**4.此时,当开启代理后,无论用户选择哪个节点进行科学上网, 小火箭会把访问网易云音乐的流量自动分配给 我们设置的'网易云音乐'小组进行代理.**
**打开代理后,可以用网易云音乐 周杰伦的专辑<摩羯座>进行测试,只要该专辑所有歌曲都能播放,那么就可以说成功完成了解锁.**
<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image20.jpg" width="32%"><img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/image21.jpg" width="32%">


开启脚本证书的教程--可去Youtube广告

开启 HTTPS 解密

配置——本地文件一栏——点击 Shadowrocket_Linsanity.conf 配置——弹出菜单选择编辑配置：
<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/编辑配置.jpg" width="40%">

可以看到 HTTPS 解密的选择，如果是未打开状态，请点击进去，将 HTTPS 解密的开关打开。
<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/解密.jpg" width="72%">

打开HTTPS开关后会弹出证书界面,请删除原有证书后,重新生成证书.

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/证书.png" width="32%">

然后点击安装证书,在右下角点击Safari打开后强行安装证书，随后在 设置 > 通用 > 关于本机 > 证书信任设置 下，手动开启证书即可．
<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/安装.png" width="32%">
<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/强行安装.png" width="32%">

最后记得返回小火箭界面在https解密右上角那里打勾号确认保存。

### 请喝奶茶？谢谢赞赏!~

<img src="https://raw.githubusercontent.com/AU-Linsanity/Shadowrocket-Clash-QuanX-Rule/main/Shadowrocket/Readme_md_files/赞赏码.jpg" width="49%">

# 所有内容均来自互联网 不确保可用性
# 不要问我太多技术细节 我真的啥都不会
### 说明 :
* 只是搬运和同步更新大佬脚本.
* 不负责维护脚本.
* 只测试自用脚本，其他大部分脚本未测试可用性.


## 免责声明 ：
* Aulinsanity发布的"Shadowrocket小火箭 解锁网易云灰色歌曲+带脚本懒人配置"项目中涉及的任何解锁和解密分析脚本仅用于资源共享和学习研究，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.
* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, Aulinsanity对于由此引起的任何隐私泄漏或其他后果概不负责.
* 请勿将"Shadowrocket小火箭 解锁网易云灰色歌曲+带脚本懒人配置"项目的任何内容用于商业或非法目的，否则后果自负.
* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.
* Aulinsanity 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.
* 您必须在下载后的24小时内从计算机或手机中完全删除以上内容.
* 任何以任何方式查看此项目的人或直接或间接使用该Script项目的任何脚本的使用者都应仔细阅读此声明。Aulinsanity 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或"Shadowrocket 小火箭 解锁网易云灰色歌曲 + 带脚本懒人配置"项目的规则，则视为您已接受此免责声明.

### 特别感谢 ：
* [w37fhy](https://github.com/w37fhy/QuantumultX)

* [@NobyDa](https://github.com/NobyDa)

* [@lhie1](https://github.com/lhie1)

* [@ConnersHua](https://github.com/DivineEngine)

* [@chavyleung](https://github.com/chavyleung)

* [@yichahucha](https://github.com/yichahucha)

* [@langkhach270389](https://github.com/langkhach270389)

* [@Choler](https://github.com/Choler)

* [@onewayticket255](https://github.com/onewayticket255)

* [@NavePnow](https://github.com/NavePnow)

* [@Meeta](https://github.com/MeetaGit)

* [@Neurogram-R](https://github.com/Neurogram-R)

* [@sazs34](https://github.com/sazs34)

* [@id77](https://github.com/id77)

* [@lxk0301](https://github.com/lxk0301)

* [@红鲤鱼与绿鲤鱼与驴](https://github.com/wangdelu2020)

* [@iisams](https://github.com/iisams/Scripts)

* [@barrym-chen](https://github.com/barrym-chen/Script)

* [@ziye12](https://github.com/ziye12/JavaScript)

* [@公众号墨鱼手记](https://github.com/ddgksf2013)

* [@Moonnaicha](https://github.com/Moonnaicha)
