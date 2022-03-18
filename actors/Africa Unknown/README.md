# Africa Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Africa Unknown](https://vuldb.com/?actor.africa_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.africa_unknown](https://vuldb.com/?actor.africa_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Africa Unknown:

* [NL](https://vuldb.com/?country.nl)
* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Africa Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.23.158.50](https://vuldb.com/?ip.2.23.158.50) | a2-23-158-50.deploy.static.akamaitechnologies.com | - | High
2 | [3.94.40.55](https://vuldb.com/?ip.3.94.40.55) | ec2-3-94-40-55.compute-1.amazonaws.com | - | Medium
3 | [3.94.72.89](https://vuldb.com/?ip.3.94.72.89) | ec2-3-94-72-89.compute-1.amazonaws.com | - | Medium
4 | [5.11.82.213](https://vuldb.com/?ip.5.11.82.213) | - | - | High
5 | [5.62.40.217](https://vuldb.com/?ip.5.62.40.217) | r-217.40.62.5.ptr.avast.com | - | High
6 | [8.241.78.254](https://vuldb.com/?ip.8.241.78.254) | - | - | High
7 | [8.248.5.254](https://vuldb.com/?ip.8.248.5.254) | - | - | High
8 | [23.39.160.11](https://vuldb.com/?ip.23.39.160.11) | a23-39-160-11.deploy.static.akamaitechnologies.com | - | High
9 | [23.39.160.19](https://vuldb.com/?ip.23.39.160.19) | a23-39-160-19.deploy.static.akamaitechnologies.com | - | High
10 | [23.39.160.59](https://vuldb.com/?ip.23.39.160.59) | a23-39-160-59.deploy.static.akamaitechnologies.com | - | High
11 | [23.39.160.72](https://vuldb.com/?ip.23.39.160.72) | a23-39-160-72.deploy.static.akamaitechnologies.com | - | High
12 | [23.41.187.13](https://vuldb.com/?ip.23.41.187.13) | a23-41-187-13.deploy.static.akamaitechnologies.com | - | High
13 | [23.62.46.8](https://vuldb.com/?ip.23.62.46.8) | a23-62-46-8.deploy.static.akamaitechnologies.com | - | High
14 | [34.98.99.30](https://vuldb.com/?ip.34.98.99.30) | 30.99.98.34.bc.googleusercontent.com | - | Medium
15 | [34.104.35.123](https://vuldb.com/?ip.34.104.35.123) | 123.35.104.34.bc.googleusercontent.com | - | Medium
16 | [38.132.109.186](https://vuldb.com/?ip.38.132.109.186) | - | - | High
17 | [41.78.118.2](https://vuldb.com/?ip.41.78.118.2) | - | - | High
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Africa Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Africa Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/account/details.php` | High
5 | File | `/admin.php` | Medium
6 | File | `/admin/user/manage` | High
7 | File | `/anony/mjpg.cgi` | High
8 | File | `/artist-display.php` | High
9 | File | `/customer_demo/index2.html` | High
10 | File | `/file?action=download&file` | High
11 | File | `/home/httpd/cgi-bin/cgi.cgi` | High
12 | File | `/html/includes/graphs/port/mac_acc_total.inc.php` | High
13 | File | `/inc/subscriber_list.php` | High
14 | File | `/install/index.php` | High
15 | File | `/layout/class.xblogcomment.php` | High
16 | File | `/LEPTON_stable_2.2.2/upload/admins/admintools/tool.php` | High
17 | File | `/manager/jsp/test.jsp` | High
18 | File | `/medical/inventories.php` | High
19 | File | `/monitoring` | Medium
20 | File | `/plugins/servlet/audit/resource` | High
21 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
22 | File | `/replication` | Medium
23 | File | `/RestAPI` | Medium
24 | File | `/TeleoptiWFM/Administration/GetOneTenant` | High
25 | File | `/tmp` | Low
26 | File | `/tmp/speedtest_urls.xml` | High
27 | File | `/uncpath/` | Medium
28 | File | `/usr/bin/at` | Medium
29 | File | `/var/log/nginx` | High
30 | File | `/_vti_pvt/access.cnf` | High
31 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
32 | File | `admin/e_mesaj_yaz.asp` | High
33 | File | `admin/mcart_xls_import.php` | High
34 | File | `admin/profile.php` | High
35 | File | `admin/salesadmin.php` | High
36 | File | `admin/systemWebAdminConfig.do` | High
37 | File | `admin11.cgi` | Medium
38 | File | `admincp/auth/checklogin.php` | High
39 | File | `agenda2.php3` | Medium
40 | File | `ajax-actions.php` | High
41 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/ManagedGuard/AfricaBlackList/blob/main/MGAfricaIPBlackList.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!