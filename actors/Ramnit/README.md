# Ramnit - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ramnit](https://vuldb.com/?actor.ramnit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ramnit](https://vuldb.com/?actor.ramnit)

## Campaigns

The following _campaigns_ are known and can be associated with Ramnit:

* Azorult

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ramnit:

* US
* ES
* RU
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ramnit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 3.64.163.50 | ec2-3-64-163-50.eu-central-1.compute.amazonaws.com | - | Medium
2 | 5.45.82.108 | - | - | High
3 | 5.45.118.216 | - | - | High
4 | 5.45.120.46 | s052d782e.fastvps-server.com | - | High
5 | 5.45.124.183 | sfc6c0e42.fastvps-server.com | - | High
6 | 5.45.147.152 | - | - | High
7 | 5.101.159.26 | - | - | High
8 | 5.180.102.147 | 377961.msk-kvm.ru | - | High
9 | 13.90.196.81 | - | - | High
10 | 13.107.21.200 | - | - | High
11 | 18.213.250.117 | ec2-18-213-250-117.compute-1.amazonaws.com | - | Medium
12 | 18.215.128.143 | ec2-18-215-128-143.compute-1.amazonaws.com | - | Medium
13 | 23.5.233.23 | a23-5-233-23.deploy.static.akamaitechnologies.com | - | High
14 | 23.46.56.194 | a23-46-56-194.deploy.static.akamaitechnologies.com | - | High
15 | 23.46.57.84 | a23-46-57-84.deploy.static.akamaitechnologies.com | - | High
16 | 23.46.57.232 | a23-46-57-232.deploy.static.akamaitechnologies.com | - | High
17 | 23.46.57.251 | a23-46-57-251.deploy.static.akamaitechnologies.com | - | High
18 | 23.64.109.30 | a23-64-109-30.deploy.static.akamaitechnologies.com | - | High
19 | 23.196.65.196 | a23-196-65-196.deploy.static.akamaitechnologies.com | - | High
20 | 23.218.130.41 | a23-218-130-41.deploy.static.akamaitechnologies.com | - | High
21 | 31.44.184.117 | - | - | High
22 | 34.98.99.30 | 30.99.98.34.bc.googleusercontent.com | - | Medium
23 | 34.102.136.180 | 180.136.102.34.bc.googleusercontent.com | - | Medium
24 | 34.197.76.50 | ec2-34-197-76-50.compute-1.amazonaws.com | - | Medium
25 | 34.225.182.233 | ec2-34-225-182-233.compute-1.amazonaws.com | - | Medium
26 | 35.188.161.42 | 42.161.188.35.bc.googleusercontent.com | - | Medium
27 | 35.224.11.86 | 86.11.224.35.bc.googleusercontent.com | - | Medium
28 | 39.107.34.197 | - | - | High
29 | 45.118.145.96 | - | - | High
30 | 46.17.47.67 | fxchfjhtftfr.net | - | High
31 | 46.161.40.50 | hosting-by.ankas-group.net | - | High
32 | 46.165.220.141 | - | - | High
33 | 46.165.220.142 | - | - | High
34 | 46.165.220.143 | - | - | High
35 | 46.165.220.144 | - | - | High
36 | 46.165.220.145 | - | - | High
37 | 46.165.220.146 | - | - | High
38 | ... | ... | ... | ...

There are 149 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Ramnit. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ramnit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin.php` | High
2 | File | `/admin/imageslider/file.php` | High
3 | File | `/cgi-bin/luci` | High
4 | File | `/cgi-bin/viewcert` | High
5 | File | `/core/vb/vurl.php` | High
6 | File | `/etc/ldap.conf` | High
7 | File | `/importTool/preview` | High
8 | File | `/mods/_core/courses/users/create_course.php` | High
9 | File | `/phppath/php` | Medium
10 | File | `/plugins/Dashboard/Controller.php` | High
11 | File | `/server-status` | High
12 | File | `/uncpath/` | Medium
13 | File | `adclick.php` | Medium
14 | File | `addentry.php` | Medium
15 | File | `add_comment.php` | High
16 | File | `admin-ajax.php` | High
17 | File | `admin.php` | Medium
18 | ... | ... | ...

There are 151 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0402-0409.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0813-0820.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0903-0910.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-0924-1001.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1015-1022.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1022-1029.html
* https://github.com/firehol/blocklist-ipsets/blob/master/bambenek_ramnit.ipset
* https://research.checkpoint.com/2018/new-ramnit-campaign-spreads-azorult-malware/
* https://research.checkpoint.com/2018/ramnits-network-proxy-servers/
* https://twitter.com/bit_dam/status/1280975679354556429

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!