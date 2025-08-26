# defender
一键屏蔽常见网络测绘+只允许cloudflare cdn ip 回源+自动下载黑名单IP并自动屏蔽

## 使用方法


```
curl -sS -O https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/block_censys_ips.sh && chmod +x block_censys_ips.sh && ./block_censys_ips.sh
```

```
bash <(wget -qO- https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/cloudflare-only.sh)
```

```
apt-get install iptables ipset cron
```

```
bash <(wget -qO- https://raw.githubusercontent.com/fjidbajd/defender/refs/heads/main/ipblocker.sh)
```
