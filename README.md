## AbBlock List

广告过滤规则整合，使用 [fordes123/ad-filters-subscriber v2](https://github.com/fordes123/ad-filters-subscriber/tree/v2)
构建。定期合并上游规则，去除重复以及包含无效域名的项目

| 文件              | 适用                          |        github        |         ghproxy          |         jsdelivr          |
|-----------------|:----------------------------|:--------------------:|:------------------------:|:-------------------------:|
| `easylist.txt`  | AdGuard、AdBlock 等主流去广告扩展和程序 | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `dns.txt`       | AdGuard Home 等基于DNS的过滤工具    |   [link][dns-raw]    |   [link][dns-ghproxy]    |   [link][dns-jsdelivr]    |
| `dnsmasq.conf`  | dnsmasq 及其衍生版本              | [link][dnsmasq-raw]  | [link][dnsmasq-ghproxy]  | [link][dnsmasq-jsdelivr]  |
| `clash.yaml`    | clash 及其衍生版本                |  [link][clash-raw]   |  [link][clash-ghproxy]   |  [link][clash-jsdelivr]   |
| `smartdns.conf` | smartdns                    | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts`         | 几乎所有操作系统原生支持                |  [link][hosts-raw]   |  [link][hosts-ghproxy]   |  [link][hosts-jsdelivr]   |
| `private.txt`   | 本仓库维护的私有规则，以 easylist 形式提供  | [link][private-raw]  | [link][private-ghproxy]  | [link][private-jsdelivr]  |

[easylist-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/easylist.txt

[dns-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/hosts

[private-raw]: https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/star1145209/adblock_list/main/rule/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/star1145209/adblock_list@main/rule/private.txt

<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard 基础过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard 移动广告过滤器</a></li>
    <li><a href="https://adguard.com/kb/zh-CN/general/ad-filtering/adguard-filters/">AdGuard 防跟踪保护过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL跟踪过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard 恼人广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard 解除搜索广告和自我推销过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard 中文过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts">大圣净化</a></li>
    <li><a href="https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://raw.githubusercontent.com/xndeye/web-ad-rule/master/easylist.txt">xndeye/web-ad-rule</a></li>    
    <li><a href="https://raw.githubusercontent.com/8680/GOODBYEADS/master/data/rules/dns.txt">8680/GOODBYEADS</a></li>
</ul>
</details>
