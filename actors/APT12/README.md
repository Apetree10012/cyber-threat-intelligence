# APT12 - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT12](https://vuldb.com/?actor.apt12). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt12](https://vuldb.com/?actor.apt12)

## Campaigns

The following _campaigns_ are known and can be associated with APT12:

* Etumbot

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT12:

* ES
* AR
* US

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT12.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 32.114.251.129 | - | Etumbot | High
2 | 59.0.249.11 | - | Etumbot | High
3 | 92.54.232.142 | - | Etumbot | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by APT12. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1499 | CWE-404 | Resource Consumption | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT12. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/wp-admin/admin-ajax.php` | High
2 | Argument | `repeater` | Medium
3 | Network Port | `tcp/264` | Low

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.fireeye.com/blog/threat-research/2014/09/darwins-favorite-apt-group-2.html
* https://www.threatminer.org/report.php?q=ASERT-Threat-Intelligence-Brief-2014-07-Illuminating-Etumbot-APT.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!