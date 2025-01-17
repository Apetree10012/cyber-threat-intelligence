# ReverseRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ReverseRAT](https://vuldb.com/?actor.reverserat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.reverserat](https://vuldb.com/?actor.reverserat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ReverseRAT:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ReverseRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [161.97.90.175](https://vuldb.com/?ip.161.97.90.175) | vmi669652.contaboserver.net | - | High
2 | [173.249.50.230](https://vuldb.com/?ip.173.249.50.230) | vmi626137.contaboserver.net | - | High
3 | [185.174.102.54](https://vuldb.com/?ip.185.174.102.54) | 185.174.102.54.deltahost-ptr | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ReverseRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1505 | CWE-89 | SQL Injection | High
2 | T1592 | CWE-200 | Configuration | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ReverseRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `data/gbconfiguration.dat` | High
2 | File | `redir.asp` | Medium
3 | Argument | `password` | Medium

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://s3.amazonaws.com/talos-intelligence-site/production/document_files/files/000/095/594/original/Network_IOCs_list_for_coverage.txt?1625657479
* https://twitter.com/souiten/status/1620629752863404032

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
