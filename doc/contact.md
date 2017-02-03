---
layout: default
lang: en
title: Contact Me
permalink: /contact/
---

This site is maintained by Matt Rude ([0xc4909ee495b0761f]({{ site.url }}/k/0xc4909ee495b0761f)). If you would like to report any problems or bugs, please send a email or XMPP messsage to the email address listed in one of my public keys.

If you are thankful for this service, please consider donating some funds to the cause. My bitcoin address is `1211xFABAc7W4QELfaGFvEqzUhVF2zbm33`.

### My Public PGP Key Information

**My Default RSA Key:**

    uid = Matt Rude
    pub = rsa2048/95B0761F 2015-03-02
    sub = rsa2048/BC158061 2015-03-02
    fingerprint = 71FD 20E3 2815 8C32 2133  FBBE C490 9EE4 95B0 761F

**My Elliptic Curve Cryptography (ECC) Key:**

    uid = Matt Rude
    pub = nistp256/03305F35 2015-02-15
    fingerprint = 77F1 D65B 5FF0 54DC 9286  6078 0314 CD85 0330 5F35

Or, you may validate my keys using one of my [DANE]({{ site.url }}/guides/dns-dane-cert-records/) or [PKA]({{ site.url }}/guides/public-key-association/) DNS records.

### Signed Contact Information

A signed copy of this infromation may be found [here]({{ site.url }}/contact.txt), or using my [ECC key]({{ site.url }}/k/0x0314CD8503305F35), may be found [here]({{ site.url }}/contact-ecc.txt). You may validate these files by running the below commands:

    curl -s https://keyserver.mattrude.com/contact.txt |gpg --keyserver-options auto-key-retrieve --auto-key-locate pka --verify
    curl -s https://keyserver.mattrude.com/contact-ecc.txt |gpg2 --keyserver-options auto-key-retrieve --auto-key-locate pka --verify

You may also see my profile on [keybase.io/mattrude](https://keybase.io/mattrude).

<!--
## Secure Contact Form

<iframe height="600" width="100%" frameborder="0" src="https://encrypt.to/matt"></iframe>
-->
