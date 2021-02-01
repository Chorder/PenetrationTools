## PenetrationTools(渗透测试工具收集)

感谢这些工具作者们的贡献和分享！

### 如何使用这个仓库？

克隆这个仓库到本地，使用git submodule 同步即可。

```
$ git clone https://github.com/Chorder/PenetrationTools.git
$ cd PenetrationTools
$ git submodule init
$ git submodule update
```

### 如何构建一个自己的工具仓库？

新建工具仓库，使用git submodule添加工具模块即可。

```
$ git init MyPenetrationTools
$ cd MyPenetrationTools
$ git submodule add https://github.com/Chorder/PenetrationTools.git PenetrationTools
```

### 工具列表(Tools List)

+ 漏洞搜索
    + https://github.com/offensive-security/exploitdb.git
+ 漏洞扫描
    + https://github.com/zigoo0/webpwn3r
    + https://github.com/lijiejie/BBScan
    + https://github.com/sowish/LNScan
    + WordPress插件漏洞扫描
        + https://github.com/wpscanteam/wpscan
        + https://github.com/mintobit/WP-plugin-scanner
    + Shellshock漏洞扫描
        + https://github.com/gry/shellshock-scanner
+ Backdoor
    + 冰蝎
        + https://github.com/rebeyond/Behinder.git
    + Python WEBSHELL工具(菜刀)
        + https://github.com/fengxuangit/pyshell
+ 目录爆破
    + https://github.com/maurosoria/dirsearch.git
+ 子域名爆破
    + https://github.com/lijiejie/subDomainsBrute
+ 信息泄漏
    + Git仓库泄漏
        + https://github.com/lijiejie/GitHack
    + DNS域传送信息泄漏
        + https://github.com/lijiejie/DNS_AXFR_Client
    + IIS短文件名信息泄漏
        + https://github.com/lijiejie/IIS_shortname_Scanner
    + .Ds_Store文件信息泄漏
        + https://github.com/lijiejie/ds_store_exp
    + Padding Oracle漏洞利用
        + https://github.com/escbar/pypadbuster.git
        + Indepent/padding-oracle/padBuster_v0.3.pl
+ 命令执行
    + Shiro反序列化漏洞利用工具
        + https://github.com/Kit4y/Awesome_shiro
+ 邮箱爆破
    + https://github.com/lijiejie/OutLook_WebAPP_Brute
+ XSS扫描
    + https://github.com/bsmali4/xssfork
    + https://github.com/enjoiz/XXEinjector
    + https://github.com/DanMcInerney/xsscrapy
+ WebCMS识别
    + https://github.com/qingsh4n/whaweb
+ 流量代理
    + https://github.com/sensepost/reGeorg
+ 提权辅助
    + https://github.com/pentestmonkey/unix-privesc-check
    + https://github.com/InteliSecureLabs/Linux_Exploit_Suggester
    + https://github.com/rebootuser/LinEnum
+ 综合渗透
    + https://github.com/rapid7/metasploit-framework
    + https://github.com/SECFORCE/sparta
    + 内网UPNP设备发现及端口映射
        + https://github.com/0x90/miranda-upnp
+ WiFi渗透
    + https://github.com/DanMcInerney/LANs.py
+ 中间人攻击
    + https://github.com/byt3bl33d3r/MITMf
+ 打印机渗透
    + https://github.com/RUB-NDS/PRET

