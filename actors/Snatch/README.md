# Snatch - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snatch](https://vuldb.com/?actor.snatch). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snatch](https://vuldb.com/?actor.snatch)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snatch:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snatch.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | - | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | - | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | - | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | - | Medium
5 | [4.96.46.65](https://vuldb.com/?ip.4.96.46.65) | - | - | High
6 | [19.2.45.3](https://vuldb.com/?ip.19.2.45.3) | - | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snatch_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snatch. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\WrData\PKG` | High
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/admin/?page=user/list` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/edit_product.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/lab.php` | High
8 | File | `/admin/login.php` | High
9 | File | `/admin/php/crud.php` | High
10 | File | `/admin/read.php?mudi=announContent` | High
11 | File | `/ajax.php?action=read_msg` | High
12 | File | `/api/ping` | Medium
13 | File | `/api/wechat/app_auth` | High
14 | File | `/App_Resource/UEditor/server/upload.aspx` | High
15 | File | `/assets/components/gallery/connector.php` | High
16 | File | `/author_posts.php` | High
17 | File | `/b2b-supermarket/shopping-cart` | High
18 | File | `/bsms_ci/index.php` | High
19 | File | `/change-language/de_DE` | High
20 | File | `/cms/category/list` | High
21 | File | `/College/admin/teacher.php` | High
22 | File | `/dashboard/settings` | High
23 | File | `/Default/Bd` | Medium
24 | File | `/dipam/athlete-profile.php` | High
25 | File | `/dipam/save-delegates.php` | High
26 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
27 | File | `/editbrand.php` | High
28 | File | `/employeeview.php` | High
29 | File | `/etc/target` | Medium
30 | File | `/export` | Low
31 | File | `/getcfg.php` | Medium
32 | File | `/goform/WriteFacMac` | High
33 | File | `/home/kickPlayer` | High
34 | File | `/home/masterConsole` | High
35 | File | `/index.php` | Medium
36 | File | `/lists/admin/user.php` | High
37 | File | `/manager?action=getlogcat` | High
38 | File | `/mkshop/Men/profile.php` | High
39 | File | `/movie.php` | Medium
40 | File | `/news-portal-script/information.php` | High
41 | File | `/pages/apply_vacancy.php` | High
42 | File | `/param.file.tgz` | High
43 | File | `/paysystem/branch.php` | High
44 | File | `/paysystem/datatable.php` | High
45 | File | `/php-opos/index.php` | High
46 | File | `/preview.php` | Medium
47 | File | `/protocol/nsasg6.0.tgz` | High
48 | File | `/rest/api/2/user/picker` | High
49 | ... | ... | ...

There are 424 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Snatch
* https://socradar.io/dark-web-profile-snatch-ransomware/
* https://thedfirreport.com/2020/06/21/snatch-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
