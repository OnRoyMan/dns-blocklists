![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)![GitHub repo size](https://img.shields.io/github/repo-size/hagezi/dns-blocklists)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhagezi%2Fdns-blocklists&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)

## :zap: DNS Blocklists - For a better internet!

### Made with :heartbeat: for a safer and cleaner internet! It always seems impossible until it’s done.

Privacy is not a crime, protect yourself. Privacy matters. Privacy is what allows us to determine who we are and who we want to be :bangbang:

If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)! Thanks for your support!

---

### :bookmark_tabs: Table of Contents

1. [Overview](#overview)
2. [Multi light](#light) - Hand brush: Light protection
3. [Multi normal](#normal) - Broom: All-round protection
4. [Multi pro](#pro) - Big broom: Extended protection (Recommended) : [Full](#pro) - [Mini](#promini)
5. [Multi pro++](#proplus) - Sweeper: Maximum protection (more aggressive) : [Full](#proplus) - [Mini](#proplusmini)
6. [Multi ultimate](#ultimate) - Ultimate Sweeper: Aggressive protection : [Full](#ultimate) - [Mini](#ultimatemini)
7. [Fake](#fake) - Protects against internet scams, traps & fakes!
8. [Pop-Up Ads](#popupads) - Protects against annoying and malicious pop-up ads!
9. [Threat Intelligence Feeds](#tif) - Increases security significantly! (Recommended) : [Full](#tif) - [Medium](#tifmedium) - [Mini](#tifmini) - [IPs](#tifips)
10. [Newly Registered Domains](#nrd) - Favoured by threat actors to launch malicious campaigns!
11. [DoH/VPN/TOR/Proxy Bypass](#bypass) - Prevent methods to bypass your DNS! : [Full](#bypass_all) - [DoH only](#bypass_dns) - [DoH IPs](#bypass_ips)
12. [Safesearch not supported](#safesearch) - Prevent the use of search engines that do not support Safesearch!
13. [Dynamic DNS](#dyndns) - Protects against the malicious use of dynamic DNS services!
14. [Badware Hoster](#hoster) - Protects against the malicious use of host services!
15. [Most Abused TLDs](#tlds) - Protects against known malicious Top Level Domains!
16. [Anti Piracy](#piracy) - Protects against piracy!
17. [Gambling](#gambling) - Protects against gambling content! : [Full](#gambling) - [Medium](#gamblingmedium) - [Mini](#gamblingmini)
18. [NSFW (external)](https://oisd.nl/setup) - oisd NSFW - Protects against adult content!
19. [Native Tracker](#native) - Broadband tracker of devices, services and operating systems
20. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - Leave a star (top right)!
21. [Recommendation](#recommendation) - [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)
22. [Online DNS Services](#dnsservices)
23. [About](#about) : [Repository](#repository) - [Referral Domains](#referral) - [Support Me](#support)
24. [Statistics](statistics.md) - [Sources](sources.md)
25. [FAQ](https://github.com/hagezi/dns-blocklists/wiki/FAQ) - Frequently Asked Questions

### :books: **Multi - Cleans the Internet and protects your privacy!** <a name="overview"></a>

An all-in-one DNS blocklist in **various versions (light, normal, pro, pro++ and ultimate)**. It can be used as a standalone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various native blocklists](sources.md). No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas.             

See also: [Which sources are used for the lists and how are the lists compiled on the basis of these sources?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#sources)

#### **Blocklist version and size overview:**

| Version | Entries | Pro++ | Pro | Nor<br>mal | Light | [Fake](#fake) | [TIF](#tif) | [Nat<br>ive](#native) | [PopUp<br>Ads](#popupads) | Bug<br>Tracker |
|:--------|---:|:------:|:-----:|:----:|:----:|:---:|:------:|:----------:|:----:|:----:|
| :green_book:[Light](#light)             | light_dh<br>light_cp     |  |   |   | :green_circle:  |  | |  :yellow_square: | | |
| :blue_book:[Normal](#normal)       | multi_dh<br>multi_cp     |  |   | :green_circle: | :green_circle: |  | :yellow_square: | :yellow_square: | :yellow_square: | |
| :ledger:[Pro](#pro)              | pro_dh<br>pro_cp         |  | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: | :green_circle: |
| :orange_book:[Pro++](#proplus)    | proplus_dh<br>proplus_cp | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square: |:yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :closed_book:[Ultimate](#ultimate)    | ultimate_dh<br>ultimate_cp | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: contains the list named in the column caption
:yellow_square: partially contains the list named in the column caption

#### **Blocking level:**

| Version | Blocking<br>level | Blocking<br>type |
|:--------|:---------------|:--------------|
| :green_book:[Light](#light)        | :green_book::green_book:                                                                    | Relaxed             |
| :blue_book:[Normal](#normal)       | :blue_book::blue_book::blue_book:                                                           | Relaxed/Balanced    |
| :ledger:[Pro](#pro)                | :ledger::ledger::ledger::ledger:                                                            | Balanced            |
| :orange_book:[Pro++](#proplus)     | :orange_book::orange_book::orange_book::orange_book::orange_book::orange_book:              | Balanced/Aggressive |
| :closed_book:[Ultimate](#ultimate) | :closed_book::closed_book::closed_book::closed_book::closed_book::closed_book::closed_book: | Aggressive |

> [!TIP]
> :information_desk_person: [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)

---

### :green_book: **Multi LIGHT** - **Basic protection** <a name="light"></a>

Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics and some Badware. A size-optimized version of the Multi NORMAL.

> [!NOTE]
> **Blocking type:** Relaxed              
> This list version should not lead to any restrictions. It is particularly suitable for environments in which there is no admin nearby who can unblock something and if you have to pay attention to the size of the list, because the AdBlocker does not support large lists.

> [!IMPORTANT]
> Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.

**Entries:** light_dh domains/hosts - light_dhc compressed hosts - light_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/light.txt) [Mirror](lnkgl_d/light.txt) [Cached](lnkjd_d/light.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/light.txt) [Mirror](lnkgl_h/light.txt) [Cached](lnkjd_h/light.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/light-compressed.txt) [Mirror](lnkgl_h/light-compressed.txt) [Cached](lnkjd_h/light-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/light.txt) [Mirror](lnkgl_a/light.txt) [Cached](lnkjd_a/light.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/light.txt) [Mirror](lnkgl_m/light.txt) [Cached](lnkjd_m/light.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/light.txt) [Mirror](lnkgl_w/light.txt) [Cached](lnkjd_w/light.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/light-onlydomains.txt) [Mirror](lnkgl_w/light-onlydomains.txt) [Cached](lnkjd_w/light-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/light.txt) [Mirror](lnkgl_r/light.txt) [Cached](lnkjd_r/light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| PAC | [Link](lnkgh_p/light.pac) [Mirror](lnkgl_p/light.pac) [Cached](lnkjd_p/light.pac) | Proxy Auto Configuration |

### :blue_book: **Multi NORMAL** - **All-round protection** <a name="normal"></a>

Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".

> [!NOTE]
> **Blocking type:** Relaxed/Balanced              
> This list version should not lead to any restrictions for the most part. It is particularly suitable for environments in which there is no admin nearby who can unblock something.

> [!IMPORTANT]
> Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.

**Entries:** multi_dh domains/hosts - multi_dhc compressed hosts - multi_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/multi.txt) [Mirror](lnkgl_d/multi.txt) [Cached](lnkjd_d/multi.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/multi.txt) [Mirror](lnkgl_h/multi.txt) [Cached](lnkjd_h/multi.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/multi-compressed.txt) [Mirror](lnkgl_h/multi-compressed.txt) [Cached](lnkjd_h/multi-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/multi.txt) [Mirror](lnkgl_a/multi.txt) [Cached](lnkjd_a/multi.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/multi.txt) [Mirror](lnkgl_m/multi.txt) [Cached](lnkjd_m/multi.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/multi.txt) [Mirror](lnkgl_w/multi.txt) [Cached](lnkjd_w/multi.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/multi-onlydomains.txt) [Mirror](lnkgl_w/multi-onlydomains.txt) [Cached](lnkjd_w/multi-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/multi.txt) [Mirror](lnkgl_r/multi.txt) [Cached](lnkjd_r/multi.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :ledger: **Multi PRO** - **Extended protection (Recommended)** <a name="pro"></a>

Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".

> [!NOTE]
> **Blocking type:** Balanced            
> This list version should only very rarely lead to restrictions. It is suitable for environments where there is an admin nearby who can unblock something. My personal recommendation for mostly problem-free adblocking with good privacy protection.

**Entries:** pro_dh domains/hosts - pro_dhc compressed hosts - pro_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/pro.txt) [Mirror](lnkgl_d/pro.txt) [Cached](lnkjd_d/pro.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/pro.txt) [Mirror](lnkgl_h/pro.txt) [Cached](lnkjd_h/pro.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/pro-compressed.txt) [Mirror](lnkgl_h/pro-compressed.txt) [Cached](lnkjd_h/pro-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/pro.txt) [Mirror](lnkgl_a/pro.txt) [Cached](lnkjd_a/pro.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/pro.txt) [Mirror](lnkgl_m/pro.txt) [Cached](lnkjd_m/pro.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.txt) [Mirror](lnkgl_w/pro.txt) [Cached](lnkjd_w/pro.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro-onlydomains.txt) [Mirror](lnkgl_w/pro-onlydomains.txt) [Cached](lnkjd_w/pro-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.txt) [Mirror](lnkgl_r/pro.txt) [Cached](lnkjd_r/pro.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :ledger: **Multi PRO mini (Recommended for browser/mobile adblockers)** <a name="promini"></a>

Size-optimised version for DNS/Browser adblockers. This list only contains domains from the Pro full that have been found on Top 1M lists (Umbrella, Cloudflare, Tranco, Chrome, ...) in the last 12 months.

**Entries:** promini_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/pro.mini.txt) [Mirror](lnkgl_a/pro.mini.txt) [Cached](lnkjd_a/pro.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/pro.mini.txt) [Mirror](lnkgl_m/pro.mini.txt) [Cached](lnkjd_m/pro.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.mini.txt) [Mirror](lnkgl_w/pro.mini.txt) [Cached](lnkjd_w/pro.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro.mini-onlydomains.txt) [Mirror](lnkgl_w/pro.mini-onlydomains.txt) [Cached](lnkjd_w/pro.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.mini.txt) [Mirror](lnkgl_r/pro.mini.txt) [Cached](lnkjd_r/pro.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :orange_book: **Multi PRO++** - **Maximum protection** <a name="proplus"></a>

Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".

> [!NOTE]
> **Blocking type:** Balanced/Aggressive              
> More aggressive version of the Multi PRO blocklist. It may contain a few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains.

> [!WARNING]
> **Referral domains (affiliate and tracking links):**           
> A few referral domains that also function as normal trackers are blocked. For further details see: [Referral domains](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)

**Entries:** proplus_dh domains/hosts - proplus_dhc compressed hosts - proplus_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/pro.plus.txt) [Mirror](lnkgl_d/pro.plus.txt) [Cached](lnkjd_d/pro.plus.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/pro.plus.txt) [Mirror](lnkgl_h/pro.plus.txt) [Cached](lnkjd_h/pro.plus.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/pro.plus-compressed.txt) [Mirror](lnkgl_h/pro.plus-compressed.txt) [Cached](lnkjd_h/pro.plus-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/pro.plus.txt) [Mirror](lnkgl_a/pro.plus.txt) [Cached](lnkjd_a/pro.plus.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam |
| DNSMasq | [Link](lnkgh_m/pro.plus.txt) [Mirror](lnkgl_m/pro.plus.txt) [Cached](lnkjd_m/pro.plus.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.plus.txt) [Mirror](lnkgl_w/pro.plus.txt) [Cached](lnkjd_w/pro.plus.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro.plus-onlydomains.txt) [Mirror](lnkgl_w/pro.plus-onlydomains.txt) [Cached](lnkjd_w/pro.plus-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.plus.txt) [Mirror](lnkgl_r/pro.plus.txt) [Cached](lnkjd_r/pro.plus.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :orange_book: **Multi PRO++ mini** <a name="proplusmini"></a>

Size-optimised version for DNS/Browser adblockers. This list only contains domains from the Pro++ full that have been found on Top 1M lists (Umbrella, Cloudflare, Tranco, Chrome, ...) in the last 12 months.

**Entries:** proplusmini_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/pro.plus.mini.txt) [Mirror](lnkgl_a/pro.plus.mini.txt) [Cached](lnkjd_a/pro.plus.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/pro.plus.mini.txt) [Mirror](lnkgl_m/pro.plus.mini.txt) [Cached](lnkjd_m/pro.plus.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.plus.mini.txt) [Mirror](lnkgl_w/pro.plus.mini.txt) [Cached](lnkjd_w/pro.plus.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro.plus.mini-onlydomains.txt) [Mirror](lnkgl_w/pro.plus.mini-onlydomains.txt) [Cached](lnkjd_w/pro.plus.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.plus.mini.txt) [Mirror](lnkgl_r/pro.plus.mini.txt) [Cached](lnkjd_r/pro.plus.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :closed_book: **Multi ULTIMATE** - **Aggressive protection** <a name="ultimate"></a>

Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Coins and other "Crap".

> [!NOTE]
> **Blocking type:** Aggressive              
> Stricter version of the Multi PRO++ blocklist. It contains domains that limit functionality in apps and on websites - some popular trackers, that lead to restrictions, are blocked in this list. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains.       

> [!WARNING]
> **Referral domains (affiliate and tracking links):**           
> A few referral domains that also function as normal trackers are blocked. For further details see: [Referral domains](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)
>                   
> **Facebook:**          
> Some META trackers are blocked in Ultimate. This restricts the use of Facebook and Facebook Messenger apps. Furthermore, the Whatsapp graph trackers are blocked, which leads to restrictions when creating avatars, using the in-app helpcenter and using video effects. Otherwise, blocking has no effect on Whatsapp functionalities. To use META apps with Ultimate, unblock the following domains if necessary: [META Tracker](share/facebook.txt)
>           
> **Windows/XBox:**          
> Some Microsoft trackers are blocked in Ultimate, which lead to restrictions, e.g. Windows Spotlight, XBox Live Achievements, Windows Activity History and others. For details and which domains must be unblocked for which function, see: [Microsoft Tracker](share/microsoft.txt).
>                   
>**Miscellaneous:**          
> Details on other known issues can be found [here](share/ultimate-known-issues.txt).  
                   
**Entries:** ultimate_dh domains/hosts - ultimate_dhc compressed hosts - ultimate_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/ultimate.txt) [Mirror](lnkgl_d/ultimate.txt) [Cached](lnkjd_d/ultimate.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/ultimate.txt) [Mirror](lnkgl_h/ultimate.txt) [Cached](lnkjd_h/ultimate.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/ultimate-compressed.txt) [Mirror](lnkgl_h/ultimate-compressed.txt) [Cached](lnkjd_h/ultimate-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/ultimate.txt) [Mirror](lnkgl_a/ultimate.txt) [Cached](lnkjd_a/ultimate.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam |
| DNSMasq | [Link](lnkgh_m/ultimate.txt) [Mirror](lnkgl_m/ultimate.txt) [Cached](lnkjd_m/ultimate.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/ultimate.txt) [Mirror](lnkgl_w/ultimate.txt) [Cached](lnkjd_w/ultimate.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/ultimate-onlydomains.txt) [Mirror](lnkgl_w/ultimate-onlydomains.txt) [Cached](lnkjd_w/ultimate-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/ultimate.txt) [Mirror](lnkgl_r/ultimate.txt) [Cached](lnkjd_r/ultimate.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_book: **Multi ULTIMATE mini** <a name="ultimatemini"></a>

Size-optimised version for DNS/Browser adblockers. This list only contains domains from the Ultimate full that have been found on Top 1M lists (Umbrella, Cloudflare, Tranco, Chrome, ...) in the last 12 months.

**Entries:** ultimatemini_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/ultimate.mini.txt) [Mirror](lnkgl_a/ultimate.mini.txt) [Cached](lnkjd_a/ultimate.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/ultimate.mini.txt) [Mirror](lnkgl_m/ultimate.mini.txt) [Cached](lnkjd_m/ultimate.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/ultimate.mini.txt) [Mirror](lnkgl_w/ultimate.mini.txt) [Cached](lnkjd_w/ultimate.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/ultimate.mini-onlydomains.txt) [Mirror](lnkgl_w/ultimate.mini-onlydomains.txt) [Cached](lnkjd_w/ultimate.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/ultimate.mini.txt) [Mirror](lnkgl_r/ultimate.mini.txt) [Cached](lnkjd_r/ultimate.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :trollface: **Fake - Protects against internet scams, traps & fakes!** <a name="fake"></a>

A blocklist for blocking fake stores, -streaming, rip-offs, cost traps and co.

|             | Light | Normal          | Pro            | Pro++          | Ultimate       | TIF<br>TIF medium |
|:-----------:|:-----:|:---------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x:   | :x: | :x: | :x: | :x: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** fake_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/fake.txt) [Mirror](lnkgl_a/fake.txt) [Cached](lnkjd_a/fake.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/fake.txt) [Mirror](lnkgl_m/fake.txt) [Cached](lnkjd_m/fake.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/fake.txt) [Mirror](lnkgl_w/fake.txt) [Cached](lnkjd_w/fake.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/fake-onlydomains.txt) [Mirror](lnkgl_w/fake-onlydomains.txt) [Cached](lnkjd_w/fake-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/fake.txt) [Mirror](lnkgl_r/fake.txt) [Cached](lnkjd_r/fake.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :tada: **Pop-Up Ads - Protects against annoying and malicious pop-up ads!** <a name="popupads"></a>

A blocklist for annoying and malicious pop-up ads.

|             | Light          | Normal         | Pro            | Pro++          | Ultimate       | TIF      |
|:-----------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :green_circle: | :green_circle: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

> [!NOTE]
> Fully included in Pro++ and Ultimate. Partially in Pro. In the combination of the Pro and additionally the Threat Intelligence Feeds (TIF) Medium or Full, all domains from the Pop-Up Ads list are included. This means that if you use the Pro and also the TIF medium or full, you no longer need to add this list separately.

**Entries:** popupads_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/popupads.txt) [Mirror](lnkgl_a/popupads.txt) [Cached](lnkjd_a/popupads.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/popupads.txt) [Mirror](lnkgl_m/popupads.txt) [Cached](lnkjd_m/popupads.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/popupads.txt) [Mirror](lnkgl_w/popupads.txt) [Cached](lnkjd_w/popupads.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/popupads-onlydomains.txt) [Mirror](lnkgl_w/popupads-onlydomains.txt) [Cached](lnkjd_w/popupads-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/popupads.txt) [Mirror](lnkgl_r/popupads.txt) [Cached](lnkjd_r/popupads.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :closed_lock_with_key: **Threat Intelligence Feeds - Increases security significantly! (Recommended)** <a name="tif"></a>

A blocklist for blocking malware, cryptojacking, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** tif_dh domains/hosts - tif_dhc compressed hosts - tif_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/tif.txt) [Mirror](lnkgl_d/tif.txt) [Cached](lnkjd_d/tif.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/tif.txt) [Mirror](lnkgl_h/tif.txt) [Cached](lnkjd_h/tif.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/tif-compressed.txt) [Mirror](lnkgl_h/tif-compressed.txt) [Cached](lnkjd_h/tif-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/tif.txt) [Mirror](lnkgl_a/tif.txt) [Cached](lnkjd_a/tif.txt) | Pi-hole, ~~AdGuard~~ (too big!), AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam |
| DNSMasq | [Link](lnkgh_m/tif.txt) [Mirror](lnkgl_m/tif.txt) [Cached](lnkjd_m/tif.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/tif.txt) [Mirror](lnkgl_w/tif.txt) [Cached](lnkjd_w/tif.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/tif-onlydomains.txt) [Mirror](lnkgl_w/tif-onlydomains.txt) [Cached](lnkjd_w/tif-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/tif.txt) [Mirror](lnkgl_r/tif.txt) [Cached](lnkjd_r/tif.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - Medium version (Recommended for browser/mobile adblockers)** <a name="tifmedium"></a>

A medium version of the Threat Intelligence Feeds list. Designed for Adblockers that have problems with the size of the full TIF list. Contains only important feeds.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** tif_m_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/tif.medium.txt) [Mirror](lnkgl_a/tif.medium.txt) [Cached](lnkjd_a/tif.medium.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/tif.medium.txt) [Mirror](lnkgl_m/tif.medium.txt) [Cached](lnkjd_m/tif.medium.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/tif.medium.txt) [Mirror](lnkgl_w/tif.medium.txt) [Cached](lnkjd_w/tif.medium.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/tif.medium-onlydomains.txt) [Mirror](lnkgl_w/tif.medium-onlydomains.txt) [Cached](lnkjd_w/tif.medium-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/tif.medium.txt) [Mirror](lnkgl_r/tif.medium.txt) [Cached](lnkjd_r/tif.medium.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - Mini version** <a name="tifmini"></a>

A size-optimised version of the Threat Intelligence Feeds Medium list. Designed for Adblockers that have problems with the size of the TIF Medium list.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** tif_i_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/tif.mini.txt) [Mirror](lnkgl_a/tif.mini.txt) [Cached](lnkjd_a/tif.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/tif.mini.txt) [Mirror](lnkgl_m/tif.mini.txt) [Cached](lnkjd_m/tif.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/tif.mini.txt) [Mirror](lnkgl_w/tif.mini.txt) [Cached](lnkjd_w/tif.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/tif.mini-onlydomains.txt) [Mirror](lnkgl_w/tif.mini-onlydomains.txt) [Cached](lnkjd_w/tif.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/tif.mini.txt) [Mirror](lnkgl_r/tif.mini.txt) [Cached](lnkjd_r/tif.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - IPs** <a name="tifips"></a>

IPv4 lists in [plain IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/tif.txt) for firewalls and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif-ips.txt) are also available as an extension to the TIF list.

> [!TIP]
> If the IP list is used in AdGuard Home, all domains that would resolve to the blocked IP are blocked. To prevent the blocked domains from being resolved via IPv6, it is necessary to deactivate resolving via IPv6 in AdGuard Home:                        
> `Settings > DNS settings > DNS server configuration > Disable resolving of IPv6 addresses`

---

### :new: **Newly Registered Domains (NRDs)** <a name="nrd"></a>

A blocklist for blocking domains registered in the last 14 or 30 days. These domains are known to be favoured by threat actors to launch malicious campaigns.

> [!IMPORTANT]
> This is an external list that is created and maintained by [@xRuffKez](https://github.com/xRuffKez).

**For the lists and further details visit the [corresponding repository](https://github.com/xRuffKez/NRD).**

---

### :outbox_tray: **DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!** <a name="bypass"></a>

Prevent methods to bypass your DNS.

> [!NOTE]
> To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS/QUIC (TCP/UDP 853) outbound.

**The block list exists in two versions:**

#### **Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies** <a name="bypass_all"></a>

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** bypass_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_a/doh-vpn-proxy-bypass.txt) [Cached](lnkjd_a/doh-vpn-proxy-bypass.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_m/doh-vpn-proxy-bypass.txt) [Cached](lnkjd_m/doh-vpn-proxy-bypass.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_w/doh-vpn-proxy-bypass.txt) [Cached](lnkjd_w/doh-vpn-proxy-bypass.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/doh-vpn-proxy-bypass-onlydomains.txt) [Mirror](lnkgl_w/doh-vpn-proxy-bypass-onlydomains.txt) [Cached](lnkjd_w/doh-vpn-proxy-bypass-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_r/doh-vpn-proxy-bypass.txt) [Cached](lnkjd_r/doh-vpn-proxy-bypass.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :outbox_tray: **Encrypted DNS Servers only** <a name="bypass_dns"></a>

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** bypassdns_dh domains/hosts - bypassdns_dhc compressed hosts - bypassdns_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/doh.txt) [Mirror](lnkgl_d/doh.txt) [Cached](lnkjd_d/doh.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/doh.txt) [Mirror](lnkgl_h/doh.txt) [Cached](lnkjd_h/doh.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard |
| Hosts<br>Compressed | [Link](lnkgh_h/doh-compressed.txt) [Mirror](lnkgl_h/doh-compressed.txt) [Cached](lnkjd_h/doh-compressed.txt) | Hostfile, Linux, Windows |
| Adblock | [Link](lnkgh_a/doh.txt) [Mirror](lnkgl_a/doh.txt) [Cached](lnkjd_a/doh.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/doh.txt) [Mirror](lnkgl_m/doh.txt) [Cached](lnkjd_m/doh.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/doh.txt) [Mirror](lnkgl_w/doh.txt) [Cached](lnkjd_w/doh.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/doh-onlydomains.txt) [Mirror](lnkgl_w/doh-onlydomains.txt) [Cached](lnkjd_w/doh-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/doh.txt) [Mirror](lnkgl_r/doh.txt) [Cached](lnkjd_r/doh.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :outbox_tray: **Encrypted DNS Servers IPs** <a name="bypass_ips"></a>

IPv4 lists in [plain IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/doh.txt) for firewalls and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-ips.txt) are also available.

> [!TIP]
> If the IP list is used in AdGuard Home, all domains that would resolve to the blocked IP are blocked. To prevent the blocked domains from being resolved via IPv6, it is necessary to deactivate resolving via IPv6 in AdGuard Home:                   
> `Settings > DNS settings > DNS server configuration > Disable resolving of IPv6 addresses`

---

### :mag: **Safesearch not supported - Prevent the use of search engines that do not support Safesearch!** <a name="safesearch"></a>

A blocklist for blocking search engines that do not support Safesearch.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** nosafe_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/nosafesearch.txt) [Mirror](lnkgl_a/nosafesearch.txt) [Cached](lnkjd_a/nosafesearch.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/nosafesearch.txt) [Mirror](lnkgl_m/nosafesearch.txt) [Cached](lnkjd_m/nosafesearch.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/nosafesearch.txt) [Mirror](lnkgl_w/nosafesearch.txt) [Cached](lnkjd_w/nosafesearch.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/nosafesearch-onlydomains.txt) [Mirror](lnkgl_w/nosafesearch-onlydomains.txt) [Cached](lnkjd_w/nosafesearch-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/nosafesearch.txt) [Mirror](lnkgl_r/nosafesearch.txt) [Cached](lnkjd_r/nosafesearch.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :lock_with_ink_pen: **Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!** <a name="dyndns"></a>

A blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** dyndns_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/dyndns.txt) [Mirror](lnkgl_a/dyndns.txt) [Cached](lnkjd_a/dyndns.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/dyndns.txt) [Mirror](lnkgl_m/dyndns.txt) [Cached](lnkjd_m/dyndns.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/dyndns.txt) [Mirror](lnkgl_w/dyndns.txt) [Cached](lnkjd_w/dyndns.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/dyndns-onlydomains.txt) [Mirror](lnkgl_w/dyndns-onlydomains.txt) [Cached](lnkjd_w/dyndns-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/dyndns.txt) [Mirror](lnkgl_r/dyndns.txt) [Cached](lnkjd_r/dyndns.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :computer: **Badware Hoster blocking - Protects against the malicious use of host services!** <a name="hoster"></a>

A blocklist for blocking known hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** hoster_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/hoster.txt) [Mirror](lnkgl_a/hoster.txt) [Cached](lnkjd_a/hoster.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/hoster.txt) [Mirror](lnkgl_m/hoster.txt) [Cached](lnkjd_m/hoster.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/hoster.txt) [Mirror](lnkgl_w/hoster.txt) [Cached](lnkjd_w/hoster.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/hoster-onlydomains.txt) [Mirror](lnkgl_w/hoster-onlydomains.txt) [Cached](lnkjd_w/hoster-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/hoster.txt) [Mirror](lnkgl_r/hoster.txt) [Cached](lnkjd_r/hoster.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| ControlD | [Link](https://github.com/hagezi/dns-blocklists/blob/main/controld/badware-hoster-folder.json)| ControlD folder |

---

### :crystal_ball: **Most Abused TLDs - Protects against known malicious Top Level Domains! (Recommended)** <a name="tlds"></a>

A blocklist for blocking Top Most Abused Top Level Domains, merged from [@Yokoffing](https://github.com/yokoffing), [@DandelionSprout](https://github.com/DandelionSprout/), [@LennyFox](https://github.com/lennyfox) Cloudflare Radar, Netcraft and SpamHaus.

> [!WARNING]
> The purpose of this list is to block TLDs (`*.top`, `*.shop`, `*.gdn`, ...) that have a bad reputation score. All pages of the TLD contained on the list are blocked, and it is clear that this also blocks any legal pages. More or less, depending on the current TLD reputation score.                    
> However, a lot of spam, scam, phishing, malware and badware is also blocked very effectively. That is the purpose of this list.                   
> Anyone using this list should be aware of what the list blocks.
>        
> For the AdBlock format (AdGuard and uBlock Origin) of the list there is the option to exclude popular domains via rule modifiers like `$denyallow` or `$domain`. However, the number is limited, as the entire rule becomes invalid depending on the total length. Therefore, only popular domains are unblocked.              
> For other formats, the user himself is responsible for unblocking what he needs.
              
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| AdGuard | [Link](lnkgh_a/spam-tlds.txt) [Mirror](lnkgl_a/spam-tlds.txt) [Cached](lnkjd_a/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock Origin  | [Link](lnkgh_a/spam-tlds-ublock.txt) [Mirror](lnkgl_a/spam-tlds-ublock.txt) [Cached](lnkjd_a/spam-tlds-ublock.txt) | uBlock Origin, Adblock Plus |
| AdBlock  | [Link](lnkgh_a/spam-tlds-adblock.txt) [Mirror](lnkgl_a/spam-tlds-adblock.txt) [Cached](lnkjd_a/spam-tlds-adblock.txt) | Pi-hole, AdBlock, TechnitiumDNS<br>Contains only spam TLDs that do not have any exclusions. |
| AdBlock<br>(Aggressive)<br><br>Allowlist | [Link](lnkgh_a/spam-tlds-adblock-aggressive.txt) [Mirror](lnkgl_a/spam-tlds-adblock-aggressive.txt) [Cached](lnkjd_a/spam-tlds-adblock-aggressive.txt)<br><br><br>[Link](lnkgh_a/spam-tlds-adblock-allow.txt) [Mirror](lnkgl_a/spam-tlds-adblock-allow.txt) [Cached](lnkjd_a/spam-tlds-adblock-allow.txt) | Pi-hole, AdBlock, TechnitiumDNS |
| RPZ | [Link](lnkgh_r/spam-tlds-rpz.txt) [Mirror](lnkgl_r/spam-tlds-rpz.txt) [Cached](lnkjd_r/spam-tlds-rpz.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound<br>Contains only spam TLDs that do not have any exclusions. |
| RPZ<br>(Aggressive) | [Link](lnkgh_r/spam-tlds-rpz-aggressive.txt) [Mirror](lnkgl_r/spam-tlds-rpz-aggressive.txt) [Cached](lnkjd_r/spam-tlds-rpz-aggressive.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound<br>Contains all spam TLDs, corresponds to the AdGuard and uBlock Origin version without exclusions. |
| ControlD | [TLDs](https://github.com/hagezi/dns-blocklists/blob/main/controld/spam-tlds-folder.json) [IDNs](https://github.com/hagezi/dns-blocklists/blob/main/controld/spam-idns-folder.json) [Allow](https://github.com/hagezi/dns-blocklists/blob/main/controld/spam-tlds-allow-folder.json) | ControlD folder |

---

### :skull: **Anti Piracy - Protects against piracy!** <a name="piracy"></a>

Blocks websites and services that are mainly used for the illegal distribution of copyrighted content.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** piracy_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/anti.piracy.txt) [Mirror](lnkgl_a/anti.piracy.txt) [Cached](lnkjd_a/anti.piracy.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/anti.piracy.txt) [Mirror](lnkgl_m/anti.piracy.txt) [Cached](lnkjd_m/anti.piracy.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/anti.piracy.txt) [Mirror](lnkgl_w/anti.piracy.txt) [Cached](lnkjd_w/anti.piracy.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/anti.piracy-onlydomains.txt) [Mirror](lnkgl_w/anti.piracy-onlydomains.txt) [Cached](lnkjd_w/anti.piracy-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/anti.piracy.txt) [Mirror](lnkgl_r/anti.piracy.txt) [Cached](lnkjd_r/anti.piracy.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :slot_machine: **Gambling - Protects against gambling content!** <a name="gambling"></a>

Blocks gambling content.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** gambling_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/gambling.txt) [Mirror](lnkgl_a/gambling.txt) [Cached](lnkjd_a/gambling.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam |
| DNSMasq | [Link](lnkgh_m/gambling.txt) [Mirror](lnkgl_m/gambling.txt) [Cached](lnkjd_m/gambling.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/gambling.txt) [Mirror](lnkgl_w/gambling.txt) [Cached](lnkjd_w/gambling.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/gambling-onlydomains.txt) [Mirror](lnkgl_w/gambling-onlydomains.txt) [Cached](lnkjd_w/gambling-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/gambling.txt) [Mirror](lnkgl_r/gambling.txt) [Cached](lnkjd_r/gambling.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :slot_machine: **Gambling - Medium version** <a name="gamblingmedium"></a>

A medium version of the Gambling list. Designed for Adblockers that have problems with the size of the full Gambling list.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** gamblingm_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/gambling.medium.txt) [Mirror](lnkgl_a/gambling.medium.txt) [Cached](lnkjd_a/gambling.medium.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/gambling.medium.txt) [Mirror](lnkgl_m/gambling.medium.txt) [Cached](lnkjd_m/gambling.medium.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/gambling.medium.txt) [Mirror](lnkgl_w/gambling.medium.txt) [Cached](lnkjd_w/gambling.medium.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/gambling.medium-onlydomains.txt) [Mirror](lnkgl_w/gambling.medium-onlydomains.txt) [Cached](lnkjd_w/gambling.medium-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/gambling.medium.txt) [Mirror](lnkgl_r/gambling.medium.txt) [Cached](lnkjd_r/gambling.medium.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :slot_machine: **Gambling - Mini version** <a name="gamblingmini"></a>

A size-optimised version of the Gambling Medium list. This list only contains domains that have been found on Top 1M lists (Umbrella, Cloudflare, Tranco, Chrome, ...) in the last 12 months.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** gamblingi_cp compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/gambling.mini.txt) [Mirror](lnkgl_a/gambling.mini.txt) [Cached](lnkjd_a/gambling.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, AdBlock, Adblock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| DNSMasq | [Link](lnkgh_m/gambling.mini.txt) [Mirror](lnkgl_m/gambling.mini.txt) [Cached](lnkjd_m/gambling.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/gambling.mini.txt) [Mirror](lnkgl_w/gambling.mini.txt) [Cached](lnkjd_w/gambling.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/gambling.mini-onlydomains.txt) [Mirror](lnkgl_w/gambling.mini-onlydomains.txt) [Cached](lnkjd_w/gambling.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/gambling.mini.txt) [Mirror](lnkgl_r/gambling.mini.txt) [Cached](lnkjd_r/gambling.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :calling: **Native Tracker - Broadband tracker of devices, services and operating systems** <a name="native"></a>

Blocks native broadband tracker from devices, services and operating systems that track your activity.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :yellow_square:   | :yellow_square:    | :yellow_square: | :yellow_square:  | :green_circle:      |

:green_circle: yes :yellow_square: partially :x: no

| Device/Service | Domains | Hosts | Adblock | DNSMasq | Wildcard<br>Asterisk | Wildcard<br>Domains | RPZ |
|:-------|:--------:|:------:|:--------:|:--------:|:---------:|:--------:|:--------:|
| Amazon (Devices, Shopping, Video) | [Link](lnkgh_d/native.amazon.txt) [Mirror](lnkgl_d/native.amazon.txt) [Cached](lnkjd_d/native.amazon.txt) | [Link](lnkgh_h/native.amazon.txt) [Mirror](lnkgl_h/native.amazon.txt) [Cached](lnkjd_h/native.amazon.txt) | [Link](lnkgh_a/native.amazon.txt) [Mirror](lnkgl_a/native.amazon.txt) [Cached](lnkjd_a/native.amazon.txt) | [Link](lnkgh_m/native.amazon.txt) [Mirror](lnkgl_m/native.amazon.txt) [Cached](lnkjd_m/native.amazon.txt) | [Link](lnkgh_w/native.amazon.txt) [Mirror](lnkgl_w/native.amazon.txt) [Cached](lnkjd_w/native.amazon.txt) | [Link](lnkgh_w/native.amazon-onlydomains.txt) [Mirror](lnkgl_w/native.amazon-onlydomains.txt) [Cached](lnkjd_w/native.amazon-onlydomains.txt) | [Link](lnkgh_r/native.amazon.txt) [Mirror](lnkgl_r/native.amazon.txt) [Cached](lnkjd_r/native.amazon.txt) |
| Apple (iOS, macOS, tvOS) | [Link](lnkgh_d/native.apple.txt) [Mirror](lnkgl_d/native.apple.txt) [Cached](lnkjd_d/native.apple.txt) | [Link](lnkgh_h/native.apple.txt) [Mirror](lnkgl_h/native.apple.txt) [Cached](lnkjd_h/native.apple.txt) | [Link](lnkgh_a/native.apple.txt) [Mirror](lnkgl_a/native.apple.txt) [Cached](lnkjd_a/native.apple.txt) | [Link](lnkgh_m/native.apple.txt) [Mirror](lnkgl_m/native.apple.txt) [Cached](lnkjd_m/native.apple.txt) | [Link](lnkgh_w/native.apple.txt) [Mirror](lnkgl_w/native.apple.txt) [Cached](lnkjd_w/native.apple.txt) | [Link](lnkgh_w/native.apple-onlydomains.txt) [Mirror](lnkgl_w/native.apple-onlydomains.txt) [Cached](lnkjd_w/native.apple-onlydomains.txt) | [Link](lnkgh_r/native.apple.txt) [Mirror](lnkgl_r/native.apple.txt) [Cached](lnkjd_r/native.apple.txt) |
| Huawei (Devices) | [Link](lnkgh_d/native.huawei.txt) [Mirror](lnkgl_d/native.huawei.txt) [Cached](lnkjd_d/native.huawei.txt) | [Link](lnkgh_h/native.huawei.txt) [Mirror](lnkgl_h/native.huawei.txt) [Cached](lnkjd_h/native.huawei.txt) | [Link](lnkgh_a/native.huawei.txt) [Mirror](lnkgl_a/native.huawei.txt) [Cached](lnkjd_a/native.huawei.txt) | [Link](lnkgh_m/native.huawei.txt) [Mirror](lnkgl_m/native.huawei.txt) [Cached](lnkjd_m/native.huawei.txt) | [Link](lnkgh_w/native.huawei.txt) [Mirror](lnkgl_w/native.huawei.txt) [Cached](lnkjd_w/native.huawei.txt) | [Link](lnkgh_w/native.huawei-onlydomains.txt) [Mirror](lnkgl_w/native.huawei-onlydomains.txt) [Cached](lnkjd_w/native.huawei-onlydomains.txt) | [Link](lnkgh_r/native.huawei.txt) [Mirror](lnkgl_r/native.huawei.txt) [Cached](lnkjd_r/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [Link](lnkgh_d/native.winoffice.txt) [Mirror](lnkgl_d/native.winoffice.txt) [Cached](lnkjd_d/native.winoffice.txt) | [Link](lnkgh_h/native.winoffice.txt) [Mirror](lnkgl_h/native.winoffice.txt) [Cached](lnkjd_h/native.winoffice.txt) | [Link](lnkgh_a/native.winoffice.txt) [Mirror](lnkgl_a/native.winoffice.txt) [Cached](lnkjd_a/native.winoffice.txt) | [Link](lnkgh_m/native.winoffice.txt) [Mirror](lnkgl_m/native.winoffice.txt) [Cached](lnkjd_m/native.winoffice.txt) | [Link](lnkgh_w/native.winoffice.txt) [Mirror](lnkgl_w/native.winoffice.txt) [Cached](lnkjd_w/native.winoffice.txt) | [Link](lnkgh_w/native.winoffice-onlydomains.txt) [Mirror](lnkgl_w/native.winoffice-onlydomains.txt) [Cached](lnkjd_w/native.winoffice-onlydomains.txt) | [Link](lnkgh_r/native.winoffice.txt) [Mirror](lnkgl_r/native.winoffice.txt) [Cached](lnkjd_r/native.winoffice.txt) |
| Samsung | [Link](lnkgh_d/native.samsung.txt) [Mirror](lnkgl_d/native.samsung.txt) [Cached](lnkjd_d/native.samsung.txt) | [Link](lnkgh_h/native.samsung.txt) [Mirror](lnkgl_h/native.samsung.txt) [Cached](lnkjd_h/native.samsung.txt) | [Link](lnkgh_a/native.samsung.txt) [Mirror](lnkgl_a/native.samsung.txt) [Cached](lnkjd_a/native.samsung.txt) | [Link](lnkgh_m/native.samsung.txt) [Mirror](lnkgl_m/native.samsung.txt) [Cached](lnkjd_m/native.samsung.txt) | [Link](lnkgh_w/native.samsung.txt) [Mirror](lnkgl_w/native.samsung.txt) [Cached](lnkjd_w/native.samsung.txt) | [Link](lnkgh_w/native.samsung-onlydomains.txt) [Mirror](lnkgl_w/native.samsung-onlydomains.txt) [Cached](lnkjd_w/native.samsung-onlydomains.txt) | [Link](lnkgh_r/native.samsung.txt) [Mirror](lnkgl_r/native.samsung.txt) [Cached](lnkjd_r/native.samsung.txt) |
| TikTok (Fingerprinting) | [Link](lnkgh_d/native.tiktok.txt) [Mirror](lnkgl_d/native.tiktok.txt) [Cached](lnkjd_d/native.tiktok.txt) | [Link](lnkgh_h/native.tiktok.txt) [Mirror](lnkgl_h/native.tiktok.txt) [Cached](lnkjd_h/native.tiktok.txt) | [Link](lnkgh_a/native.tiktok.txt) [Mirror](lnkgl_a/native.tiktok.txt) [Cached](lnkjd_a/native.tiktok.txt) | [Link](lnkgh_m/native.tiktok.txt) [Mirror](lnkgl_m/native.tiktok.txt) [Cached](lnkjd_m/native.tiktok.txt) | [Link](lnkgh_w/native.tiktok.txt) [Mirror](lnkgl_w/native.tiktok.txt) [Cached](lnkjd_w/native.tiktok.txt) | [Link](lnkgh_w/native.tiktok-onlydomains.txt) [Mirror](lnkgl_w/native.tiktok-onlydomains.txt) [Cached](lnkjd_w/native.tiktok-onlydomains.txt) | [Link](lnkgh_r/native.tiktok.txt) [Mirror](lnkgl_r/native.tiktok.txt) [Cached](lnkjd_r/native.tiktok.txt) |
| TikTok (Fingerprinting) Aggressive | [Link](lnkgh_d/native.tiktok.extended.txt) [Mirror](lnkgl_d/native.tiktok.extended.txt) [Cached](lnkjd_d/native.tiktok.extended.txt) | [Link](lnkgh_h/native.tiktok.extended.txt) [Mirror](lnkgl_h/native.tiktok.extended.txt) [Cached](lnkjd_h/native.tiktok.extended.txt) | [Link](lnkgh_a/native.tiktok.extended.txt) [Mirror](lnkgl_a/native.tiktok.extended.txt) [Cached](lnkjd_a/native.tiktok.extended.txt) | [Link](lnkgh_m/native.tiktok.extended.txt) [Mirror](lnkgl_m/native.tiktok.extended.txt) [Cached](lnkjd_m/native.tiktok.extended.txt) | [Link](lnkgh_w/native.tiktok.extended.txt) [Mirror](lnkgl_w/native.tiktok.extended.txt) [Cached](lnkjd_w/native.tiktok.extended.txt) | [Link](lnkgh_w/native.tiktok.extended-onlydomains.txt) [Mirror](lnkgl_w/native.tiktok.extended-onlydomains.txt) [Cached](lnkjd_w/native.tiktok.extended-onlydomains.txt) | [Link](lnkgh_r/native.tiktok.extended.txt) [Mirror](lnkgl_r/native.tiktok.extended.txt) [Cached](lnkjd_r/native.tiktok.extended.txt) |
| LG webOS | [Link](lnkgh_d/native.lgwebos.txt) [Mirror](lnkgl_d/native.lgwebos.txt) [Cached](lnkjd_d/native.lgwebos.txt) | [Link](lnkgh_h/native.lgwebos.txt) [Mirror](lnkgl_h/native.lgwebos.txt) [Cached](lnkjd_h/native.lgwebos.txt) | [Link](lnkgh_a/native.lgwebos.txt) [Mirror](lnkgl_a/native.lgwebos.txt) [Cached](lnkjd_a/native.lgwebos.txt) | [Link](lnkgh_m/native.lgwebos.txt) [Mirror](lnkgl_m/native.lgwebos.txt) [Cached](lnkjd_m/native.lgwebos.txt) | [Link](lnkgh_w/native.lgwebos.txt) [Mirror](lnkgl_w/native.lgwebos.txt) [Cached](lnkjd_w/native.lgwebos.txt) | [Link](lnkgh_w/native.lgwebos-onlydomains.txt) [Mirror](lnkgl_w/native.lgwebos-onlydomains.txt) [Cached](lnkjd_w/native.lgwebos-onlydomains.txt) | [Link](lnkgh_r/native.lgwebos.txt) [Mirror](lnkgl_r/native.lgwebos.txt) [Cached](lnkjd_r/native.lgwebos.txt) |
| Vivo | [Link](lnkgh_d/native.vivo.txt) [Mirror](lnkgl_d/native.vivo.txt) [Cached](lnkjd_d/native.vivo.txt) | [Link](lnkgh_h/native.vivo.txt) [Mirror](lnkgl_h/native.vivo.txt) [Cached](lnkjd_h/native.vivo.txt) | [Link](lnkgh_a/native.vivo.txt) [Mirror](lnkgl_a/native.vivo.txt) [Cached](lnkjd_a/native.vivo.txt) | [Link](lnkgh_m/native.vivo.txt) [Mirror](lnkgl_m/native.vivo.txt) [Cached](lnkjd_m/native.vivo.txt) | [Link](lnkgh_w/native.vivo.txt) [Mirror](lnkgl_w/native.vivo.txt) [Cached](lnkjd_w/native.vivo.txt) | [Link](lnkgh_w/native.vivo-onlydomains.txt) [Mirror](lnkgl_w/native.vivo-onlydomains.txt) [Cached](lnkjd_w/native.vivo-onlydomains.txt) | [Link](lnkgh_r/native.vivo.txt) [Mirror](lnkgl_r/native.vivo.txt) [Cached](lnkjd_r/native.vivo.txt) |
| OPPO/Realme | [Link](lnkgh_d/native.oppo-realme.txt) [Mirror](lnkgl_d/native.oppo-realme.txt) [Cached](lnkjd_d/native.oppo-realme.txt) | [Link](lnkgh_h/native.oppo-realme.txt) [Mirror](lnkgl_h/native.oppo-realme.txt) [Cached](lnkjd_h/native.oppo-realme.txt) | [Link](lnkgh_a/native.oppo-realme.txt) [Mirror](lnkgl_a/native.oppo-realme.txt) [Cached](lnkjd_a/native.oppo-realme.txt) | [Link](lnkgh_m/native.oppo-realme.txt) [Mirror](lnkgl_m/native.oppo-realme.txt) [Cached](lnkjd_m/native.oppo-realme.txt) | [Link](lnkgh_w/native.oppo-realme.txt) [Mirror](lnkgl_w/native.oppo-realme.txt) [Cached](lnkjd_w/native.oppo-realme.txt) | [Link](lnkgh_w/native.oppo-realme-onlydomains.txt) [Mirror](lnkgl_w/native.oppo-realme-onlydomains.txt) [Cached](lnkjd_w/native.oppo-realme-onlydomains.txt) | [Link](lnkgh_r/native.oppo-realme.txt) [Mirror](lnkgl_r/native.oppo-realme.txt) [Cached](lnkjd_r/native.oppo-realme.txt) |
| Xiaomi | [Link](lnkgh_d/native.xiaomi.txt) [Mirror](lnkgl_d/native.xiaomi.txt) [Cached](lnkjd_d/native.xiaomi.txt) | [Link](lnkgh_h/native.xiaomi.txt) [Mirror](lnkgl_h/native.xiaomi.txt) [Cached](lnkjd_h/native.xiaomi.txt) | [Link](lnkgh_a/native.xiaomi.txt) [Mirror](lnkgl_a/native.xiaomi.txt) [Cached](lnkjd_a/native.xiaomi.txt) | [Link](lnkgh_m/native.xiaomi.txt) [Mirror](lnkgl_m/native.xiaomi.txt) [Cached](lnkjd_m/native.xiaomi.txt) | [Link](lnkgh_w/native.xiaomi.txt) [Mirror](lnkgl_w/native.xiaomi.txt) [Cached](lnkjd_w/native.xiaomi.txt) | [Link](lnkgh_w/native.xiaomi-onlydomains.txt) [Mirror](lnkgl_w/native.xiaomi-onlydomains.txt) [Cached](lnkjd_w/native.xiaomi-onlydomains.txt) | [Link](lnkgh_r/native.xiaomi.txt) [Mirror](lnkgl_r/native.xiaomi.txt) [Cached](lnkjd_r/native.xiaomi.txt) |

---

### :bulb: **Recommendation** <a name="recommendation"></a>

As a network-wide DNS blocker, I recommend using [Adguard Home](https://adguard.com), [Pi-hole](https://pi-hole.net/), [TechnitiumDNS](https://technitium.com/dns/), [Blocky](https://github.com/0xERR0R/blocky) (advanced users), [adblock-lean](https://github.com/lynxthecat/adblock-lean) (OpenWrt) or [eBlocker](https://eblocker.org/).

DNS blockers offer good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!
Therefore, I **additionally** recommend the use of a browser content blocker such as [AdGuard](https://adguard.com), [uBlock Origin](https://ublockorigin.com) or [Ghostery](https://www.ghostery.com/).

Check out Yokoffing's [Recommended Filters for uBlock Origin](https://github.com/yokoffing/filterlists) for content blocker filter lists.
For a browser recommendation see also Yokoffing's [I need a browser with ad blocking. Which one should I choose?](https://github.com/yokoffing/NextDNS-Config#i-need-a-browser-with-ad-blocking-which-one-should-i-choose)

> [!TIP]
> :information_desk_person: [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)

---

### :department_store: **Online DNS Services** <a name="dnsservices"></a>

If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then you can use one of the following DNS services.

**Availability of the lists in the respective DNS services:** <a name="availablelists"></a>

| Service | Light | Nor<br>mal | Pro | Pro<br>++ | Ulti<br>mate | TIF | By<br>pass | Dyn<br>DNS | Hoster | TLDs | Anti<br>Piracy | Gam<br>bling |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| AdGuard<br>DNS         | :x:            | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle:   | :green_circle:   | :green_circle: | :green_circle: | :green_circle:   | :green_circle:   |
| ControlD            | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square:  | :yellow_square:  | :notebook:            | :notebook:            | :yellow_square:  | :yellow_square:  |
| NextDNS             | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :x:            | :yellow_square:              | :x:              | :x:            | :x:            | :x:              | :x:              |
| Rethink<br>DNS          | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :x:              | :green_circle:   | :green_circle: | :x:            | :x:              | :x:              |
| DNS<br>warden           | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :x:              | :x:              | :x:            | :x:            | :x:              | :x:              |

:yellow_square: Are included in the ControlD/NextDNS native lists of the respective category.                        
:notebook: Available as [ControlD folder](https://github.com/hagezi/dns-blocklists/tree/main/controld).

#### :department_store: **AdGuardDNS - limited free/paid** <a name="adguarddns"></a>

In [AdGuardDNS](https://adguard-dns.io) you can use my Multi Normal, Pro, Pro++, Ultimate, TIF, Gambling, Anti Piracy, DoH/VPN/TOR/Proxy Bypass, DynDNS, Badware Hoster, Most Abused TLDs list and the Allowlist Referral.

#### :department_store: **ControlD - free/paid** <a name="controld"></a>

In [ControlD](https://controld.com) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF lists.

**Free:**

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC | Legacy DNS | Apple |
|:-----------|:---------------|:-------------|:-------------|:---:|
| Light | `https://freedns.controld.com/x-hagezi-light` | `x-hagezi-light.freedns.controld.com` | 76.76.2.37<br>76.76.10.37<br>2606:1a40::37<br>2606:1a40:1::37 | [Link](https://api.controld.com/mobileconfig/x-hagezi-light?type=free&exclude_common=1) |
| Normal | `https://freedns.controld.com/x-hagezi-normal` | `x-hagezi-normal.freedns.controld.com` | 76.76.2.40<br>76.76.10.40<br>2606:1a40::40<br>2606:1a40:1::40 | [Link](https://api.controld.com/mobileconfig/x-hagezi-normal?type=free&exclude_common=1) |
| Pro | `https://freedns.controld.com/x-hagezi-pro` | `x-hagezi-pro.freedns.controld.com` | 76.76.2.41<br>76.76.10.41<br>2606:1a40::41<br>2606:1a40:1::41 | [Link](https://api.controld.com/mobileconfig/x-hagezi-pro?type=free&exclude_common=1) |
| Pro Plus | `https://freedns.controld.com/x-hagezi-proplus` | `x-hagezi-proplus.freedns.controld.com` | 76.76.2.42<br>76.76.10.42<br>2606:1a40::42<br>2606:1a40:1::42 | [Link](https://api.controld.com/mobileconfig/x-hagezi-proplus?type=free&exclude_common=1) |
| Ultimate | `https://freedns.controld.com/x-hagezi-ultimate` | `x-hagezi-ultimate.freedns.controld.com` | 76.76.2.45<br>76.76.10.45<br>2606:1a40::45<br>2606:1a40:1::45 | [Link](https://api.controld.com/mobileconfig/x-hagezi-ultimate?type=free&exclude_common=1) |
| TIF | `https://freedns.controld.com/x-hagezi-tif` | `x-hagezi-tif.freedns.controld.com` | 76.76.2.46<br>76.76.10.46<br>2606:1a40::46<br>2606:1a40:1::46 | [Link](https://api.controld.com/mobileconfig/x-hagezi-tif?type=free&exclude_common=1) |

**Paid:**

Check out Yokoffing's [ControlD Config Guide](https://github.com/yokoffing/Control-D-Config) for recommended [ControlD](https://controld.com) configuration settings.

#### :department_store: **NextDNS - limited free/paid** <a name="nextdns"></a>

In [NextDNS](https://nextdns.io) you can use my Light, Normal, Pro, Pro++ and Ultimate lists.

Check out Yokoffing's [NextDNS Config Guide](https://github.com/yokoffing/NextDNS-Config) and the Techlore Video [The ULTIMATE Guide to Mastering NextDNS!](https://youtu.be/WUG57ynLb8I) for recommended [NextDNS](https://nextdns.io) configuration settings.

#### :department_store: **RethinkDNS - free** <a name="rethinkdns"></a>

In [RethinkDNS](https://rethinkdns.com) you can use my Light, Normal, Pro, Pro++, Ultimate, TIF, DynDNS and Badware Hoster lists.

> [!NOTE]
> The lists in RethinkDNS are only updated once a week.

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:-------------|
| Light + TIF | `https://sky.rethinkdns.com/1:AAkACAQA` | `1-aaeqacaeaa.max.rethinkdns.com` |
| Normal + TIF | `https://sky.rethinkdns.com/1:AAkACAgA` | `1-aaeqacaiaa.max.rethinkdns.com` |
| Pro + TIF  | `https://sky.rethinkdns.com/1:AAoACBAA` | `1-aafaacaqaa.max.rethinkdns.com` |
| Pro plus + TIF | `https://sky.rethinkdns.com/1:AAoACAgA` | `1-aafaacaiaa.max.rethinkdns.com` |
| Ultimate + TIF | `https://sky.rethinkdns.com/1:gAgACABA` | `1-qaeaacaaia.max.rethinkdns.com` |

#### :department_store: **DNSwarden - free** <a name="dnswarden"></a>

In [DNSwarden](https://dnswarden.com/customfilter.html) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF lists.

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:------------------|
| Light + TIF | `https://dns.dnswarden.com/00000000000000000000048` | `00000000000000000000048.dns.dnswarden.com` |
| Normal + TIF | `https://dns.dnswarden.com/00000000000000000000028` | `00000000000000000000028.dns.dnswarden.com` |
| Pro + TIF  | `https://dns.dnswarden.com/00000000000000000000018` | `00000000000000000000018.dns.dnswarden.com` |
| Pro plus + TIF | `https://dns.dnswarden.com/0000000000000000000000o` | `0000000000000000000000o.dns.dnswarden.com` |
| Ultimate + TIF | `https://dns.dnswarden.com/0000000000000000000000804` | `0000000000000000000000804.dns.dnswarden.com` |

#### :department_store: **OpenBLD.net - free** <a name="openbld"></a>

[OpenBLD.net](https://openbld.net/docs/get-started/third-party-filters/hagezi/) uses my Multi Pro in combination with the TIF blocklist.

| Blocklists | DNS-over-HTTPS | 
|:-----------|:---------------|
| Pro + TIF  | `https://ric.openbld.net/dns-query/hagezi` |

#### :department_store: **RobinGroppe.de (Germany) - free** <a name="robingroppe"></a>

[RobinGroppe.de DNS](https://www.robingroppe.de/serverzeug/dns-server) offers a free German DNS server without logging to block malware, phishing and other threats. It uses my TIF list.

---

### :loudspeaker: **About** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists&max=1" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

The blocklists are based on [various sources](sources.md) and my own denylists/extensions. They were designed to avoid false positive domains as much as possible without losing effectiveness and efficiency. Dead hosts are regularly removed from the lists to keep them as small as possible.
Made with :heartbeat: for a safer and cleaner internet.

All lists were tested against 10000 websites from the Cisco Umbrella Top 1 million list. It was checked whether the pages load, the page content is displayed correctly, navigation links work, images load, videos start and much more.

No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas. See also: [Which sources are used for the lists and how are the lists compiled on the basis of these sources?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#sources)

The results of a test against the 10000 [whotracks.me](https://whotracks.me/websites.html) pages. All pages were opened and fully loaded via batch in Edge with privacy features turned off. Cookies were all accepted.

| **List**     | Total queries | Blocked queries | % blocked | % gap to light |
|-------------:|--------------:|----------------:|----------:|---------------:|
| **Ultimate** | 299646        | 131093          | 43.75     | 12.85          |
| **Pro++**    | 299646        | 119681          | 39.94     | 9.05           |
| **Pro**      | 299646        | 97508           | 32.54     | 1.65           |
| **Normal**   | 299646        | 93258           | 31.12     | 0.23           |
| **Light**    | 299646        | 92576           | 30.90     |                |
| **----**     | 299646        | 67888           | 22.66     | -8.24          |

Test them, give feedback and [report blockable or incorrectly blocked](https://github.com/hagezi/dns-blocklists/issues) domains.

#### :octocat: Repository <a name="repository"></a>

The repository is occasionally compressed (reinitialised) to reduce the overall size. Among other things, this invalidates forks and cleans up the commit history.

#### :cyclone: Referral Domains <a name="referral"></a>

[Why are referral domains (affiliate and tracking links) not blocked in the lists?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)

#### :dizzy: Support Me <a name="support"></a>

If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!

Give feedback, show me your ideas, report domains to be blocked, report false positive domains and help to keep the internet safe and clean.
Help and cooperation of any kind are welcome!

**Thanks for your support!**

---

### :stars: Stargazers <a name="stargazers"></a>

[![Star History Chart](https://api.star-history.com/svg?repos=hagezi/dns-blocklists&type=Date)](https://star-history.com/#hagezi/dns-blocklists&Date)

---

### **Keep the internet clean!**

---

[![https://gafam.info](https://ptrace.gafam.info/unofficial/img/color/lqdn-gafam-poster-en-color-5x1-2560x.png)](https://gafam.info)

---
