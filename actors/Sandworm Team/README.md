# Sandworm Team - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandworm Team](https://vuldb.com/?actor.sandworm_team). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandworm_team](https://vuldb.com/?actor.sandworm_team)

## Campaigns

The following _campaigns_ are known and can be associated with Sandworm Team:

* BlackEnergy
* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandworm Team:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sandworm Team.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.32.230](https://vuldb.com/?ip.5.9.32.230) | static.230.32.9.5.clients.your-server.de | BlackEnergy | High
2 | [5.61.38.31](https://vuldb.com/?ip.5.61.38.31) | - | BlackEnergy | High
3 | [5.79.80.166](https://vuldb.com/?ip.5.79.80.166) | - | BlackEnergy | High
4 | [5.133.8.46](https://vuldb.com/?ip.5.133.8.46) | d8046.artnet.gda.pl | - | High
5 | [5.149.254.114](https://vuldb.com/?ip.5.149.254.114) | mail1.auditoriavanzada.info | BlackEnergy | High
6 | [5.255.87.39](https://vuldb.com/?ip.5.255.87.39) | - | BlackEnergy | High
7 | [31.210.111.154](https://vuldb.com/?ip.31.210.111.154) | . | BlackEnergy | High
8 | [37.220.34.56](https://vuldb.com/?ip.37.220.34.56) | - | BlackEnergy | High
9 | [45.56.93.83](https://vuldb.com/?ip.45.56.93.83) | li895-83.members.linode.com | Ukraine | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandworm Team_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm Team. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/alphaware/summary.php` | High
8 | File | `/api/` | Low
9 | File | `/api/admin/store/product/list` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/cron/settings/setJob/` | High
12 | File | `/api/stl/actions/search` | High
13 | File | `/api/sys/login` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/api/trackedEntityInstances` | High
16 | File | `/api/v2/cli/commands` | High
17 | File | `/aux` | Low
18 | File | `/bin/ate` | Medium
19 | File | `/bitrix/admin/ldap_server_edit.php` | High
20 | File | `/boat/login.php` | High
21 | File | `/booking/show_bookings/` | High
22 | File | `/bsms_ci/index.php/book` | High
23 | File | `/cgi-bin` | Medium
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/changePassword` | High
26 | File | `/Content/Template/root/reverse-shell.aspx` | High
27 | File | `/dashboard/add-blog.php` | High
28 | File | `/data/remove` | Medium
29 | File | `/debug/pprof` | Medium
30 | File | `/DXR.axd` | Medium
31 | File | `/ecshop/admin/template.php` | High
32 | File | `/enginemanager/server/user/delete.htm` | High
33 | File | `/env` | Low
34 | File | `/forum/away.php` | High
35 | File | `/goform/SetFirewallCfg` | High
36 | File | `/group1/uploa` | High
37 | File | `/index.php` | Medium
38 | File | `/j_security_check` | High
39 | File | `/medicines/profile.php` | High
40 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
41 | File | `/novel/bookSetting/list` | High
42 | File | `/out.php` | Medium
43 | File | `/owa/auth/logon.aspx` | High
44 | File | `/php-sms/admin/?page=user/manage_user` | High
45 | File | `/probe?target` | High
46 | File | `/reservation/add_message.php` | High
47 | File | `/resources//../` | High
48 | ... | ... | ...

There are 417 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.google/threat-analysis-group/ukraine-remains-russias-biggest-cyber-focus-in-2023/
* https://ddanchev.blogspot.com/2022/06/exclusive-exposing-grus-unit-74455.html
* https://media.defense.gov/2020/May/28/2002306626/-1/-1/0/CSA%20Sandworm%20Actors%20Exploiting%20Vulnerability%20in%20Exim%20Transfer%20Agent%2020200528.pdf
* https://otx.alienvault.com/pulse/62552abdd7e44d9aba08636d
* https://www.threatminer.org/report.php?q=BlackEnergy2_Plugins_Router.pdf&y=2014
* https://www.welivesecurity.com/2016/01/03/blackenergy-sshbeardoor-details-2015-attacks-ukrainian-news-media-electric-industry/
* https://www.welivesecurity.com/2016/12/13/rise-telebots-analyzing-disruptive-killdisk-attacks/
* https://www.welivesecurity.com/2017/06/30/telebots-back-supply-chain-attacks-against-ukraine/
* https://www.welivesecurity.com/2018/10/11/new-telebots-backdoor-linking-industroyer-notpetya/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
