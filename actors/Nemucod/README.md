# Nemucod - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nemucod](https://vuldb.com/?actor.nemucod). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nemucod](https://vuldb.com/?actor.nemucod)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nemucod:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nemucod.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [24.96.108.157](https://vuldb.com/?ip.24.96.108.157) | static-24-96-108-157.knology.net | - | High
2 | [61.134.39.188](https://vuldb.com/?ip.61.134.39.188) | - | - | High
3 | [62.173.145.104](https://vuldb.com/?ip.62.173.145.104) | sadovaya-mebel.com | - | High
4 | [76.73.17.194](https://vuldb.com/?ip.76.73.17.194) | - | - | High
5 | [78.129.150.54](https://vuldb.com/?ip.78.129.150.54) | - | - | High
6 | [82.192.94.125](https://vuldb.com/?ip.82.192.94.125) | - | - | High
7 | [85.93.145.251](https://vuldb.com/?ip.85.93.145.251) | mail.boanywhere.com | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nemucod_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nemucod. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/ad-list` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/attendance_row.php` | High
7 | File | `/admin/categories/manage_category.php` | High
8 | File | `/admin/categories/view_category.php` | High
9 | File | `/admin/controller/JobLogController.java` | High
10 | File | `/admin/courses/manage_course.php` | High
11 | File | `/admin/departments/manage_department.php` | High
12 | File | `/admin/doctors.php` | High
13 | File | `/admin/edit-services.php` | High
14 | File | `/admin/edit_subject.php` | High
15 | File | `/admin/employee_row.php` | High
16 | File | `/admin/maintenance/brand.php` | High
17 | File | `/admin/maintenance/view_designation.php` | High
18 | File | `/admin/mechanics/manage_mechanic.php` | High
19 | File | `/admin/reportupload.aspx` | High
20 | File | `/admin/service.php` | High
21 | File | `/admin/students/manage_academic.php` | High
22 | File | `/admin/transactions/track_shipment.php` | High
23 | File | `/admin/user/manage_user.php` | High
24 | File | `/alphaware/summary.php` | High
25 | File | `/api/` | Low
26 | File | `/api/admin/store/product/list` | High
27 | File | `/api/baskets/{name}` | High
28 | File | `/api/log/killJob` | High
29 | File | `/api/stl/actions/search` | High
30 | File | `/api/sys/login` | High
31 | File | `/api/sys/set_passwd` | High
32 | File | `/api/trackedEntityInstances` | High
33 | File | `/api/v2/cli/commands` | High
34 | File | `/aux` | Low
35 | File | `/bin/ate` | Medium
36 | File | `/boat/login.php` | High
37 | File | `/booking/show_bookings/` | High
38 | File | `/bsms_ci/index.php/book` | High
39 | File | `/cgi-bin` | Medium
40 | File | `/cgi-bin/wlogin.cgi` | High
41 | File | `/change-language/de_DE` | High
42 | File | `/changePassword` | High
43 | File | `/classes/Master.php?f=save_item` | High
44 | File | `/collection/all` | High
45 | File | `/Content/Template/root/reverse-shell.aspx` | High
46 | File | `/dashboard/add-blog.php` | High
47 | File | `/data/remove` | Medium
48 | File | `/debug/pprof` | Medium
49 | File | `/download.php?file=author.png` | High
50 | File | `/ecshop/admin/template.php` | High
51 | File | `/env` | Low
52 | File | `/forum/away.php` | High
53 | File | `/friends` | Medium
54 | File | `/goform/WifiBasicSet` | High
55 | File | `/group1/uploa` | High
56 | File | `/index.php` | Medium
57 | File | `/index.php?controller=GzUser&action=edit&id=1` | High
58 | File | `/index/user/user_edit.html` | High
59 | File | `/main/offices.php` | High
60 | ... | ... | ...

There are 526 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0524-0531.html
* https://isc.sans.edu/forums/diary/NemucodAES+and+the+malspam+that+distributes+it/22614/
* https://unit42.paloaltonetworks.com/unit42-practice-makes-perfect-nemucod-evolves-delivery-obfuscation-techniques-harvest-credentials/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
