# StreamEx - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _StreamEx_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with StreamEx:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with StreamEx or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of StreamEx.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
2 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
3 | [88.208.228.56](https://vuldb.com/?ip.88.208.228.56) | bextec.co.uk | [Shell Crew](https://vuldb.com/?actor.shell_crew) | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within StreamEx. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during StreamEx. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/alphaware/summary.php` | High
9 | File | `/api/` | Low
10 | File | `/api/admin/store/product/list` | High
11 | File | `/api/admin/system/store/order/list` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/sys/login` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/api/trackedEntityInstances` | High
17 | File | `/api/v2/cli/commands` | High
18 | File | `/attachments` | Medium
19 | File | `/aux` | Low
20 | File | `/bin/ate` | Medium
21 | File | `/boat/login.php` | High
22 | File | `/booking/show_bookings/` | High
23 | File | `/bsms_ci/index.php/book` | High
24 | File | `/cgi-bin` | Medium
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/changePassword` | High
27 | File | `/Content/Template/root/reverse-shell.aspx` | High
28 | File | `/csms/?page=contact_us` | High
29 | File | `/dashboard/add-blog.php` | High
30 | File | `/data/remove` | Medium
31 | File | `/debug/pprof` | Medium
32 | File | `/ecshop/admin/template.php` | High
33 | File | `/env` | Low
34 | File | `/etc/hosts` | Medium
35 | File | `/forum/away.php` | High
36 | File | `/group1/uploa` | High
37 | File | `/index.php` | Medium
38 | File | `/medicines/profile.php` | High
39 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
40 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
41 | File | `/php-sms/admin/?page=user/manage_user` | High
42 | File | `/proxy` | Low
43 | File | `/reservation/add_message.php` | High
44 | File | `/resources//../` | High
45 | File | `/spip.php` | Medium
46 | File | `/testConnection` | High
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
