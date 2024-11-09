# 关于领地

## 领地规定
1.严禁将他人未及时圈地的地方圈地占为己有<br>
2.禁止将公共地区圈地<br>
领地创建限制最大为12个区块，每人最多可创建10个领地

## 如何创建领地
### 1.自动创建

自动创建不需要选择对角线点，会以玩家为中心自动创建一定区域的领地。<br>
使用 /dominion 或/dom 打开主菜单，点击【创建领地】;<br>
在弹出的 UI 中输入你要创建的领地名称;<br>
输入完成后左键点击下方中间的绿色混凝土，即可自动创建一块领地;<br>
自动创建的领地默认半径为10<br>

### 2.手动创建
需要使用圈地工具（默认为箭矢），依次使用左键点选领地长方体区域的第一个点、右键点击长方体区域的第二个点。<br>
然后使用： /dominion create <领地名称> 创建领地，领地名称不可与其他领地重复。<br>

> [!TIP]
> 领地名称不可与其他领地重复；<br>领地名称不可包含空格；<br>领地名称不可包含特殊字符；

## 领地的权限设置
### 1.权限的种类
Dominion 采用了 访客-成员-权限组 的权限管理模型，来更好的让玩家所用。<br>
如果你只想要知道如何添加成员和管理员，黑名单的话，可以直接跳过下面的一大堆理论讲解，前往3.权限的赋予处。如果你想要稍微了解一点的它们的含义的话可以继续阅读下去。<br>
 <br>


访客：领地的访客权限，不属于领地成员的玩家将收到此权限的限制；<br>
成员：领地的成员权限，属于领地成员的玩家将收到此权限的限制；<br>
权限组：领地的权限组，将玩家添加到权限组中，可以为多个玩家配置相同的权限；可以理解为可自定义的权限管理，不过对于一般玩家来说是不常用到的<br>
 <br>
当一个玩家不属于领地成员时将收到访客权限的限制；<br>
如果是领地成员那么会判断玩家是否属于权限组；<br>
如果玩家属于权限组那么将收到对应权限组的行为控制；<br>
如果玩家不属于权限组那么将采用该玩家在此领地中的成员权限；<br>

### 2.权限的管理
管理员是领地成员权限中的一个特殊权限：<br>
 <br>
✅管理员可以做的事：<br>
该领地的其他所有权限<br>
修改领地权限<br>
修改领地的玩家权限（添加、删除、修改）<br>
 <br>
❌管理员不可以做的事：<br>
删除领地<br>
修改领地尺寸<br>
将其他玩家设置为管理员<br>
 <br>
通过将一些玩家设置为管理员，可以让他们帮助你管理领地的其他玩家，减轻领地所有人的操作负担。同时不必担心管理员会对领地进行破坏性操作（例如删除、缩小领地）。<br>
  <br>

### 3.权限的赋予

添加成员:/dom member add 领地的名字 玩家名<br>
(/dom = /dominion 两者只是写法不一致，本质为同一个指令)<br>

后续可以通过打开领地菜单 /dominion；<br>
在 【我的领地】 中点击对应领地的 【管理】<br>
（上述步骤可以通过/dom manage 领地名直接达到）<br>

在领地管理界面中选择 【成员管理】，此处列出了领地的所有成员；<br>
点击 【配置权限】 可以配置此成员在领地内的权限；<br>
点击 【移除成员】 可以将此成员移出领地;<br>
如果一个玩家属于某权限组，那么你不能单独编辑他的权限，对应【配置权限】为灰色不可点击；<br>
玩家名称最前方标记含义：<br>
 <br>
【A】：该领地管理员<br>
【N】：普通成员<br>
【B】：黑名单成员（没有移动权限）<br>
【G】：属于某个权限组<br>
注意事项<br>
选择成员页面只会显示在安装了Dominion后登录过服务器的玩家名称，因此暂时不支持对从没有在服务器登录过的玩家进行操作。<br>
<br>
你也可以通过同样的方式管理访客的权限。<br>
通过搜索框添加成员不支持模糊搜索，需要输入准确的玩家名称（大小写敏感）。<br>

## 如何删除领地

使用命令 /dominion delete <领地名称> force 即可删除领地

## 其他

### 玩家开放的领地
玩家可以通过设置领地内访客的权限来更好的公开刷怪塔，小黑台，交易所之类的场所。<br>
指令/dom manage 领地名<br>
找到访客权限，找到移动和传送权限，点击红框即可运行其他玩家进入和直接通过领地名传送到此处。<br>

### 已公开的玩家领地
领地名： 冰船起点<br>
简介： MC冰道赛车比赛（）在11.2日晚进行了一次多人比赛，感兴趣的话可以喊上几个朋友一起去玩玩，请不要破坏赛道，我们可以查出来的:D <br>
指令: /dom tp 冰船起点<br>
<br>

领地名：Koulai的附魔商店<br>
简介：全服免费的最低价最全的附魔书村民商店！！！<br>
造福广大服务器玩家，其贡献的价值和示范的作用对服务器的好影响不可估量。<br>
指令：/dom tp Koulai<br>


### 其他的其他
懒得写了捏 更为详细的文档请各位前往[官方文档](https://dominion.lunadeer.cn/zh-cn/manage-dominion/)查看<br>
<br>
还有其他玩家公开领地可以qq发给gqch之后会更新添加到文档中。