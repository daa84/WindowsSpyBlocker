# Changelog

## 4.25.0 (2019/11/09)

* Update hosts for extra and spy rules
* Update IPs for extra, spy and update rules
* Add OS compatibility in manifest
* Update libs

## 4.24.1 (2019/10/09)

* Update hosts for extra rules
* Update IPs for extra, spy and update rules

## 4.24.0 (2019/09/30)

* Switch to [magefile](https://magefile.org) to build app
* Move [doc](doc)
* Go 1.12.10

## 4.23.1 (2019/09/01)

* Update hosts for update rules
* Update IPs for extra, spy and update rules

## 4.23.0 (2019/08/27)

* Add and publish [Chocolatey package](https://chocolatey.org/packages/windowsspyblocker) (Issue #143)
* Switch to GitHub Actions

## 4.22.3 (2019/08/03)

* Update hosts for extra and spy rules
* Update IPs for extra, spy and update rules

## 4.22.2 (2019/07/08)

* Update IPs for extra, spy and update rules (Issue #153 #154)

## 4.22.1 (2019/07/02)

* Update hosts for extra and spy rules
* Update IPs for extra and update rules

## 4.22.0 (2019/05/26)

* Update hosts for extra, spy and update rules
* Update IPs for extra, spy and update rules
* Wireshark 3.0.2
* Npcap 0.995
* Fix WindowsSpyBlocker NCSI HTTP Probe (Issue #128)
* Move virtualearth.net to extra (Issue #149)
* Switch to TravisCI

## 4.21.0 (2019/05/05)

* Handle IPv6 blocking for hosts (Issue #146)
* Add ability to perform DNS AAAA lookup test on hosts

## 4.20.0 (2019/05/02)

* Update IPs for extra, spy and update rules
* Go 1.12

## 4.19.1 (2019/04/02)

* Update hosts for extra rule
* Update IPs for extra, spy and update rules

## 4.19.0 (2019/03/02)

* Update hosts for extra and spy rules
* Update IPs for extra, spy and update rules
* Review data files header

## 4.18.4 (2019/01/28)

* Update hosts for extra and update rules
* Update IPs for extra and update rules
* Fix NCSI Microsoft probes

## 4.18.3 (2018/12/31)

* Update hosts for extra and update rules
* Update IPs for extra, spy and update rules

## 4.18.2 (2018/11/28)

* Fix typo

## 4.18.1 (2018/11/28)

* Update hosts for spy rules
* Update IPs for extra, spy and update rules
* SiSyPHuS BSI Windows 10 Telemetry data (Issue #123)
* Go 1.11.2

## 4.18.0 (2018/10/23)

* Fix incompatible rules
* Add menu to check for incompatible rules

## 4.17.1 (2018/10/23)

* Update hosts for extra, spy and update rules
* Update IPs for extra, spy and update rules
* Move `version.hybrid.api.here.com` to extra (Issue #120)
* Move 40.77.224, 65.52.108, 191.232.139.2 to update (Issue #119)
* Move 64.4.54 to extra

## 4.17.0 (2018/09/16)

* Update hosts for update rules
* Update IPs for extra and update rules
* Go 1.11
* Use [go mod](https://golang.org/cmd/go/#hdr-Module_maintenance) instead of `dep`

## 4.16.1 (2018/08/14)

* Update hosts for extra, spy and update rules
* Update IPs for extra, spy and update rules
* Update [wilcard domains](https://github.com/crazy-max/WindowsSpyBlocker/blob/master/app/settings.json#L120) settings (Issues #114 #115)
* Update some rules based on Microsoft endpoints docs (Issues #114 #115)
* Move `i1.services.social.microsoft.com` to extra (Issue #116)

## 4.16.0 (2018/07/09)

* Update hosts for extra and spy rules
* Update IPs for spy rules
* Fix iP.NF API

## 4.15.0 (2018/06/03)

* Remove dead hosts
* Add ability to perform DNS lookup test on hosts
* Fix hosts file parsing

## 4.14.0 (2018/06/02)

* Update hosts for extra, spy and update rules
* Update IPs for extra, spy and update rules
* Merge Windows 7/8.1/10 rules (Issues #30 #79 #112)

## 4.13.0 (2018/05/08)

* Update hosts for Windows 10 spy and update
* Move db*.wns.windows.com to update for Windows 10
* Update IPs for Windows 10 extra, spy and update
* Move 111.221.29.40 to spy for Windows 10
* Move 40.77.226 to update for Windows 10
* Update hosts for Windows 8.1 spy and update
* Update IPs for Windows 8.1 spy and update
* Move 40.77.226 to update for Windows 8.1
* Update hosts for Windows 7 spy and update
* Update IPs for Windows 7 spy and update
* Move 40.77.226 to update for Windows 7
* Write all Wireshark events
* More accurate tcpdump filter
* Sysmon CSV header malformed

## 4.12.1 (2018/04/09)

* Update hosts for Windows 10 extra and spy
* Update IPs for Windows 10 spy
* Update hosts for Windows 8.1 update
* Update IPs for Windows 8.1 extra, spy and update
* Update hosts for Windows 7 update
* Update IPs for Windows 7 extra, spy and update

## 4.12.0 (2018/03/27)

* Review Windows 10 lists (Issue #105)
* Move 40.77.229 to update for Windows 7
* Move 137.117.235.16, 191.237.208.126 to extra (Windows Defender)
* Remove 65.55.163 from Windows 8 extra (belongs to update)
* Refine IPs ranges
* Add option `useEmbeddedData` in config file to allow to use external data (Issue #75)
* Add menu to extract embedded data (Issue #75)
* Firewall test logs are not written if the directory does not exist
* Change the color of the menus for last items

## 4.11.0 (2018/03/03)

* Update hosts for Windows 10 extra and spy
* Update IPs for Windows 10 extra, spy and update
* Move 13.107.5, 51.141.32.51, 64.4.23, 65.55.163, 65.55.223, 104.45.18.177, 134.170.188.248, 157.55.56, 157.55.129.21 to extra for Windows 10
* Update hosts for Windows 8.1 spy and update
* Update IPs for Windows 8.1 extra, spy and update
* Move 13.79.239.69, 51.141.32.51, 64.4.23 to extra for Windows 8.1
* Move 13.78.230.134, 64.4.27.50 to update for Windows 8.1
* Update hosts for Windows 7 extra, spy and update
* Update IPs for Windows 7 extra, spy and update
* Move 13.79.239.69, 51.141.32.51, 64.4.23 to extra for Windows 7
* Manage IP range for testing
* Review IP analysis

## 4.10.4 (2018/02/10)

* Move 13.78.230.134 to update for Windows 10 (Issue #94)
* Move 13.79.239.69 to extra for Windows 10 (Issue #94)
* Typo in Windows 10 spy list (Issue #98)

## 4.10.3 (2018/01/24)

* Update hosts for Windows 10 extra and spy
* Update IPs for Windows 10 extra and spy
* Update hosts for Windows 8.1 spy and update
* Update IPs for Windows 8.1 extra and spy
* Update IPs for Windows 7 extra
* Go 1.9.3

## 4.10.2 (2017/12/24)

* Update hosts for Windows 10 spy
* Update IPs for Windows 10 extra and spy
* Update hosts for Windows 8.1 spy and update
* Update IPs for Windows 8.1 extra, spy and update
* Update hosts for Windows 7 extra
* Update IPs for Windows 7 extra

## 4.10.1 (2017/11/24)

* Move 13.68.87, 13.74.179 and 52.229.171 to update for Windows 10 (Issue #92)
* Move 13.68.87, 13.78.184, 52.229.171, 66.119.144 and 157.55.133 to update for Windows 8.1 (Issue #92)
* Move 66.119.144, 134.170.51 and 134.170.53 to update for Windows 7 (Issue #92)

## 4.10.0 (2017/11/22)

* New hosts for Windows 10 extra and spy
* New IPs for Windows 10 spy
* New hosts for Windows 8.1 spy
* New IPs for Windows 8.1 spy and update
* New IPs for Windows 7 spy
* Switch to [Golang Dep](https://github.com/golang/dep) as dependency manager
* Reduce dependencies and system calls to avoid heuristic detection (Issue #82)
* Use SetConsoleTitle instead of exec cmd
* Error while removing sysmon evtx file
* Remove unused code
* Go 1.9.1

## 4.9.0 (2017/10/17)

* New hosts for Windows 10 extra, spy and update
* New IPs for Windows 10 extra and spy
* New hosts for Windows 8.1 spy and update
* New IPs for Windows 8.1 extra, spy and update
* New IPs for Windows 7 spy and update
* Fix bug while extracting sysmon events
* Update libs

## 4.8.3 (2017/09/17)

* New hosts for Windows 10 spy
* New IPs for Windows 10 extra and spy
* New hosts for Windows 8.1 update
* New IPs for Windows 8.1 spy and update
* New hosts for Windows 7 spy
* Update libs
* Go 1.9

## 4.8.2 (2017/08/07)

* New hosts for Windows 10 spy
* New IPs for Windows 10 spy
* Move 40.114.241.141 to extra for Windows 10
* New hosts for Windows 8.1 spy and update
* New IPs for Windows 8.1 spy
* New IPs for Windows 7 spy

## 4.8.1 (2017/07/16)

* New hosts for Windows 10 extra and spy
* New IPs for Windows 10 spy and update
* Move 40.77.229 and 134.170.115.56 to update for Windows 10
* New hosts for Windows 8.1 extra
* New IPs for Windows 8.1 spy and update
* New hosts for Windows 7 extra and spy
* New IPs for Windows 7 spy
* Use go-evtx instead of LogParser (Issue #73)
* Merge version on upgrade

## 4.7.1 (2017/06/30)

* Add p2p data format (Issue #69)
* Add simplewall data format (Issue #68)
* Move 23.97.178.173 to extra for Windows 10 (Issue #67)
* Update go libs

## 4.6.1 (2017/06/17)

* New hosts for Windows 10 extra and spy 
* New IPs for Windows 10 extra and spy 
* Add IP range for Windows 10 spy (40.77.229)
* Move 64.4.54 to extra for Windows 10
* New hosts for Windows 8.1 spy and update
* New IPs for Windows 8.1 spy
* Move 64.4.54 to extra for Windows 8.1
* New IPs for Windows 7 spy
* Move 64.4.54 to extra for Windows 7
* Improve Proxifier log parser
* Improve menu

## 4.5.1 (2017/06/03)

* Move Test IPs in the Firewall menu to dev (Issue #65)
* Add offline Windows Update info in the wiki (Issue #64)
* Move 191.232.139 to update for Windows 7, 8.1 and 10 (Issue #15)

## 4.4.1 (2017/06/01)

* Typo on IP for Windows 10 spy
* Error parsing OpenWRT data (Issue #63)
* Move 66.119.144 to update for Windows 10 (Issue #62)
* Move 207.46 to extra for Windows 10 (Issue #15)

## 4.3.1 (2017/05/31)

* Again Windows Store cannot download apps (Issue #15)

## 4.3.0 (2017/05/28)

* Make compatible on 32bit platforms (Issue #61)

## 4.2.1 (2017/05/27)

* Windows Store cannot download apps (Issue #15)

## 4.2.0 (2017/05/23)

* Move Firewall and NCSI to the Telemetry parent menu
* Simplify the README

## 4.1.1 (2017/05/21)

* New hosts for Windows 10 extra, spy and update
* New IP for Windows 10 update
* New IPs for Windows 10 spy
* Typo in Windows 10 spy
* Add IP range for Windows 10 spy (65.55.252)
* New sub IP for Windows 10 extra (40.77.224)
* Typo in Windows 10 extra
* New hosts for Windows 8.1 spy and update
* New sub IP and IP for Windows 8.1 update (191.234.72)
* New sub IPs and IP for Windows 8.1 spy (13.79.239, 13.81.59)
* New hosts for Windows 7 spy and update
* New sub IPs and IP for Windows 7 spy (13.79.239, 51.141.32)
* Handle panic (Issue #58)
* Add menu to merge data (Issue #57)
* Missing print for firewall tests (Issue #56)
* Perform upgrade operations on new release (Issue #55)
* Add new release notification on startup (Issue #54)
* Update app.conf if keys are missing on update (Issue #53)
* Provide libs infos in the code (Issue #52)
* Null pointer on NCSI test (Issue #50)
* Add a menu on Wireshark to capture traffic (Issue #48)
* Separate IPs and domains for Proxifier rules
* Remove NCSI reg files
* Enhanced menu
* Upgrade Wireshark lib
* Duplicated diffs
* Code review

## 4.0.0 (2017/05/15)

* Unified console app made with Go (Issue #38)
* Add Glide dependency manager for Go
* Add Codacy review
* Add AppVeyor CI integration
* Add Go Report badge
* Standard code organization
* Move 131.253.61.0-131.253.61.255 to extra for Windows 8.1 (Issue #39)
* Move *.vo.msecnd.net to extra rules (Issue #37)

## 3.7.5 (2017/04/15)

* New hosts for Windows 10 spy and update
* New IP for Windows 10 update
* Add IP range for Windows 10 update (65.55.163) 
* New IPs for Windows 10 spy
* New sub IPs for Windows 10 spy (51.141.32, 52.178.178, 52.178.193, 52.178.223, 52.187.60)
* New sub IP for Windows 10 extra (13.107.21)
* New hosts for Windows 8.1 extra, spy and update
* Add IP range for Windows 8.1 update (65.55.163)
* New sub IPs for Windows 8.1 spy (51.141.32, 52.178.178, 52.178.193, 52.178.223, 52.187.60, 64.233.164, 64.233.166)
* New hosts for Windows 7 spy and update
* New sub IPs for Windows 7 spy (40.118.106, 52.178.178, 52.178.193, 52.178.223, 52.187.60)
* Move crl.microsoft.com to extra rules for Windows 7 (Issue #19)

## 3.7.4 (2017/03/07)

* New hosts for Windows 10 spy
* Add IPs range for Windows 10 spy (131.253.14, 157.55.109)
* New sub IP for Windows 10 update (131.253.33)
* New hosts for Windows 8.1 extra and update
* New sub IP for Windows 8.1 extra (40.118.106)
* New IP for Windows 8.1 update
* New host for Windows 7 update
* Misplaced IPs blocking Windows update bug (Issue #33)
* Skype problem (Issue #32)
* Move 134.170.185.* to extra rules (Issue #31)
* Move 48.118.103 and 65.52.108 to extra rules for Windows 10
* Missing IP in OpenWRT extra rules (Windows 8.1 and 10)

## 3.7.3 (2017/01/23)

* Move answers.microsoft.com to extra rules
* choice.microsoft.com was not completely moved to extra rules

## 3.7.2 (2017/01/22)

* New hosts for Windows 10 spy and update
* Add IP range for Windows 10 spy (134.170.111)
* New sub IP for Windows 10 spy (52.164.240)
* New IPs for Windows 10 spy
* New hosts for Windows 8.1 update
* Move officeclient.microsoft.com to extra rules (Issue #29)
* Move m.hotmail.com to extra rules (Issue #28)

## 3.7.1 (2016/12/19)

* New hosts for Windows 10 spy
* New sub IPs for Windows 10 spy (40.113.10, 40.115.1, 52.178.151, 65.52.26, 104.46.38, 134.170.120) 
* New sub IP for Windows 8.1 update (191.232.80)

## 3.7.0 (2016/11/28)

* New hosts for Windows 10 spy and update
* Add IPs range for Windows 10 spy (40.77.229, 134.170.106)
* New sub IPs for Windows 10 spy (23.97.61, 23.99.121, 40.76.1, 40.117.144, 65.52.219, 104.210.212, 134.170.111, 134.170.120, 157.55.109, 191.237.218, 207.46.194)
* Move spy IP rule to update for Windows 10 (157.55.133.204)
* New hosts for Windows 7 update
* New sub IPs for Windows 7 spy (52.164.241, 52.178.147)
* Fix undefined index
* Fix tmp file creation
* Downloads from Xbox Store broken (Issue #24)
* OpenWRT dnsmasq.conf alternative method (Issue #20)

## 3.6.0 (2016/11/06)

* New hosts for Windows 10 spy
* Add IPs range for Windows 10 update (65.55.138)
* Add IPs range for Windows 10 spy (40.77.226, 64.4.54, 65.52.100)
* New sub IPs for Windows 10 spy (13.76.218, 40.77.229, 52.178.147, 137.170.51, 134.170.115)
* New hosts for Windows 8.1 update
* Add IPs range for Windows 8.1 update (65.55.138, 134.170.51)
* New sub IPs for Windows 8.1 update (134.170.115)
* New sub IPs for Windows 8.1 spy (40.77.226, 52.164.240, 52.164.241, 52.178.147, 52.178.151)
* New sub IPs for Windows 7 spy (40.77.226, 52.164.240, 52.178.151)
* Update Proxifier script exceptions
* Windows 10 Store Blocked (Issue #22)

## 3.5.0 (2016/09/18)

* New hosts and firewall rules
* 2 Spy entries are maybe incorrect (Issue #19)

## 3.4.4 (2016/08/02)

* New hosts and firewall rules

## 3.4.3 (2016/07/24)

* New hosts and firewall rules

## 3.4.2 (2016/07/12)

* New hosts and firewall rules

## 3.4.1 (2016/07/03)

* New hosts and firewall rules

## 3.4.0 (2016/06/24)

* New hosts and firewall rules
* Scripts more verbose
* Skip diff if file not exist

## 3.3.1 (2016/06/18)

* New hosts and firewall rules
* Fix login problem on Windows Store (Issue #15)

## 3.3.0 (2016/06/12)

* New hosts and firewall rules
* Resolve domains history via ThreatCrowd
* Manage CDNs
* Diffs reports in CSV format
* Add additional whois and resolutions API

## 3.2.0 (2016/06/08)

* Add third digit to release version for rules updates only
* New hosts and firewall rules
* Better diffs order
* Update and separate OpenWrt dnsmasq / iptables files

## 3.1 (2016/06/07)

* Add Windows 7 and Windows 8.1 hosts and firewall rules (Issue #1)
* Add Wireshark script to extract log and generate CSV (Issue #6)
* Bug spy rule blocking Windows update (Issue #14)
* Add diff script to compare current firewall rules / hosts with generated CSVs
* New hosts and firewall rules

## 3.0 (2016/06/03)

* Add Sysmon, Proxifier, Wireshark capture method in the [Wiki](../../wiki) (Issue #11)
* Enhancement for firewall script (Issue #2)
* Separate rules and scripts in distinct folders
* New hosts and firewall rules
* Add capture logs in CSV files
* Add Sysmon script (install / uninstall / extract event log)
* Add Proxifier script (extract log)

## 2.7 (2016/05/27)

* Add NCSI alternative probe (Issue #9)
* Allow Network Connectivity Status Indicator (Issue #8)
* Windows Update was blocked unintentional. (Issue #7)
* New firewall rules
* Add Windows Update firewall rules
* New hosts
* Add IPs to Proxifier rules (copy from firewall rules)
* Remove reverse DNS lookup hosts
* Update [FAQ](../../wiki/FAQ)

## 2.6 (2016/05/22)

* New firewall rules
* New extra host
* Add check on IP range
* Rename hosts files

## 2.5 (2016/05/16)

* Add instructions to use blacklist domains with DNSCrypt (Issue #5)
* Add DNSCrypt blacklisted domains files
* Rename firewall and proxifier files according to operating system
* New firewall rules
* Move rules to extra for Proxifier and DNSCrypt

## 2.4 (2016/05/16)

* New firewall rules
* New extra hosts
* Move `204.79.197.200` to extra firewall rules (Bing)
* Add relative information about firewall IP addresses in `firewallTestIPs.csv` file

## 2.3 (2016/05/15)

* New firewall rules
* New hosts
* Add extra firewall rules in a separate file
* Add test IPs menu in firewall script

## 2.2 (2016/05/15)

* New firewall rules
* Add logo (credit to DWS)

## 2.1 (2016/05/14)

* New firewall rules since Microsoft Patch Tuesday May 2016

## 2.0 (2016/05/14)

* Update hosts Windows Extra
* Add Firewall rules

## 1.5 (2016/03/29)

* New hosts since KB3140768
* Add third party applications blocking file

## 1.4 (2016/03/06)

* New hosts since KB3135173
* Add Windows Update block rules

## 1.3 (2016/03/04)

* Initial version
