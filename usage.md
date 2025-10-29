# ========================只封堵磐基使用名称空间下暴露的端口，请执行下面的方法：==================
# 1 先执行下面的抓取流量
./iptables_block.sh --run-host-caps --block-only-panji

# 2 再生成封堵脚本
./iptables_block.sh --gen-block-sripts --block-only-panji










# ========================封堵所有，请执行下面的方法：==================
# 1 先执行下面的抓取流量
./iptables_block.sh --run-host-caps 

# 2 再生成封堵脚本
./iptables_block.sh --gen-block-sripts 
