自动化渗透测试的侦察扫描仪：sn1per 
sn1per是一个自动化渗透测试侦察扫描仪，可以在渗透测试和漏洞扫描过程中使用。

特点：

自动化渗透测试的侦察扫描：sn1per
自动收集基本侦察（例如WHOIS，PING，DNS，等）
自动启动谷歌黑客攻击目标域查询
自动枚举打开的端口
蛮力sub-domains和DNS信息
自动运行Nmap脚本对目标开放的端口
自动扫描所有常见的漏洞的网络应用程序
自动蛮力所有打开服务

安装：

./ install.sh

安装所有的依赖。建议在Kali Linux安装使用。

使用：

./sn1per domain/IP/hostname

+ -- --=[Sn1per v1.3 by 1N3
+ -- --=[http://crowdshield.com
 
Sn1per - Automated Pentest Recon Scanner

ABOUT:
Sn1per is an automated scanner that can be used during a penetration test to enumerate and scan for vulnerabilities. 

FEATURES:
- Automatically collects basic recon (ie. whois, ping, DNS, etc.)
- Automatically launches Google hacking queries against a target domain
- Automatically enumerates open ports
- Automatically brute forces sub-domains and DNS info
- Automatically runs targeted nmap scripts against open ports
- Automatically scans all web applications for common vulnerabilities
- Automatically brute forces all open services

INSTALL:
./install.sh - Installs all dependencies. Best run from Kali Linux. 

USAGE:
./sn1per <target>

SAMPLE REPORT:
https://gist.githubusercontent.com/1N3/070d14c364e5f23bfe5e/raw/8e152e740ba50cd49bb3366ec91cf7d08ca02715/Sn1per%2520Sample%2520Report
