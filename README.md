# embydbfix
emby数据库损坏修复


# 一键指令
# /vol1/1000/docker/emby/config改为自己的emby对应的地址
curl -LJO https://raw.githubusercontent.com/diciky/embydbfix/refs/heads/main/embydbfix.sh && chmod +x embydbfix.sh && sudo ./embydbfix.sh --path /vol1/1000/docker/emby/config
