# WinXray 
WinXray[:loud_sound:](http://dict.youdao.com/dictvoice?audio=winxray&type=2) 是最简洁轻快的 V2Ray、XRay、Trojan、Trojan-go、Shadowsocks、SSR(ShadowsocksR)、SSRoT、NaïveProxy，SOCKS，HTTP,HTTPS 全能通用客户端（Windows系统），支持并发检测大量服务器并迅速找到当前最快的服务器，服务器连接异常时可自动寻找其他速度最快的服务器 - 切换速度快如闪电，自订阅源获取的服务器异常时可自动刷新订阅，并且自带一键自动部署服务端工具。

**本软件源码已放弃版权贡献到公共域** ，源码可使用 [aardio](http://www.aardio.com) 编译生成单文件绿色EXE

# WinXray 未注册任何域名，谨防钓鱼网站    
WinXray 分为原版、抄袭版。  
抄袭版没有贡献任何功能，仅添加了假冒官网推广链接，然后原版更新任何功能，抄袭版都会复制粘贴改成他自己的名字重新提交，并且乱改版本号

# 本项目说明
项目克隆自 [https://github.com/TheMRLL/WinXray](https://github.com/TheMRLL/WinXray)  
很显然，我克隆的这个项目就是上面所说的抄袭版，加了很多广告。  
我觉得不必纠结到底谁是原版，毕竟这个软件最初也不叫`WinXray`，而是`win2ray`，这是现在`github`上能找到的[最古老的版本](https://github.com/xinanzai/win2ray)，但这个不是原作者，原作者已经删库了。  

### 为什么选择在这个“抄袭版”的基础上改进
这个版本是我接触winxray的第一个版本，用了很久，代理上没有什么问题，且这个版本较其他版本改进了些内容，比如  
- 将`v2ray`替换为更好的`xray`（虽然看到有些写的原版的也有xray，不过还混着v2ray）
- 添加二维码识别功能
- 其他优化

### 改进计划
虽然这个版本较原版有些优化，但仍然值得改进。  
- [x] 删除所有广告
- [x] 优化系统托盘显示与交互
- [ ] github直连下载改为cdn下载
- [x] 调整配置目录为和应用同级的config目录，方便打包拷走
- [x] 移除检查更新用的大文件