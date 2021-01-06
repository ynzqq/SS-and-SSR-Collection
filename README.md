# SS-and-SSR-Collection
酸酸及酸酸乳相关常用资源汇集，仅个人收集向，不定时更新

## Source
### Shadowsocks
| Platform | URL                                                         |
|----------|-------------------------------------------------------------|
| Windows  | https://github.com/shadowsocks/shadowsocks-windows/releases |
| MacOS    | https://github.com/shadowsocks/ShadowsocksX-NG/releases     |
| Android  | https://github.com/shadowsocks/shadowsocks-android/releases |
| obfs     | https://github.com/shadowsocks/simple-obfs-android/releases |

### ShadowsocksR
| Platform | URL                                                                  |
|----------|----------------------------------------------------------------------|
| Windows  | https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases  |
| MacOS    | https://github.com/shadowsocksr-backup/ShadowsocksX-NG/releases      |
| Android  | https://github.com/shadowsocksr-backup/shadowsocksr-android/releases |

协议插件文档：https://github.com/shadowsocksr-backup/shadowsocks-rss/blob/master/ssr.md

### SSTap
https://www.sockscap64.com/sstap-enjoy-gaming-enjoy-sstap/

### Rules
#### SSTap
https://github.com/FQrabbit/SSTap-Rule

#### GFWList
https://github.com/gfwlist/gfwlist

#### ChinaList
https://github.com/felixonmars/dnsmasq-china-list

#### PAC
https://github.com/breakwa11/gfw_whitelist

### chnrouter
#### IPIP
https://raw.githubusercontent.com/17mon/china_ip_list/master/china_ip_list.txt

#### APNIC
```bash
curl 'http://ftp.apnic.net/apnic/stats/apnic/delegated-apnic-latest' | grep ipv4 | grep CN | awk -F\| '{ printf("%s/%d\n", $4, 32-log($5)/log(2)) }' > chnroute.txt
```

### DNS
ChinaDNS: https://github.com/shadowsocks/ChinaDNS

Pcap DNSProxy: https://github.com/chengr28/Pcap_DNSProxy

overture: https://github.com/shawn1m/overture
