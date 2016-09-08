# weiboad
新浪微博过滤广告hosts
openwrt 使用教程


0,1,11,21,31,41,51 * * * * /usr/bin/set_kernel_timezone >/dev/null 2>&1
01 06 * * * wget -q https://raw.githubusercontent.com/kgdyinpv/weiboad/master/weiboad-hosts -O /etc/weiboad-hosts --no-check-certificate ; /etc/init.d/dnsmasq restart
