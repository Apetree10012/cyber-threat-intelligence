# Imperial Kitten - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Imperial Kitten](https://vuldb.com/?actor.imperial_kitten). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.imperial_kitten](https://vuldb.com/?actor.imperial_kitten)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Imperial Kitten:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 27 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Imperial Kitten.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.8.146.37](https://vuldb.com/?ip.45.8.146.37) | vm1396047.stark-industries.solutions | - | High
2 | [45.32.181.118](https://vuldb.com/?ip.45.32.181.118) | 45.32.181.118.vultrusercontent.com | - | High
3 | [45.81.226.38](https://vuldb.com/?ip.45.81.226.38) | vm4336982.25ssd.had.wf | - | High
4 | [45.93.82.109](https://vuldb.com/?ip.45.93.82.109) | - | - | High
5 | [45.93.93.198](https://vuldb.com/?ip.45.93.93.198) | - | - | High
6 | [45.155.37.105](https://vuldb.com/?ip.45.155.37.105) | - | - | High
7 | [45.155.37.140](https://vuldb.com/?ip.45.155.37.140) | - | - | High
8 | [51.81.165.110](https://vuldb.com/?ip.51.81.165.110) | ip110.ip-51-81-165.us | - | High
9 | [64.176.164.117](https://vuldb.com/?ip.64.176.164.117) | 64.176.164.117.vultrusercontent.com | - | High
10 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Imperial Kitten_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Imperial Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/tutor/filter` | High
2 | File | `/app/options.py` | High
3 | File | `/card_scan.php` | High
4 | File | `/cgi-bin` | Medium
5 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
6 | File | `/cgi-bin/wlogin.cgi` | High
7 | File | `/ClickAndBanexDemo/admin/admin_dblayers.asp` | High
8 | File | `/CMD_ACCOUNT_ADMIN` | High
9 | File | `/cwc/login` | Medium
10 | File | `/download` | Medium
11 | File | `/etc/quagga` | Medium
12 | File | `/etc/shadow` | Medium
13 | File | `/fhconf/umconfig.txt` | High
14 | File | `/forms/doLogin` | High
15 | File | `/h/calendar` | Medium
16 | File | `/inc/extensions.php` | High
17 | File | `/include/chart_generator.php` | High
18 | File | `/includes/login.php` | High
19 | File | `/index.php` | Medium
20 | File | `/members/view_member.php` | High
21 | File | `/mhds/clinic/view_details.php` | High
22 | File | `/nova/bin/console` | High
23 | File | `/nova/bin/detnet` | High
24 | File | `/oauth/idp/.well-known/openid-configuration` | High
25 | File | `/out.php` | Medium
26 | File | `/owa/auth/logon.aspx` | High
27 | File | `/product_list.php` | High
28 | File | `/req_password_user.php` | High
29 | File | `/rest/api/latest/projectvalidate/key` | High
30 | File | `/rom-0` | Low
31 | File | `/secure/QueryComponent!Default.jspa` | High
32 | File | `/ServletAPI/accounts/login` | High
33 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
34 | File | `/sysmanage/changelogo.php` | High
35 | File | `/tmp/.uci/network` | High
36 | File | `/uncpath/` | Medium
37 | File | `/upload` | Low
38 | File | `/usr/bin/pkexec` | High
39 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
40 | File | `/usr/syno/etc/mount.conf` | High
41 | File | `/vdesk` | Low
42 | File | `/WEB-INF/web.xml` | High
43 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
44 | File | `/wp-json` | Medium
45 | File | `aboutus.php` | Medium
46 | File | `achat/produit_details.php` | High
47 | File | `adclick.php` | Medium
48 | File | `add_to_cart.php` | High
49 | File | `adm.cgi` | Low
50 | File | `admin.jcomments.php` | High
51 | File | `admin/index.php` | High
52 | File | `admin/modules/tools/ip_history_logs.php` | High
53 | File | `admin/specials.php` | High
54 | File | `announce.php` | Medium
55 | File | `App/Ajax/ajax.php?action=mobile_upload_save` | High
56 | ... | ... | ...

There are 490 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.crowdstrike.com/blog/imperial-kitten-deploys-novel-malware-families/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
