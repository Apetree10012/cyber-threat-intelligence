# SDBbot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SDBbot_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SDBbot:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [DE](https://vuldb.com/?country.de)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SDBbot or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA505](https://vuldb.com/?actor.ta505) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SDBbot.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.149.252.171](https://vuldb.com/?ip.5.149.252.171) | absolutecorporation.info | [TA505](https://vuldb.com/?actor.ta505) | High
2 | [37.59.52.229](https://vuldb.com/?ip.37.59.52.229) | bemta-05.srv.sopeople.net | [TA505](https://vuldb.com/?actor.ta505) | High
3 | [45.8.126.7](https://vuldb.com/?ip.45.8.126.7) | mail01.bivoic.com | [TA505](https://vuldb.com/?actor.ta505) | High
4 | [91.214.124.20](https://vuldb.com/?ip.91.214.124.20) | - | [TA505](https://vuldb.com/?actor.ta505) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SDBbot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-37 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SDBbot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/admin/action/update-deworm.php` | High
3 | File | `/admin/add-services.php` | High
4 | File | `/admin/ajax.php?action=save_area` | High
5 | File | `/admin/del_service.php` | High
6 | File | `/admin/departments/manage_department.php` | High
7 | File | `/admin/reportupload.aspx` | High
8 | File | `/admin/sys_sql_query.php` | High
9 | File | `/ample/app/action/edit_product.php` | High
10 | File | `/api/plugin/uninstall` | High
11 | File | `/api/sys/login` | High
12 | File | `/app/sys1.php` | High
13 | File | `/apply/index.php` | High
14 | File | `/assets/php/upload.php` | High
15 | File | `/audimex/cgi-bin/wal.fcgi` | High
16 | File | `/auth_pic.cgi` | High
17 | File | `/blog` | Low
18 | File | `/boaform/device_reset.cgi` | High
19 | File | `/cgi-bin/adm.cgi` | High
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
22 | File | `/cgi-bin/webproc` | High
23 | File | `/classes/Master.php?f=save_inquiry` | High
24 | File | `/classes/Users.php?f=save` | High
25 | File | `/collection/all` | High
26 | File | `/dashboard/createblog` | High
27 | File | `/dipam/athlete-profile.php` | High
28 | File | `/dosen/data` | Medium
29 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
30 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
31 | File | `/file-manager/rename.php` | High
32 | File | `/home/filter_listings` | High
33 | ... | ... | ...

There are 284 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securityintelligence.com/posts/ta505-continues-to-infect-networks-with-sdbbot-rat/
* https://www.proofpoint.com/us/threat-insight/post/ta505-distributes-new-sdbbot-remote-access-trojan-get2-downloader

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
