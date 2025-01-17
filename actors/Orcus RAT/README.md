# Orcus RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Orcus RAT](https://vuldb.com/?actor.orcus_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.orcus_rat](https://vuldb.com/?actor.orcus_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Orcus RAT:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Orcus RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.54.107.33](https://vuldb.com/?ip.1.54.107.33) | - | - | High
2 | [1.54.107.38](https://vuldb.com/?ip.1.54.107.38) | - | - | High
3 | [1.54.172.244](https://vuldb.com/?ip.1.54.172.244) | - | - | High
4 | [2.58.56.242](https://vuldb.com/?ip.2.58.56.242) | 2.58.56.242.powered.by.rdp.sh | - | High
5 | [3.129.187.220](https://vuldb.com/?ip.3.129.187.220) | ec2-3-129-187-220.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.133.207.110](https://vuldb.com/?ip.3.133.207.110) | ec2-3-133-207-110.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.137.146.78](https://vuldb.com/?ip.3.137.146.78) | ec2-3-137-146-78.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.143.239.116](https://vuldb.com/?ip.3.143.239.116) | ec2-3-143-239-116.us-east-2.compute.amazonaws.com | - | Medium
9 | [5.78.108.0](https://vuldb.com/?ip.5.78.108.0) | static.0.108.78.5.clients.your-server.de | - | High
10 | [13.53.37.168](https://vuldb.com/?ip.13.53.37.168) | ec2-13-53-37-168.eu-north-1.compute.amazonaws.com | - | Medium
11 | [15.235.3.1](https://vuldb.com/?ip.15.235.3.1) | ip1.ip-15-235-3.net | - | High
12 | [16.170.253.123](https://vuldb.com/?ip.16.170.253.123) | ec2-16-170-253-123.eu-north-1.compute.amazonaws.com | - | Medium
13 | [18.117.142.49](https://vuldb.com/?ip.18.117.142.49) | ec2-18-117-142-49.us-east-2.compute.amazonaws.com | - | Medium
14 | [18.192.31.165](https://vuldb.com/?ip.18.192.31.165) | ec2-18-192-31-165.eu-central-1.compute.amazonaws.com | - | Medium
15 | [20.89.177.186](https://vuldb.com/?ip.20.89.177.186) | - | - | High
16 | [27.124.3.19](https://vuldb.com/?ip.27.124.3.19) | - | - | High
17 | [27.124.4.200](https://vuldb.com/?ip.27.124.4.200) | - | - | High
18 | [27.124.6.248](https://vuldb.com/?ip.27.124.6.248) | - | - | High
19 | [31.44.184.52](https://vuldb.com/?ip.31.44.184.52) | - | - | High
20 | [31.173.170.243](https://vuldb.com/?ip.31.173.170.243) | - | - | High
21 | [39.44.128.21](https://vuldb.com/?ip.39.44.128.21) | - | - | High
22 | [42.114.153.12](https://vuldb.com/?ip.42.114.153.12) | - | - | High
23 | [42.114.153.115](https://vuldb.com/?ip.42.114.153.115) | - | - | High
24 | ... | ... | ... | ...

There are 91 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Orcus RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Orcus RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Key=PhoneRequestAuthorization` | High
2 | File | `/admin/access` | High
3 | File | `/admin/index.html` | High
4 | File | `/api/RecordingList/DownloadRecord?file=` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/bin/login` | Medium
7 | File | `/configs/application.ini` | High
8 | File | `/etc/gsissh/sshd_config` | High
9 | File | `/home` | Low
10 | File | `/public` | Low
11 | File | `/rapi/read_url` | High
12 | File | `/scripts/unlock_tasks.php` | High
13 | File | `/system/user/modules/mod_users/controller.php` | High
14 | File | `/whbs/?page=manage_account` | High
15 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
16 | File | `admin.php/comments/batchdel/` | High
17 | File | `admin.php/User/del/ucode/` | High
18 | File | `admin.php?c=a_adminuser&a=add&run=1` | High
19 | File | `admin.php?m=Member&a=adminaddsave` | High
20 | ... | ... | ...

There are 164 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/1.54.107.38
* https://search.censys.io/hosts/1.54.172.244
* https://search.censys.io/hosts/15.235.3.1
* https://search.censys.io/hosts/16.170.253.123
* https://search.censys.io/hosts/27.124.6.248
* https://search.censys.io/hosts/39.44.128.21
* https://search.censys.io/hosts/42.114.153.12
* https://search.censys.io/hosts/42.114.153.115
* https://search.censys.io/hosts/45.204.82.82
* https://search.censys.io/hosts/45.204.82.103
* https://search.censys.io/hosts/61.92.130.64
* https://search.censys.io/hosts/85.209.176.26
* https://search.censys.io/hosts/88.119.171.56
* https://search.censys.io/hosts/89.208.105.120
* https://search.censys.io/hosts/104.168.163.193
* https://search.censys.io/hosts/116.103.214.233
* https://search.censys.io/hosts/138.197.66.62
* https://search.censys.io/hosts/146.235.217.116
* https://search.censys.io/hosts/150.107.2.102
* https://search.censys.io/hosts/154.243.252.14
* https://search.censys.io/hosts/154.244.157.117
* https://search.censys.io/hosts/154.244.175.192
* https://search.censys.io/hosts/154.244.248.129
* https://search.censys.io/hosts/154.245.132.20
* https://search.censys.io/hosts/154.245.216.63
* https://search.censys.io/hosts/154.245.225.202
* https://search.censys.io/hosts/183.80.186.171
* https://search.censys.io/hosts/183.80.187.20
* https://search.censys.io/hosts/185.196.10.32
* https://search.censys.io/hosts/188.27.189.65
* https://search.censys.io/hosts/194.26.192.11
* https://search.censys.io/hosts/194.87.216.52
* https://search.censys.io/hosts/194.233.31.117
* https://search.censys.io/hosts/197.119.113.44
* https://search.censys.io/hosts/197.119.135.90
* https://search.censys.io/hosts/206.84.153.217
* https://search.censys.io/hosts/206.84.154.119
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.software.product%3A+orcus+and+not+labels%3A+tarpit
* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/07b742c9303e04be588f20f51d68828cae04a1af02cb6d09a9d935007dbb4906/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
