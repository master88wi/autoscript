# AUTOSCRIPT
Installer Script SSH Xray Multi Port 44, 80
DEBIAN 10 / Ubuntu 20
CPU MIN 1 CORE
RAM 1GB

### INSTALL SCRIPT
- Step 1
```
apt update && apt upgrade -y && reboot
```
- Step 2
```
apt install -y wget screen && wget -q https://raw.githubusercontent.com/firdaus-rx/autoscript/main/main.sh && chmod +x main.sh && screen -S install ./main.sh
```

### PORT INFO
```
- SSH WS TLS 443
- SSH WS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```

### Kontak Admin
- Telegram : https://t.me/firdaus_rx

## Stargazers over time

[![Stargazers over time](https://starchart.cc/firdaus-rx/AutoScriptXray.svg)](https://starchart.cc/firdaus-rx/autoscript)
