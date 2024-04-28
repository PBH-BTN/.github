## PBH-BTN

欢迎来到 PBH-BTN 组织，我们是一群 BitTorrent 的热爱者。这里是一个以建设和维护健康的 BitTorrent 网络为目标的，由社区驱动的组织。  
由最初的 Ghost-chu/PeerBanHelper 发展而来，在 hp/torrent 和 dt/torrent 等恶意的吸血者出现后，我们构想了一个 BTN 网络并付诸行动，并将 PBH 项目和 BTN 一起转移到了一个独立组织，与吸血和破坏者进行技术对抗。  

### 看看我们的工作

#### [PeerBanHelper](https://github.com/PBH-BTN/PeerBanHelper)

一切的开始，也是首个 BTN 协议的实现。使用 Java 语言编写的一个兼容 qBittorrent 和 Transmission 客户端的反吸血程序。通过 WebUI 获取数据、并通过预置/云端规则封禁找到的恶意吸血者。

#### [BTN-Spec](https://github.com/PBH-BTN/BTN-Spec)

BTN 威胁防护网络的实现规范，鼓励更多人构建自己的 BTN 客户端/服务端实现。基于隐私考量设计，并满足多点分析的协议。

#### [BTN-Collected-Rules](https://github.com/PBH-BTN/BTN-Collected-Rules)

由 BTN 网络数据分析的来的 IP 规则集，其中包含了经过确认是恶意吸血/破坏者的 IP 地址。您可以将其加入系统防火墙来阻止它们连接到你。
