# AdNauseam Block List

⚠️ **NOTICE:** ⚠️ \
This project is in no way, shape, or form related to the [AdNauseam](https://adnauseam.io) project, team, and/or browser extension.

This repository is up-to-date as of **2023-05-21**

## Purpose

This repository, AdNauseamBL, serves to be yet another source of DNS-level (or simple `/etc/hosts` file) blocking of domains/TLDs/IPs.
As of this moment, this repository serves to only provide a block file to block domains using generic TLDs (gTLDs) that are based on file extentions
that a gracious mega-corporation[^1][^2][^3] has unfavourably allowed to be registered as internet domains.

*If you would like to convert this list into a hosts-file format, then please submit a pull request with the conversion and it may be merged!*

## Exceptions

Despite this blocklist mainly existing to block file extension based TLDs, exceptions are granted to select TLDs. Below is a list of TLDs excluded from this list.

|**TLD**|**Reason**|
|:---:|:---:|
|**.rs**|Primarily used for [rust-lang](https://rust-lang.org/) and [cargo](https://cargo.io/) projects.|
|**.sh**|Primarily used for diskless install scripts, typically in Shell Script.[^4]|
|**.com**|One of, and if not, the most widely used TLD in the world right next to **.net** and **.org**.|
|**.dev**|Legitimate uses include, but not limited to, developer portfolio and project websites.|
|**.app**|Mostly used for software websites.|

---

[^1]: [XDA-Developers: Google's new .zip and .mov domains are a security incident waiting to happen](https://www.xda-developers.com/google-zip-mov-domains-security/)

[^2]: [ArsTechnica: Google pushes .zip and .mov domains onto the Internet, and the Internet pushes back](https://arstechnica.com/information-technology/2023/05/critics-say-googles-new-zip-and-mov-domains-will-be-a-boon-to-scammers/)

[^3]: [TechRadar: Some of Google's new domain names could pose a serious security risk](https://www.techradar.com/news/want-a-new-google-zip-domain-it-could-be-a-serious-security-risk)

[^4]: Shell Script — A scripting language typically used on UNIX/UNIX-like systems such as Linux, macOS, and BSD systems.
