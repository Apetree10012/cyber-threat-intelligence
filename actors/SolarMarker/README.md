# SolarMarker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SolarMarker](https://vuldb.com/?actor.solarmarker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.solarmarker](https://vuldb.com/?actor.solarmarker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SolarMarker:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [DE](https://vuldb.com/?country.de)
* ...

There are 30 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SolarMarker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.120.233.92](https://vuldb.com/?ip.37.120.233.92) | no-rdns.m247.com | - | High
2 | [37.120.237.251](https://vuldb.com/?ip.37.120.237.251) | - | - | High
3 | [45.42.201.248](https://vuldb.com/?ip.45.42.201.248) | - | - | High
4 | [46.30.188.221](https://vuldb.com/?ip.46.30.188.221) | 46.30.188.221.static.quadranet.com | - | High
5 | [77.105.166.247](https://vuldb.com/?ip.77.105.166.247) | fleet-impulse.aeza.network | - | High
6 | [78.135.73.148](https://vuldb.com/?ip.78.135.73.148) | - | - | High
7 | ... | ... | ... | ...

There are 23 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SolarMarker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SolarMarker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/api/baskets/{name}` | High
3 | File | `/api2/html/` | Medium
4 | File | `/apiadmin/notice/add` | High
5 | File | `/classes/master.php?f=delete_order` | High
6 | File | `/cloud_config/router_post/register` | High
7 | File | `/debug/pprof` | Medium
8 | File | `/ecommerce/support_ticket` | High
9 | File | `/etc/gsissh/sshd_config` | High
10 | File | `/forms/nslookupHandler` | High
11 | File | `/Forms/tools_test_1` | High
12 | File | `/forum/away.php` | High
13 | File | `/forum/PostPrivateMessage` | High
14 | File | `/h/autoSaveDraft` | High
15 | File | `/h/calendar` | Medium
16 | File | `/holiday.php` | Medium
17 | File | `/home/cavesConsole` | High
18 | File | `/include/chart_generator.php` | High
19 | File | `/index.php` | Medium
20 | File | `/lam/tmp/` | Medium
21 | File | `/librarian/bookdetails.php` | High
22 | File | `/login/index.php` | High
23 | File | `/log_download.cgi` | High
24 | File | `/manager?action=getlogcat` | High
25 | File | `/mgmt/tm/util/bash` | High
26 | File | `/modules/profile/index.php` | High
27 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
28 | File | `/news.dtl.php` | High
29 | File | `/oauth/idp/.well-known/openid-configuration` | High
30 | File | `/out.php` | Medium
31 | File | `/p1/p2/:name` | Medium
32 | File | `/param.file.tgz` | High
33 | File | `/patient/appointment.php` | High
34 | File | `/php-opos/index.php` | High
35 | File | `/proc/<PID>/mem` | High
36 | File | `/protocol/iscgwtunnel/uploadiscgwrouteconf.php` | High
37 | File | `/ptms/?page=user` | High
38 | File | `/Service/ImageStationDataService.asmx` | High
39 | File | `/setup/finish` | High
40 | File | `/spip.php` | Medium
41 | File | `/sysmanage/importconf.php` | High
42 | File | `/template/edit` | High
43 | File | `/uncpath/` | Medium
44 | File | `/upload/file.php` | High
45 | File | `/user/s.php` | Medium
46 | File | `/usr/bin/at` | Medium
47 | ... | ... | ...

There are 408 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/184/solarmarker-malware-iocs/
* https://ioc.exchange/@squiblydoo@infosec.exchange/110854242511709508
* https://ioc.exchange/@squiblydoo@infosec.exchange/110952627273483306
* https://threatfox.abuse.ch
* https://tria.ge/210824-j7r4atcshe/behavioral2
* https://twitter.com/SquiblydooBlog/status/1498447061628379140
* https://twitter.com/SquiblydooBlog/status/1660782805687865344
* https://twitter.com/SquiblydooBlog/status/1671556028226207746

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
