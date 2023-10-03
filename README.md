# AD Invaders: Unmasking and Defeating Post-Exploitation Tactics

## Introduction to Active Directory Post-Exploitation

Welcome to BSides Orlando 2023! This is going to be an intense 4 hours, but my commitment to you is that everyone will get something out of this. Whether red team, blue team, or just here for the lolz.

This is an _extremely_ hands on workshop. However, the lab is hosted over the internet by Pluralsight **FOR FREE** (thanks Pluralsight!). Each of you will get an individual lab environment, but it does take some setup from you.

To get started, **please proceed to the [Setup](./0_setup/README.md) page for lab environment instructions.**

## The Flow

In this workshop, you will act as the threat actor (TA) breaking into an environment via Remote Desktop Protocol (RDP). We are not focusing on the method by which the TA (that's _you!_) accessed the environment. Rather, our focus is on the attacks that will be carried out against Active Directory (AD). After all, this is a workshop on AD attacks!

All of the information you need to follow along with the workshop, is included in the following sections:

### [1. Active Directory Credential Grabbing](./1_ad_credential_grabbing/)

The TA will obtain access to the network via a local administrator account. As such, the TA (again, that's _you!_) does not have access to a domain account. In order to enumerate the AD environment, the TA will need to obtain access to a domain account. That is exactly what you will be doing in this section.

### [2. Active Directory Enumeration](./2_enumeration/)

Once the TA obtains access to a domain account, they will begin AD enumeration. We will begin enumeration using common methodologies, which of course are easily detectable. After showing you how to detect these methods, we will move to a more advanced methodology.

### [3. Active Directory Kerberoasting](./3_kerberoasting/)

One of the most common attacks against AD is an attack on Kerberos known as Kerberoasting. In this section, you will learn how to perform a Kerberoasting attack using common tools. You will then learn how to perform a much more stealth version of this attack.

## Shoutout! 

This wasn't the first time this workshop has been presented. DEF CON graciously allowed me and two other brilliant individuals to present this year and I want to give special thanks to those two for their effort in putting this together:
- [Aaron Rosenmund](https://aaronrosenmund.com/about/)
- [Ryan Chapman](https://incidentresponse.training/)

## Socials

A little about me:
- [Website](https://www.devaultsecurity.com)
- [LinkedIn](https://www.linkedin.com/in/brandondevault/)
- [My Pluralsight Courses](https://app.pluralsight.com/profile/author/brandon-devault)
