# Awesome CobaltStrike ![Awesome CobaltStrike](https://img.shields.io/badge/awesome-cobaltstrike-red.svg) ![Awesome community](https://img.shields.io/badge/awesome-community-green.svg)

### 0x00 前言
1. 一部分是近期做RedTeam项目的时候看到的一些关于CobaltStrike不错的文章
2. 目前网上的Aggressor Script种类繁多，大多数资源的聚合都是只给出对应的链接，而不说明是干什么的，以至于在查看时不知道如何选择，要一个一个打开看
3. 关于新特性BOF资源的整合
4. 解决要用的时候找不到合适aggressor script或者BOF的问题
5. 如果有本repo没有涉及的优质内容，欢迎大家提交pr

### 0x01 相关文章合集
基础知识参考：
1. [Cobalt_Strike_wiki](https://github.com/aleenzz/Cobalt_Strike_wiki)
2. [CobaltStrike4.0笔记](https://github.com/Snowming04/CobaltStrike4.0_related)
3. [CobaltStrike相关网络文章集合](https://4hou.win/wordpress/?cat=306)

破解以及定制参考：
1. [IntelliJ-IDEA修改cobaltstrike](https://pingmaoer.github.io/2020/06/08/IntelliJ-IDEA修改cobaltstrike/)
2. [CobaltStrike二次开发环境准备](https://pingmaoer.github.io/2020/06/24/CobaltStrike二次开发环境准备/)
3. [Cobal Strike 自定义OneLiner](https://evi1cg.me/archives/Custom_Oneliner.html)
4. [通过反射DLL注入来构建后渗透模块（第一课）](https://payloads.online/archivers/2020-03-02/1)
5. [Cobalt Strike Aggressor Script （第一课）](https://payloads.online/archivers/2020-03-02/4)
6. [Cobalt Strike Aggressor Script （第二课）](https://payloads.online/archivers/2020-03-02/5)

使用技巧参考：
1. [Cobalt Strike Spear Phish](https://evi1cg.me/archives/spear_phish.html)
2. [run CS in win -- teamserver.bat](https://evi1cg.me/archives/teamserver.html)
3. [Remote NTLM relaying through CS -- related to CVE_2018_8581](https://evi1cg.me/archives/Remote_NTLM_relaying_through_CS.html)
4. [CobaltStrike证书修改躲避流量审查](https://mp.weixin.qq.com/s/sYfvD0XQqi6BFw70_jrv5Q)
5. [渗透神器CS3.14搭建使用及流量分析](https://mp.weixin.qq.com/s/DG87HFrwHf25_M2Dnfdx3g)
6. [CobaltStrike生成免杀shellcode](https://mp.weixin.qq.com/s/G1hmsDVTO2208Ymlia_ggQ)
7. [CS-notes](https://github.com/kluo84/CS-notes)--一系列CS的使用技巧笔记

CobaltStrike分析参考：
1. Volatility Plugin for Detecting Cobalt Strike Beacon. [blog](https://blogs.jpcert.or.jp/en/2018/08/volatility-plugin-for-detecting-cobalt-strike-beacon.html)|[Toolset](https://github.com/RomanEmelyanov/CobaltStrikeForensic)
2. [逆向分析Cobalt Strike安装后门](https://mp.weixin.qq.com/s/VHpcHzLc829hmQjrx1139A)
3. [分析cobaltstrike c2 协议](https://github.com/verctor/Cobalt_Homework)
4. Small [tool](https://github.com/Mkv4/cobaltstrike-authfile-decrypt) to decrypt a Cobalt Strike auth file

### 0x02 C2 Profiles

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  ALL   |   [Malleable-C2-Profiles](https://github.com/rsmudge/Malleable-C2-Profiles)  |   Official Malleable C2 Profiles  |  ![](https://img.shields.io/github/stars/rsmudge/Malleable-C2-Profiles)   | ![](https://img.shields.io/github/languages/top/rsmudge/Malleable-C2-Profiles) |
|  ALL   |   [Malleable-C2-Randomizer](https://github.com/bluscreenofjeff/Malleable-C2-Randomizer)  |   This script randomizes Cobalt Strike Malleable C2 profiles through the use of a metalanguage  |  ![](https://img.shields.io/github/stars/bluscreenofjeff/Malleable-C2-Randomizer)   | ![](https://img.shields.io/github/languages/top/bluscreenofjeff/Malleable-C2-Randomizer)|
|  ALL   |   [malleable-c2](https://github.com/threatexpress/malleable-c2)  | Cobalt Strike Malleable C2 Design and Reference Guide  |  ![](https://img.shields.io/github/stars/threatexpress/malleable-c2)   | ![](https://img.shields.io/github/languages/top/threatexpress/malleable-c2) |
|  ALL   |   [C2concealer](https://github.com/FortyNorthSecurity/C2concealer)  | C2concealer is a command line tool that generates randomized C2 malleable profiles for use in Cobalt Strike.  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/C2concealer)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/C2concealer) |


### 0x03 BOF

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  ALL   |   [BOF_Collection](https://github.com/rvrsh3ll/BOF_Collection)  |   Various Cobalt Strike BOFs  |  ![](https://img.shields.io/github/stars/rvrsh3ll/BOF_Collection)   | ![](https://img.shields.io/github/languages/top/rvrsh3ll/BOF_Collection)     |
|  ALL   |   [Situational Awareness BOF](https://github.com/trustedsec/CS-Situational-Awareness-BOF)  |   Its larger goal is providing a code example and workflow for others to begin making more BOF files. [Blog](https://www.trustedsec.com/blog/a-developers-introduction-to-beacon-object-files/)  |  ![](https://img.shields.io/github/stars/trustedsec/CS-Situational-Awareness-BOF)   | ![](https://img.shields.io/github/languages/top/trustedsec/CS-Situational-Awareness-BOF)     |
|  ALL   |   [QueueUserAPC_PPID](https://github.com/m57/cobaltstrike_bofs)  |   BOF spawns a process of your choice under a specified parent, and injects a provided shellcode file via QueueUserAPC().  |  ![](https://img.shields.io/github/stars/m57/cobaltstrike_bofs)   | ![](https://img.shields.io/github/languages/top/m57/cobaltstrike_bofs)     |


### 0x04 Aggressor Script

|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  BypassAV   |   [BypassAV](https://github.com/hack2fun/BypassAV)  |   用于快速生成免杀的可执行文件  |  ![](https://img.shields.io/github/stars/hack2fun/BypassAV)   | ![](https://img.shields.io/github/languages/top/hack2fun/BypassAV)     |
|  BypassAV   |   [scrun](https://github.com/k8gege/scrun)  |   BypassAV ShellCode Loader (Cobaltstrike/Metasploit) [Useage](https://www.cnblogs.com/k8gege/p/11223393.html)  |  ![](https://img.shields.io/github/stars/k8gege/scrun)   | ![](https://img.shields.io/github/languages/top/k8gege/scrun)     |
|  BypassAV   |   [beacon-c2-go](https://github.com/wahyuhadi/beacon-c2-go)  |   beacon-c2-go (Cobaltstrike/Metasploit)  |  ![](https://img.shields.io/github/stars/wahyuhadi/beacon-c2-go)   | ![](https://img.shields.io/github/languages/top/wahyuhadi/beacon-c2-go)  |
|  BypassAV   |   [C--Shellcode](https://github.com/OneHone/C--Shellcode)  |   python ShellCode Loader (Cobaltstrike&Metasploit)  [Useage](http://hone.cool/2019/11/26/%E5%85%8D%E6%9D%80-C-Shellcode%E5%8A%A0%E8%BD%BD%E5%99%A8/) |  ![](https://img.shields.io/github/stars/OneHone/C--Shellcode)   | ![](https://img.shields.io/github/languages/top/OneHone/C--Shellcode)  |
|  Recon   |   [red-team-scripts](https://github.com/threatexpress/red-team-scripts)  |   perform some rudimentary Windows host enumeration with Beacon built-in commands   |  ![](https://img.shields.io/github/stars/threatexpress/red-team-scripts)   | ![](https://img.shields.io/github/languages/top/threatexpress/red-team-scripts)     |
|  Recon   |   [aggressor-powerview](https://github.com/tevora-threat/aggressor-powerview)  |   All functions listed in the PowerView about page are included in this with all arguments for each function. [PowerView](https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1)   |  ![](https://img.shields.io/github/stars/tevora-threat/aggressor-powerview)   | ![](https://img.shields.io/github/languages/top/tevora-threat/aggressor-powerview)     |
|  Recon   |   [PowerView3-Aggressor](https://github.com/tevora-threat/PowerView3-Aggressor)  |   PowerView Aggressor Script for CobaltStrike [PowerView](https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1)   |  ![](https://img.shields.io/github/stars/tevora-threat/PowerView3-Aggressor)   | ![](https://img.shields.io/github/languages/top/tevora-threat/PowerView3-Aggressor)     |
|  Recon   |   [AggressorScripts](https://github.com/C0axx/AggressorScripts)  |   Sharphound-Aggressor- A user menu for the SharpHound ingestor  |  ![](https://img.shields.io/github/stars/C0axx/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/C0axx/AggressorScripts)     |
|  Exploit   |   [XSS-Fishing2-CS](https://github.com/TheKingOfDuck/XSS-Fishing2-CS)  |   鱼儿在cs上线后自动收杆 / Automatically stop fishing in javascript after the fish is hooked   |  ![](https://img.shields.io/github/stars/TheKingOfDuck/XSS-Fishing2-CS)   | ![](https://img.shields.io/github/languages/top/TheKingOfDuck/XSS-Fishing2-CS)     |
|  Exploit   |   [XSS-Phishing](https://github.com/timwhitez/XSS-Phishing)  |   xss钓鱼，cna插件配合php后端收杆   |  ![](https://img.shields.io/github/stars/timwhitez/XSS-Phishing)   | ![](https://img.shields.io/github/languages/top/timwhitez/XSS-Phishing)     |
|  Exploit   |   [custom_payload_generator](https://github.com/offsecginger/AggressorScripts)  |   CobaltStrike3.0+ --> creates various payloads for Cobalt Strike's Beacon. Current payload formats   |  ![](https://img.shields.io/github/stars/offsecginger/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/offsecginger/AggressorScripts)     |
|  Exploit   |   [CrossC2](https://github.com/gloxec/CrossC2)  |   CrossC2 framework - Generator CobaltStrike's cross-platform beacon   |  ![](https://img.shields.io/github/stars/gloxec/CrossC2)   | ![](https://img.shields.io/github/languages/top/gloxec/CrossC2)     |
|  Exploit   |   [GECC](https://github.com/Lz1y/GECC)  |   Go External C2 Client implementation for cobalt strike.   |  ![](https://img.shields.io/github/stars/Lz1y/GECC)   | ![](https://img.shields.io/github/languages/top/Lz1y/GECC)     |
|  Exploit   |   [Cobaltstrike-MS17-010](https://github.com/phink-team/Cobaltstrike-MS17-010)  |   ms17-010 exploit tool and scanner.   |  ![](https://img.shields.io/github/stars/phink-team/Cobaltstrike-MS17-010)   | ![](https://img.shields.io/github/languages/top/phink-team/Cobaltstrike-MS17-010)     |
|  Exploit   |   [AES-PowerShellCode](https://github.com/offsecginger/AES-PowerShellCode)  |   Standalone version of my AES Powershell payload for Cobalt Strike.   |  ![](https://img.shields.io/github/stars/offsecginger/AES-PowerShellCode)   | ![](https://img.shields.io/github/languages/top/offsecginger/AES-PowerShellCode)     |
|  Exploit   |   [SweetPotato_CS](https://github.com/Tycx2ry/SweetPotato_CS)  |   CobaltStrike4.x --> SweetPotato   |  ![](https://img.shields.io/github/stars/Tycx2ry/SweetPotato_CS)   | ![](https://img.shields.io/github/languages/top/Tycx2ry/SweetPotato_CS)     |
|  Exploit   |   [ElevateKit](https://github.com/rsmudge/ElevateKit)  |   privilege escalation exploits   |  ![](https://img.shields.io/github/stars/rsmudge/ElevateKit)   | ![](https://img.shields.io/github/languages/top/rsmudge/ElevateKit)     |
|  Exploit   |   [CVE-2018-4878](https://github.com/vysecurity/CVE-2018-4878)  |   CVE-2018-4878   |  ![](https://img.shields.io/github/stars/vysecurity/CVE-2018-4878)   | ![](https://img.shields.io/github/languages/top/vysecurity/CVE-2018-4878)     |
|  Exploit   |   [Aggressor-Scripts](https://github.com/RhinoSecurityLabs/Aggressor-Scripts)  |   The only current public is UACBypass, whose readme can be found inside its associated folder.   |  ![](https://img.shields.io/github/stars/RhinoSecurityLabs/Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/RhinoSecurityLabs/Aggressor-Scripts)     |
|  Exploit   |   [CVE_2020_0796_CNA](https://github.com/Rvn0xsy/CVE_2020_0796_CNA)  |   基于[ReflectiveDLLInjection](https://github.com/stephenfewer/ReflectiveDLLInjection)实现的本地提权漏洞   |  ![](https://img.shields.io/github/stars/Rvn0xsy/CVE_2020_0796_CNA)   | ![](https://img.shields.io/github/languages/top/Rvn0xsy/CVE_2020_0796_CNA)     |
|  Exploit   |   [DDEAutoCS](https://github.com/p292/DDEAutoCS)  |   setup our stage(d) Web Delivery attack   |  ![](https://img.shields.io/github/stars/p292/DDEAutoCS)   | ![](https://img.shields.io/github/languages/top/p292/DDEAutoCS)     |
|  Exploit   |   [geacon](https://github.com/darkr4y/geacon)  |   Implement CobaltStrike's Beacon in Go (can be used in Linux)   |  ![](https://img.shields.io/github/stars/darkr4y/geacon)   | ![](https://img.shields.io/github/languages/top/darkr4y/geacon)     |
|  Persistence   |   [persistence-aggressor-script](https://github.com/ZonkSec/persistence-aggressor-script)  |   persistence-aggressor-script   |  ![](https://img.shields.io/github/stars/ZonkSec/persistence-aggressor-script)   | ![](https://img.shields.io/github/languages/top/ZonkSec/persistence-aggressor-script)     |
|  Persistence   |   [Peinject_dll](https://github.com/m0ngo0se/Peinject_dll)  |   弃用winexec函数，使用shellexecute函数，程序流不在卡顿，达到真正的无感。  |  ![](https://img.shields.io/github/stars/m0ngo0se/Peinject_dll)   | ![](https://img.shields.io/github/languages/top/m0ngo0se/Peinject_dll)     |
|  Persistence   |   [TikiTorch](https://github.com/rasta-mouse/TikiTorch)  |   TikiTorch follows the same concept([CACTUSTORCH](https://github.com/vysecurity/CACTUSTORCH)) but has multiple types of process injection available, which can be specified by the user at compile time.   |  ![](https://img.shields.io/github/stars/rasta-mouse/TikiTorch)   | ![](https://img.shields.io/github/languages/top/rasta-mouse/TikiTorch)     |
|  Persistence   |   [CACTUSTORCH](https://github.com/mdsecactivebreach/CACTUSTORCH)  |   A JavaScript and VBScript shellcode launcher. This will spawn a 32 bit version of the binary specified and inject shellcode into it.   |  ![](https://img.shields.io/github/stars/mdsecactivebreach/CACTUSTORCH)   | ![](https://img.shields.io/github/languages/top/mdsecactivebreach/CACTUSTORCH)     |
|  Persistence   |   [UploadAndRunFrp](https://github.com/Ch1ngg/AggressorScript-UploadAndRunFrp)  |   上传frpc并且运行frpc   |  ![](https://img.shields.io/github/stars/Ch1ngg/AggressorScript-UploadAndRunFrp)   | ![](https://img.shields.io/github/languages/top/Ch1ngg/AggressorScript-UploadAndRunFrp)     |
|  Persistence   |   [persistence-aggressor-script](https://github.com/threatexpress/persistence-aggressor-script)  |   [Persistence Aggressor Script](https://zonksec.com/blog/persistence-aggressor-script/)   |  ![](https://img.shields.io/github/stars/threatexpress/persistence-aggressor-script)   | ![](https://img.shields.io/github/languages/top/threatexpress/persistence-aggressor-script)     |
|  Auxiliary   |   [Cobaltstrike-atexec](https://github.com/Rvn0xsy/Cobaltstrike-atexec)  |   利用任务计划进行横向，需要与135端口、445端口进行通信    |  ![](https://img.shields.io/github/stars/Rvn0xsy/Cobaltstrike-atexec)   | ![](https://img.shields.io/github/languages/top/Rvn0xsy/Cobaltstrike-atexec)     |
|  Auxiliary   |   [SharpCompile](https://github.com/SpiderLabs/SharpCompile)  |   SharpCompile is an aggressor script for Cobalt Strike which allows you to compile and execute C# in realtime.    |  ![](https://img.shields.io/github/stars/SpiderLabs/SharpCompile)   | ![](https://img.shields.io/github/languages/top/SpiderLabs/SharpCompile)     |
|  Auxiliary   |   [Quickrundown](https://github.com/icebearfriend/Quickrundown)  |   Utilizing QRD will allow an operator to quickly characterize what processes are both known and unknown on a host through the use of colors and notes about the processes displayed.     |  ![](https://img.shields.io/github/stars/icebearfriend/Quickrundown)   | ![](https://img.shields.io/github/languages/top/icebearfriend/Quickrundown)     |
|  Auxiliary   |   [Phant0m_cobaltstrike](https://github.com/p292/Phant0m_cobaltstrike)  |   This script walks thread stacks of Event Log Service process (spesific svchost.exe) and identify Event Log Threads to kill Event Log Service Threads. So the system will not be able to collect logs and at the same time the Event Log Service will appear to be running.  |  ![](https://img.shields.io/github/stars/p292/Phant0m_cobaltstrike)   | ![](https://img.shields.io/github/languages/top/p292/Phant0m_cobaltstrike)     |
|  Auxiliary   |   [NoPowerShell](https://github.com/bitsadmin/nopowershell)  |   NoPowerShell is a tool implemented in C# which supports executing PowerShell-like commands while remaining invisible to any PowerShell logging mechanisms.    |  ![](https://img.shields.io/github/stars/bitsadmin/nopowershell)   | ![](https://img.shields.io/github/languages/top/bitsadmin/nopowershell)     |
|  Auxiliary   |   [EventLogMaster](https://github.com/QAX-A-Team/EventLogMaster)  |   RDP EventLog Master  |  ![](https://img.shields.io/github/stars/QAX-A-Team/EventLogMaster)   | ![](https://img.shields.io/github/languages/top/QAX-A-Team/EventLogMaster)     |
|  Auxiliary   |   [ANGRYPUPPY](https://github.com/vysecurity/ANGRYPUPPY)  |  Bloodhound Attack Path Execution for Cobalt Strike    |  ![](https://img.shields.io/github/stars/vysecurity/ANGRYPUPPY)   | ![](https://img.shields.io/github/languages/top/vysecurity/ANGRYPUPPY)     |
|  Auxiliary   |   [CobaltStrike_Script_Wechat_Push](https://github.com/a1ices/CobaltStrike_Script_Wechat_Push)  |  上线微信提醒的插件,通过微信Server酱提醒    |  ![](https://img.shields.io/github/stars/a1ices/CobaltStrike_Script_Wechat_Push)   | ![](https://img.shields.io/github/languages/top/a1ices/CobaltStrike_Script_Wechat_Push)     |
|  Auxiliary   |   [CS-Aggressor-Scripts](https://github.com/secgroundzero/CS-Aggressor-Scripts)  |  slack and webhooks reminder    |  ![](https://img.shields.io/github/stars/secgroundzero/CS-Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/secgroundzero/CS-Aggressor-Scripts)     |
|  Auxiliary   |   [Aggressor-Scripts](https://github.com/skyleronken/Aggressor-Scripts)  |  surveying of powershell on targets (在对应的目标上检测powershell的相关信息)    |  ![](https://img.shields.io/github/stars/skyleronken/Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/skyleronken/Aggressor-Scripts)     |
|  Auxiliary   |   [cs-magik](https://github.com/tomsteele/cs-magik)  |  Implements an events channel and job queue using Redis for Cobalt Strike. |  ![](https://img.shields.io/github/stars/tomsteele/cs-magik)   | ![](https://img.shields.io/github/languages/top/tomsteele/cs-magik)     |
|  Auxiliary   |   [AggressorScripts](https://github.com/zer0yu/AggressorScripts)  | 查看进程的时候讲av进程标注为红色 |  ![](https://img.shields.io/github/stars/zer0yu/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/zer0yu/AggressorScripts)     |
|  Auxiliary   |   [Raven](https://github.com/xorrior/raven)  | CobaltStrike External C2 for Websockets |  ![](https://img.shields.io/github/stars/xorrior/raven)   | ![](https://img.shields.io/github/languages/top/xorrior/raven)     |
|  Auxiliary   |   [CobaltStrikeParser](https://github.com/Sentinel-One/CobaltStrikeParser)  | Python parser for CobaltStrike Beacon's configuration |  ![](https://img.shields.io/github/stars/Sentinel-One/CobaltStrikeParser)   | ![](https://img.shields.io/github/languages/top/Sentinel-One/CobaltStrikeParser)     |
|  Auxiliary   |   [fakelogonscreen](https://github.com/bitsadmin/fakelogonscreen)  | FakeLogonScreen is a utility to fake the Windows logon screen in order to obtain the user's password. |  ![](https://img.shields.io/github/stars/bitsadmin/fakelogonscreen)   | ![](https://img.shields.io/github/languages/top/bitsadmin/fakelogonscreen)     |
|  Auxiliary   |   [SyncDog](https://github.com/Lz1y/SyncDog)  | Make bloodhound sync with cobaltstrike. |  ![](https://img.shields.io/github/stars/Lz1y/SyncDog)   | ![](https://img.shields.io/github/languages/top/Lz1y/SyncDog)     |
|  Synthesis   |   [Erebus](https://github.com/DeEpinGh0st/Erebus)  |   CobaltStrike4.x --> Erebus CobaltStrike后渗透测试插件   |  ![](https://img.shields.io/github/stars/DeEpinGh0st/Erebus)   | ![](https://img.shields.io/github/languages/top/DeEpinGh0st/Erebus)     |
|  Synthesis   |   [Cobalt-Strike-Aggressor-Scripts](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts)  |   CobaltStrike后渗透测试插件集合 [Usage](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts/wiki/Usage)   |  ![](https://img.shields.io/github/stars/timwhitez/Cobalt-Strike-Aggressor-Scripts)   | ![](https://img.shields.io/github/languages/top/timwhitez/Cobalt-Strike-Aggressor-Scripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/bluscreenofjeff/AggressorScripts)  |   Aggressor scripts for use with Cobalt Strike 3.0+   |  ![](https://img.shields.io/github/stars/bluscreenofjeff/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/bluscreenofjeff/AggressorScripts)     |
|  Synthesis   |   [RedTeamTools](https://github.com/lengjibo/RedTeamTools)  |   RedTeamTools for use with Cobalt Strike   |  ![](https://img.shields.io/github/stars/lengjibo/RedTeamTools)   | ![](https://img.shields.io/github/languages/top/lengjibo/RedTeamTools)     |
|  Synthesis   |   [cobalt-arsenal](https://github.com/mgeeky/cobalt-arsenal)  |Aggressor Scripts for Cobalt Strike 4.0+   |  ![](https://img.shields.io/github/stars/mgeeky/cobalt-arsenal)   | ![](https://img.shields.io/github/languages/top/mgeeky/cobalt-arsenal)     |
|  Synthesis   |   [MoveKit](https://github.com/0xthirteen/MoveKit)  |The aggressor script handles payload creation by reading the template files for a specific execution type. [intro](https://www.4hou.com/posts/jO1y)   |  ![](https://img.shields.io/github/stars/0xthirteen/MoveKit)   | ![](https://img.shields.io/github/languages/top/0xthirteen/MoveKit)     |
|  Synthesis   |   [StayKit](https://github.com/0xthirteen/StayKit)  |The aggressor script handles payload creation by reading the template files for a specific execution type. [intro](https://www.4hou.com/posts/jO1y)   |  ![](https://img.shields.io/github/stars/0xthirteen/StayKit)   | ![](https://img.shields.io/github/languages/top/0xthirteen/StayKit)     |
|  Synthesis   |   [AggressorScripts](https://github.com/ramen0x3f/AggressorScripts)  | AggressorScripts  |  ![](https://img.shields.io/github/stars/ramen0x3f/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/ramen0x3f/AggressorScripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/harleyQu1nn/AggressorScripts)  | Collection of Aggressor scripts for Cobalt Strike 3.0+ pulled from multiple sources  |  ![](https://img.shields.io/github/stars/harleyQu1nn/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/harleyQu1nn/AggressorScripts)     |
|  Synthesis   |   [AggressorScripts](https://github.com/ramen0x3f/AggressorScripts)  | AggressorScripts  |  ![](https://img.shields.io/github/stars/ramen0x3f/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/ramen0x3f/AggressorScripts)     |
|  Synthesis   |   [Aggressor-VYSEC](https://github.com/vysecurity/Aggressor-VYSEC)  | Contains a bunch of CobaltStrike Aggressor Scripts  |  ![](https://img.shields.io/github/stars/vysecurity/Aggressor-VYSEC)   | ![](https://img.shields.io/github/languages/top/vysecurity/Aggressor-VYSEC)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | AggressorAssessor  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | AggressorAssessor  |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [aggressor-scripts](https://github.com/threatexpress/aggressor-scripts)  | Collection of Cobalt Strike Aggressor Scripts  |  ![](https://img.shields.io/github/stars/threatexpress/aggressor-scripts)   | ![](https://img.shields.io/github/languages/top/threatexpress/aggressor-scripts)     |
|  Synthesis   |   [Aggressor-scripts](https://github.com/Und3rf10w/Aggressor-scripts)  | This is just a random collection of Aggressor Scripts I've written for Cobalt Strike 3.x. (其中有一个debug脚本比较好用)  |  ![](https://img.shields.io/github/stars/Und3rf10w/Aggressor-scripts)   | ![](https://img.shields.io/github/languages/top/Und3rf10w/Aggressor-scripts)     |
|  Synthesis   |   [Aggressor-Script](https://github.com/rasta-mouse/Aggressor-Script)  | Collection of Aggressor Scripts for Cobalt Strike(主要包含了提权和权限维持脚本)  |  ![](https://img.shields.io/github/stars/rasta-mouse/Aggressor-Script)   | ![](https://img.shields.io/github/languages/top/rasta-mouse/Aggressor-Script)     |
|  Synthesis   |   [Aggressor-Script](https://github.com/QAX-A-Team/CobaltStrike-Toolset)  | Aggressor Script, Kit, Malleable C2 Profiles, External C2 and so on  |  ![](https://img.shields.io/github/stars/QAX-A-Team/CobaltStrike-Toolset)   | ![](https://img.shields.io/github/languages/top/QAX-A-Team/CobaltStrike-Toolset)     |
|  Synthesis   |   [aggressor_scripts_collection](https://github.com/michalkoczwara/aggressor_scripts_collection)  | Collection of various aggressor scripts for Cobalt Strike from awesome people. Will be sure to update this repo with credit to each person.  |  ![](https://img.shields.io/github/stars/michalkoczwara/aggressor_scripts_collection)   | ![](https://img.shields.io/github/languages/top/michalkoczwara/aggressor_scripts_collection)     |
|  Synthesis   |   [CobaltStrike-ToolKit](https://github.com/killswitch-GUI/CobaltStrike-ToolKit)  | googlesearch.profile and script related to AD.  |  ![](https://img.shields.io/github/stars/killswitch-GUI/CobaltStrike-ToolKit)   | ![](https://img.shields.io/github/languages/top/killswitch-GUI/CobaltStrike-ToolKit)     |
|  Synthesis   |   [Arsenal](https://github.com/Cliov/Arsenal)  | Cobalt Strike 3.13 Arsenal Kit  |  ![](https://img.shields.io/github/stars/Cliov/Arsenal)   | ![](https://img.shields.io/github/languages/top/Cliov/Arsenal)     |
|  Synthesis   |   [cobalt-arsenal](https://github.com/mgeeky/cobalt-arsenal)  | My collection of battle-tested Aggressor Scripts for Cobalt Strike 4.0+  |  ![](https://img.shields.io/github/stars/mgeeky/cobalt-arsenal)   | ![](https://img.shields.io/github/languages/top/mgeeky/cobalt-arsenal)     |
|  Synthesis   |   [aggressor_scripts](https://github.com/001SPARTaN/aggressor_scripts)  | code execution via DCOM;the privilege escalation techniques included in ElevateKit;etc.  |  ![](https://img.shields.io/github/stars/Cliov/Arsenal)   | ![](https://img.shields.io/github/languages/top/Cliov/Arsenal)     |
|  Synthesis   |   [aggressor_scripts](https://github.com/001SPARTaN/aggressor_scripts)  | code execution via DCOM;the privilege escalation techniques included in ElevateKit;etc.  |  ![](https://img.shields.io/github/stars/001SPARTaN/aggressor_scripts)   | ![](https://img.shields.io/github/languages/top/001SPARTaN/aggressor_scripts)     |
|  Synthesis   |   [aggressor](https://github.com/gaudard/scripts/tree/master/red-team/aggressor)  | creating tunnels with netsh; changed default to bit.ly redirect to mcdonalds;using powershell to kill parent process;  |  ![](https://img.shields.io/github/stars/001SPARTaN/aggressor_scripts)   | ![](https://img.shields.io/github/languages/top/001SPARTaN/aggressor_scripts)     |
|  Synthesis   |   [CobaltStrikeCNA](https://github.com/branthale/CobaltStrikeCNA)  | A collection of scripts - from various sources - see script for more info. |  ![](https://img.shields.io/github/stars/branthale/CobaltStrikeCNA)   | ![](https://img.shields.io/github/languages/top/branthale/CobaltStrikeCNA)     |
|  Synthesis   |   [AggressorScripts](https://github.com/oldb00t/AggressorScripts)  | Highlights selected processes from the ps command in beacon;Loads various aliases into beacon;sets a few defaults for scripts to be used later.. |  ![](https://img.shields.io/github/stars/oldb00t/AggressorScripts)   | ![](https://img.shields.io/github/languages/top/oldb00t/AggressorScripts)     |
|  Synthesis   |   [AggressorAssessor](https://github.com/FortyNorthSecurity/AggressorAssessor)  | 从C2生成到横向移动的全辅助脚本套件 |  ![](https://img.shields.io/github/stars/FortyNorthSecurity/AggressorAssessor)   | ![](https://img.shields.io/github/languages/top/FortyNorthSecurity/AggressorAssessor)     |
|  Synthesis   |   [AggressorCollection](https://github.com/invokethreatguy/AggressorCollection)  | Collection of awesome Cobalt Strike Aggressor Scripts. All credit due to the authors |  ![](https://img.shields.io/github/stars/invokethreatguy/AggressorCollection)   | ![](https://img.shields.io/github/languages/top/invokethreatguy/AggressorCollection)     |
|  Synthesis   |   [Cobaltstrike-Aggressor-Scripts-Collection](https://github.com/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)  | The collection of tested cobaltstrike aggressor scripts. |  ![](https://img.shields.io/github/stars/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)   | ![](https://img.shields.io/github/languages/top/bytecod3r/Cobaltstrike-Aggressor-Scripts-Collection)     |
|  Synthesis   |   [aggressorScripts](https://github.com/Matrix20085/aggressorScripts)  | CobaltStrike AggressorScripts for the lazy |  ![](https://img.shields.io/github/stars/Matrix20085/aggressorScripts)   | ![](https://img.shields.io/github/languages/top/Matrix20085/aggressorScripts)     |

### 0x05 Related Tools
|  Type   |   Name  |  Description   |  Popularity   |   Language  |
|:---:|:---:|:---:|:---:|:---:|
|  AntiCS   |   [cobaltstrike_brute](https://github.com/isafe/cobaltstrike_brute)  |   Cobalt Strike Team Server Password Brute Forcer  |  ![](https://img.shields.io/github/stars/isafe/cobaltstrike_brute)   | ![](https://img.shields.io/github/languages/top/isafe/cobaltstrike_brute)     |
|  Synthesis   |   [redi](https://github.com/taherio/redi)  | Automated script for setting up CobaltStrike redirectors (nginx reverse proxy, letsencrypt) |  ![](https://img.shields.io/github/stars/taherio/redi)   | ![](https://img.shields.io/github/languages/top/taherio/redi)     |









