
## ACL4SSR_Online_Full_Modify
自定义 YAML配置文件 https://raw.githubusercontent.com/AKING0v0/ClashRule/refs/heads/main/Clash_Max.yaml

自定义 订阅转换 配置转换 规则转换 的远程配置：

https://raw.githubusercontent.com/AKING0v0/ClashRule/refs/heads/main/ACL4SSR_Online_Full_Modify.ini

修改自
https://git.moezx.cc/mashiro/ACL4SSR/raw/branch/master/Clash/config/ACL4SSR_Online_Full.ini
https://raw.githubusercontent.com/zsokami/ACL4SSR/main/ACL4SSR_Online_Full_Mannix_No_DNS_Leak.ini

可添加无 DNS 泄漏：
和原配置只有一行差异
原配置不在已知名单中的（国内外）域名会先通过当地 DNS 服务器解析一次。
添加 no-resolve 后，不在已知名单中的（国内外）域名将直接✈️ 起飞

由于ACL4SSR规则停更，所以替换了一部分blackmatrix7规则

移除
- 🛑 广告拦截
- 📢 谷歌FCM
- Ⓜ️ 微软云盘
- 🍎 苹果服务
- 📲 电报消息
- 🎶 网易音乐
- 🎮 游戏平台
- 🎥 奈飞视频
- 🌏 国内媒体
- 🌍 国外媒体
- 📺 巴哈姆特
- 🍃 应用净化

重命名
- Ⓜ️ 微软服务 -> 🪟 微软服务
- 🚀 节点选择 -> ✈️ 起飞选择
- 🚀 手动切换 -> 👆🏻 手动切换
- ♻️ 自动选择 -> ⚡ 最低延迟

新增
- 🎓 学术平台
- 🌏 全球节点

url-test                                  
- 间隔时间 300秒 -> 120秒
- 容差 50/150毫秒 -> 60毫秒
