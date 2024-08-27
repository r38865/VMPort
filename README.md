# TESTED ON

- KVM VPS ( 1GB RAM )
- UBUNTU 20.04 TLS



# SETTING CLOUDFLARE

- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF



# MULTI-PORT

```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/r38865/VMPort/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh

  ```
