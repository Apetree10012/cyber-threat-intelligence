# RMS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RMS](https://vuldb.com/?actor.rms). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rms](https://vuldb.com/?actor.rms)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RMS:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RMS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.133.65.53](https://vuldb.com/?ip.5.133.65.53) | - | - | High
2 | [37.58.60.5](https://vuldb.com/?ip.37.58.60.5) | hosted-by.zenex5.com | - | High
3 | [43.255.175.215](https://vuldb.com/?ip.43.255.175.215) | - | - | High
4 | [45.82.71.172](https://vuldb.com/?ip.45.82.71.172) | cathost.io | - | High
5 | [45.144.30.30](https://vuldb.com/?ip.45.144.30.30) | polzovatel.com | - | High
6 | [50.240.232.117](https://vuldb.com/?ip.50.240.232.117) | 50-240-232-117-static.hfc.comcastbusiness.net | - | High
7 | [51.83.171.208](https://vuldb.com/?ip.51.83.171.208) | hosted.by.majorcore.com | - | High
8 | [51.83.171.223](https://vuldb.com/?ip.51.83.171.223) | hosted.by.majorcore.com | - | High
9 | [52.208.217.243](https://vuldb.com/?ip.52.208.217.243) | ec2-52-208-217-243.eu-west-1.compute.amazonaws.com | - | Medium
10 | [54.188.107.146](https://vuldb.com/?ip.54.188.107.146) | ec2-54-188-107-146.us-west-2.compute.amazonaws.com | - | Medium
11 | [65.0.5.240](https://vuldb.com/?ip.65.0.5.240) | ec2-65-0-5-240.ap-south-1.compute.amazonaws.com | - | Medium
12 | [66.23.226.254](https://vuldb.com/?ip.66.23.226.254) | - | - | High
13 | [66.208.244.253](https://vuldb.com/?ip.66.208.244.253) | sbs.heraldtech.net | - | High
14 | [77.161.25.182](https://vuldb.com/?ip.77.161.25.182) | 77-161-25-182.fixed.kpn.net | - | High
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RMS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RMS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/options` | High
2 | File | `/api/addusers` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/v11/users/sessions` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/category.php` | High
7 | File | `/cgi-bin/diagnostics` | High
8 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
9 | File | `/cgi-bin/pass` | High
10 | File | `/cmf/process/<process_id>/logs` | High
11 | File | `/config.cgi?webmin` | High
12 | File | `/connectors/index.php` | High
13 | File | `/data/wps.setup.json` | High
14 | File | `/download` | Medium
15 | File | `/edit/server` | Medium
16 | File | `/index.php` | Medium
17 | File | `/mcategory.php` | High
18 | File | `/MIME/INBOX-MM-1/` | High
19 | File | `/movie.php` | Medium
20 | File | `/multi-vendor-shopping-script/product-list.php` | High
21 | File | `/news-portal-script/information.php` | High
22 | File | `/owa/auth/logon.aspx` | High
23 | File | `/page.php` | Medium
24 | File | `/public/login.htm` | High
25 | File | `/public/plugins/` | High
26 | File | `/real-estate-script/search_property.php` | High
27 | File | `/recordings/index.php` | High
28 | File | `/searchJob.php` | High
29 | File | `/uncpath/` | Medium
30 | File | `/user/loader.php?api=1` | High
31 | File | `/var/miniupnpd.conf` | High
32 | File | `/wp-admin/options-general.php` | High
33 | File | `/wp-content/plugins/updraftplus/admin.php` | High
34 | File | `addentry.php` | Medium
35 | File | `addrtoname.c` | Medium
36 | ... | ... | ...

There are 305 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/de7fab866e4ec43a9421d6f98ee5d37ab55c0d341261eb93b564d39786b882ae/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
