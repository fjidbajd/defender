# defender


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)




## 功能

*    一键屏蔽常见网络测绘(censys+facebook+部分shodan)
*   只允许cloudflare cdn ip 回源＋白名单管理(基于iptable)
*   自动下载黑名单IP并自动屏蔽(基于ipset)






## 使用方法

屏蔽
```
curl -sS -O https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/block_censys_ips.sh && chmod +x block_censys_ips.sh && ./block_censys_ips.sh
```
端口回源允许
```
bash <(wget -qO- https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/cloudflare-only.sh)
```

自动定时下载黑名单并封禁
```
apt-get install iptables ipset cron
```

```
bash <(wget -qO- https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/ipblocker.sh)
```
