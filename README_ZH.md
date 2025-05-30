
<h1 align="center"> 🏎 Nping </h1>
<p align="center">
    <em>Nping 是一个基于 Rust 开发的终端可视化 Ping 工具, 支持多地址并发 Ping, 可视化图表展示, 数据实时更新等特性 </em>
</p>
<p align="center">
    <img src="docs/imgs/nb.gif" alt="Nping demo" width="30%">
</p>

<p align="center">
    <a href="https://hellogithub.com/repository/21f5600774554866a3d686308df2dbf0" target="_blank">
        <img src="https://api.hellogithub.com/v1/widgets/recommend.svg?rid=21f5600774554866a3d686308df2dbf0&claim_uid=uT2Sc8Xli4PUA76&theme=neutral" alt="Featured｜HelloGitHub" style="width: 200px; height: 60px;" width="250" height="60" />
    </a>
<a href="https://trendshift.io/repositories/13472" target="_blank"><img src="https://trendshift.io/api/badge/repositories/13472" alt="hanshuaikang%2FNping | Trendshift" style="width: 200px; height: 60px;" width="250" height="55"/></a>
</p>

**图表视图**
<p align="center">
    <img src="docs/imgs/black.gif" alt="Nping demo" width="100%">
</p>


**表格视图**
<p align="center">
    <img src="docs/imgs/table.gif" alt="Nping demo" width="100%">
</p>

**点视图**
<p align="center">
    <img src="docs/imgs/point.gif" alt="Nping demo" width="100%">
</p>

**Sparkline 视图**
<p align="center">
    <img src="docs/imgs/sparkline.gif" alt="Nping demo" width="100%">
</p>


## Installation

#### MacOS Homebrew
```bash
brew tap hanshuaikang/nping
brew install nping

nping --help
```


## Feature:
- 支持多地址并发同时 Ping
- 支持可视化延迟展示
- 实时最大最小平均延迟丢包率等指标展示
- 支持 IpV4 和 IpV6
- 支持一个地址下并发 Ping n 个 ip
- 支持输出结果到文件

## 后续的计划:
- UI 界面优化, 增加更多的动态效果

## Usage

```bash
nping www.baidu.com www.google.com www.apple.com www.sina.com -c 20 -i 2

nping --help

🏎  Nping mean NB Ping, A Ping Tool in Rust with Real-Time Data and Visualizations

Usage: nping [OPTIONS] <TARGET>...

Arguments:
  <TARGET>...  target IP address or hostname to ping

Options:
  -c, --count <COUNT>          Number of pings to send [default: 65535]
  -i, --interval <INTERVAL>    Interval in seconds between pings [default: 0]
  -6, --force_ipv6             Force using IPv6
  -m, --multiple <MULTIPLE>    Specify the maximum number of target addresses, Only works on one target address [default: 0]
  -v, --view-type <VIEW_TYPE>  View mode graph/table/point/sparkline [default: graph]
  -o, --output <OUTPUT>        Output file to save ping results
  -h, --help                   Print help
  -V, --version                Print version
```

## 致谢
感谢这些朋友对 Nping 提出的反馈和建议。

| [ThatFlower](https://github.com/ThatFlower) | [zx4i](https://github.com/zx4i) | [snail2sky](https://github.com/snail2sky) | [shenshouer](https://github.com/shenshouer) | [vnt-dev](https://github.com/vnt-dev) | [qingyuan0o0](https://github.com/qingyuan0o0)
| [Onlywzr](https://github.com/Onlywzr)

感谢以下自媒体对 Nping 的关注和转发。

| [阮一峰的网络日志](https://www.ruanyifeng.com/blog/weekly/) |[Rust 中文社区](https://rustcc.cn/) | [公众号:奇妙的linux世界](https://mp.weixin.qq.com/s/lK_OqKp2yY8lDBoyLxtdGA) | [公众号:IT运维技术圈](https://mp.weixin.qq.com/s/bDJZ-H02dIKG3R7LQCeyaQ)
| [X:@geekbb](https://x.com/geekbb/status/1875754541905539510) | [公众号:一飞开源](https://mp.weixin.qq.com/s/BZjr54h8dIQgzr8UW3fwOQ) ｜ [公众号: 开源日记](https://mp.weixin.qq.com/s/uGtkD4x_XOFyKNbIy5pHYA)

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=hanshuaikang/Nping&type=Date)](https://star-history.com/#hanshuaikang/Nping&Date)