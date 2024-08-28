---
title: Latest IPv6-Related Security Flaw Affects Windows Desktop Computers
date: 2024-08-26 22:38:16
updated: 2024-08-29 12:42:43
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/windows-11-logo.jpg
---

## Latest IPv6-Related Security Flaw Affects Windows Desktop Computers

Security updates are an important way to keep your devices safe, and if you have a Windows PC, you'll definitely want to install any available updates. Microsoft is now patching a significant vulnerability caused by the IPv6 stack in Windows.

 Microsoft has confirmed a critical vulnerability in its TCP/IP protocol that could allow remote attackers to execute code on all Windows systems using [IPv6](https://eaxpv-info.techidaily.com/updated-boosting-sales-through-effective-strategies-for-channel-trailer-creation-for-2024/). The vulnerability, identified as CVE-2024-38063, is particularly concerning as IPv6 is enabled by default on most Windows installations. The flaw, discovered by Kunlun Lab's XiaoWei, stems from an integer underflow weakness. Attackers could exploit this to trigger buffer overflows, paving the way for arbitrary code execution. XiaoWei has refrained from disclosing more details for now as to complicate malicious actors taking advantage of it.

 Microsoft has classified the vulnerability as "exploitation more likely," indicating a high probability of threat actors developing exploit code. It's not clear if this is being exploited in the wild right now (and how widespread it is), but ideally, the problem should be patched before people actually get hurt. While disabling IPv6 can mitigate the risk, Microsoft advises against it. IPv6 is a core component of modern Windows versions, and disabling it could impact system functionality.

 Dustin Childs, Head of Threat Awareness at Trend Micro's Zero Day Initiative, also labeled it as "wormable," meaning it could spread between vulnerable systems without user interaction. Although this isn't the first IPv6-related vulnerability in Windows, its ease of exploitation makes it particularly dangerous. What makes a vulnerability dangerous is not only how much it can actually wreak havoc, but also how easy it is for someone to gain access to it.

 If you haven't updated your computer in a while, you'll want to do so as soon as you get the chance before something catastrophic happens. Make sure your computer is fully updated with all the latest security patches.

 Source: [Bleeping Computer](https://www.bleepingcomputer.com/news/microsoft/zero-click-windows-tcp-ip-rce-impacts-all-systems-with-ipv6-enabled-patch-now/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
