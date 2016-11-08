# 提取黑名单
## public sites
Segugio这篇论文里提到从public和commercial获得黑名单,文中提到了几个网站, 包括:
spyeyetracker.abuse.ch(目前被 www.abuse.ch 替代), zeustracker.abuse.ch, malwaredomains.com, 和 malwaredomainlist.com

### From malwaredomainlist.com
export.csv-----这个csv文件就是malwaredomainlist.com网站提供的黑名单。这个网站提供域名黑名单的下载地址http://www.malwaredomainlist.com/forums/index.php?topic=3270.0，所以不用爬虫爬了。



### From abuse.cn
*关于abuse.cn这个网站,它提供了几种类型的blocklist, 包括domain,IP,url,SSL指纹; 我们最关心的可能是domain和IP, 根据需求下载(网站提供了打包下载方式)*

ZeuS_domain_blocklist.txt，ZeuS_IP_blocklist.txt-----www.abuse.ch的子子链接https://zeustracker.abuse.ch/blocklist.php提供ZeuS domains & IPs blocklist

RW_DOMBL.txt，RW_IPBL.txt-----www.abuse.ch的子子链接https://ransomwaretracker.abuse.ch/blocklist/ransomware domains & IPs blocklist


feodo_IP_BL_vACD.txt-----www.abuse.ch的子子链接https://feodotracker.abuse.ch/blocklist/提供 Feodo Trojan四种版本(ABCD version)的C&C服务器的domain & IP 的blocklist, 只能下载下来A\C\D三种version的C&C服务的IP blocklist.
