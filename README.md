# embydbfix
emby数据库损坏修复

# 由于我是一句代码都不懂的小白,所以我的脚本都是在ai的帮助下写出来的.如有问题还请大佬帮忙修改.

# 一键脚本 
# 将/vol1/1000/docker/emby/config改为自己的emby对应的地址
# 运行脚本前请手动备份数据库 data/library.db

curl -LJO https://raw.githubusercontent.com/diciky/embydbfix/refs/heads/main/embydbfix.sh && chmod +x embydbfix.sh && sudo ./embydbfix.sh --path /vol1/1000/docker/emby/config

