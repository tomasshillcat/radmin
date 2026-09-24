🇨🇳 中文 | 🇺🇸 [English](README_EN.md) | 🇷🇺 [Русский](README_RU.md)

#### Radmin VPN 并非通常意义上的 VPN，无法帮你绕过访问限制。推荐替代方案：[vpnforchinese.com](https://www.vpnforchinese.com/)</br>

官方网站（radmin vpn 官网）：[radmin-vpn.com](https://www.radmin-vpn.com/)</br>
官方中文页：[radmin-vpn.com/cn](https://www.radmin-vpn.com/cn/)</br>
免费下载（安装包）：[radmin-vpn.com](https://www.radmin-vpn.com/)（当前版本 2.1.4951.1）</br>
帮助中心：[radmin-vpn.com/help](https://www.radmin-vpn.com/help/)</br>

### 简介

Radmin VPN 是 **Famatech Corp.** 推出的免费软件，用于在互联网上创建**虚拟局域网**，让处于不同路由器和防火墙后的电脑像在同一个局域网内一样互联互通。它是知名度最高的 Hamachi 免费替代品，大多数人安装它的目的是**局域网联机游戏**——我的世界（Minecraft）、泰拉瑞亚，以及各类没有官方联机服务器的老游戏——此外还有远程共享文件和连接公司电脑。它**不是**隐私类或解锁类 VPN：不会对网站隐藏你的 IP，不会把上网流量经由出口服务器转发，也没有国家节点列表。

### Radmin VPN 下载 —— 全部客户端

Radmin VPN **仅支持 Windows**。官方没有 macOS、Linux、安卓或 iOS 客户端；任何提供这些版本的网站都不是在分发 Famatech 的软件。

| 平台 | 下载 | 说明 |
| ---- | ---- | ---- |
| **Windows 电脑版** | [下载](https://www.radmin-vpn.com/) | 支持 Windows 11 / 10 / 8 / 7；版本 2.1.4951.1 |
| **官方中文页** | [下载](https://www.radmin-vpn.com/cn/) | 官方简体中文站点 |
| **官方俄文页** | [下载](https://www.radmin-vpn.com/ru/) | 官方俄语站点 |
| **macOS** | —— | 无官方客户端 |
| **Linux** | —— | 无官方客户端 |
| **安卓 / iOS** | —— | 无官方客户端 |
| **Radmin（远程控制）** | [下载](https://www.radmin.com/download/) | 另售的付费产品 |

关于域名的提醒：官方站点是 **radmin-vpn.com**，中文版与俄文版分别位于 `/cn/` 和 `/ru/` 路径下。其他域名上以「Radmin LAN」名义分发的站点并非官方下载入口——即便页面底部挂着 Famatech 的版权声明。

### 安装与使用步骤

1. 从官网下载安装包并运行，安装过程会在 Windows 中添加 **Famatech Radmin VPN Ethernet Adapter** 虚拟网卡。
2. **无需注册、无需登录**，打开即用。
3. 建立网络：点击 **Create network（创建网络）**，设置网络名称和密码，然后把这两项发给要一起联机的人。
4. 其他人点击 **Join network（加入网络）**并输入相同的名称和密码即可。成员会显示在列表中，附带各自的虚拟 IP、延迟和状态。

每位成员会分配到一个 **26.0.0.0/8** 网段的地址；把这个地址（或成员名称）当作普通局域网地址使用即可，用于游戏开房、文件共享或远程桌面。

### 网络结构

Radmin VPN 没有常规意义上的服务器网络，也没有可供选择的国家列表。它在网络成员之间建立**点对点（P2P）直连**；当双方的 NAT 或防火墙导致无法直连时，会退回到经由 Famatech 基础设施的**中继 / TCP 连接**，延迟会相应增加。Famatech 未公开服务器位置、容量数据，也未说明单个网络的成员数量上限。因此实际速度取决于两端各自的网络条件，而非服务商的骨干网。

### 套餐方案

| 产品 | 设备数 | 用途 | 月付 | 年付 | 两年付 |
| ---- | ------ | ---- | ---- | ---- | ------ |
| **Radmin VPN** | 不限 | 虚拟局域网、联机游戏、远程访问 | 免费 | 免费 | 免费 |
| **Radmin（远程控制）** | 按授权数 | 远程桌面管理 | —— | 每个授权 $49 起 | —— |

Radmin VPN **完全免费**：没有付费版本、没有广告版本、没有流量配额，也没有使用期限——Famatech 明确说明其中没有广告、也没有付费功能。公司的收入来自另一款商业产品 **Radmin** 远程控制软件，单机授权约 $49 起，更多数量有批量授权包。

### 支付方式与退款

无需付费，也就不存在退款：Radmin VPN 不收集任何支付信息，不需要订阅，完全没有计费环节。如果改为购买付费的 **Radmin** 远程控制产品，其授权为永久授权而非订阅制，通过 Famatech 官方商店及其合作伙伴渠道销售。购买入口：[radmin.com](https://www.radmin.com/)。

### 功能特性

* **互联网上的虚拟局域网** —— 把处于不同 NAT 和防火墙后的机器接入同一个网络
* **256 位 AES 加密** —— 成员之间端到端加密
* **专为联机优化** —— 广泛用于我的世界等仅支持局域网联机的游戏；Famatech 提供分游戏教程，并说明 Hamachi 的设置方法通常同样适用
* **与 Radmin 集成** —— 可对网络中任意成员直接发起远程控制会话
* **自动更新**、无广告、无需注册，网络数量与成员数量不限

它没有终止开关、没有分应用分流、没有广告拦截，也没有协议切换——对局域网工具而言这些功能都不适用。

### 速度、流媒体与 BT 下载

Radmin VPN 无法解锁 Netflix、BBC iPlayer 或任何流媒体片库——你访问公网的流量根本不经过它，IP 地址和所在地区都不会改变。它同样不是常规意义上的 BT 下载工具，不过可以用于自建网络成员之间的文件传输。速度取决于两名成员之间的 P2P 直连质量；退回中继模式时会明显变慢，Famatech 也未公布任何吞吐量数据。

### 隐私与审计

Famatech 声明采用**无日志政策**——不追踪、不出售用户数据——并以 256 位 AES 加密成员之间的流量。除此之外，与商业 VPN 相比信息相当有限：**没有公开的独立审计、没有透明度报告、也没有预警信标（warrant canary）**，客户端为闭源，公司也未说明中继基础设施托管在何处。对一款免费的局域网工具而言这算正常，而非危险信号，但这也意味着其隐私承诺只能依赖厂商自述。相关政策：[radmin-vpn.com/privacy](https://www.radmin-vpn.com/privacy/) · [radmin-vpn.com/security](https://www.radmin-vpn.com/security/)。

### 免费版

整个产品就是免费版。Radmin VPN 没有高级版升级、没有设备数量上限、没有流量配额，也没有到期的试用期——同一个安装包对个人用户免费，按 Famatech 的说明，商业使用同样免费。相比付费的消费级 VPN，你放弃的是隐私保护和地区解锁相关的一切能力——而这些本来就不是 Radmin VPN 的设计目标。

### Radmin VPN 商业版

商业线是它的付费兄弟产品：**Radmin** 远程控制软件，被 IT 团队用于技术支持和服务器管理，按受控电脑数量永久授权，单机约 $49 起，另有 50 台和 100 台授权包，更大规模可走批量授权。Famatech 还发布了两款免费的网络发现工具 **Advanced IP Scanner** 与 **Advanced Port Scanner**，均可与 Radmin 集成实现一键远程访问。详见：[radmin.com](https://www.radmin.com/)。

### 客户支持

支持以文档为主：帮助中心提供安装、防火墙设置与故障排查文章、分游戏的联机教程，以及邮件支持表单。**没有在线聊天，也没有 7×24 小时客服**——对免费产品来说这在意料之中。帮助中心：[radmin-vpn.com/help](https://www.radmin-vpn.com/help/) · [radmin-vpn.com/support](https://www.radmin-vpn.com/support/)。

### 其他 Famatech 应用

同一家开发商还提供远程桌面控制软件 [Radmin](https://www.radmin.com/)，以及两款免费网络工具：用于发现网络中所有设备的 [Advanced IP Scanner](https://www.advanced-ip-scanner.com/)，和用于检测开放端口的 [Advanced Port Scanner](https://www.advanced-port-scanner.com/)。两者均为 Windows 工具，且都可对接 Radmin 进行远程管理。

### Radmin VPN 在中国大陆

Radmin VPN 不是用来突破防火长城的工具——把它当成翻墙软件是关于它最常见的误解。它不会代理你的网页流量，因此无法打开被封锁的网站，Famatech 也从未作出过这类宣称。中国用户安装它通常是为了局域网联机——这也是它会和我的世界及各类联机工具一起出现在搜索结果中的原因——而即便是这个用途，在大陆也未必稳定：中继回退线路和下载站点本身有时会很慢甚至无法访问。如果你的目标是突破网络审查，需要的是另一类产品。
