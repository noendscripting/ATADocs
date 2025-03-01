---
title: What is Microsoft Defender for Identity?
description: Explains what Microsoft Defender for Identity is and what kinds of suspicious activities it can detect
ms.date: 01/29/2023
ms.topic: overview
---

# What is Microsoft Defender for Identity?

Microsoft Defender for Identity is a cloud-based security solution that uses your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.

Defender for Identity enables SecOp analysts and security professionals struggling to detect advanced attacks in hybrid environments to:

- Monitor users, entity behavior, and activities with learning-based analytics
- Protect user identities and credentials stored in Active Directory
- Identify and investigate suspicious user activities and advanced attacks throughout the kill chain
- Provide clear incident information on a simple timeline for fast triage

Defender for Identity was formerly known as Azure Advanced Threat Protection (Azure ATP).

[!INCLUDE [automatic-redirect](../includes/automatic-redirect.md)]

## Monitor and analyze user behavior and activities

Defender for Identity monitors and analyzes user activities and information across your network, such as permissions and group membership, creating a behavioral baseline for each user. Defender for Identity then identifies anomalies with adaptive built-in intelligence, giving you insights into suspicious activities and events, revealing the advanced threats, compromised users, and insider threats facing your organization. Defender for Identity's proprietary sensors monitor organizational domain controllers, providing a comprehensive view for all user activities from every device.

## Protect user identities and reduce the attack surface

Defender for Identity provides you with invaluable insights on identity configurations and suggested security best-practices. Through security reports and user profile analytics, Defender for Identity helps dramatically reduce your organizational attack surface, making it harder to compromise user credentials, and advance an attack. Defender for Identity's *Lateral Movement Paths* help you quickly understand exactly how an attacker can move laterally inside your organization to compromise sensitive accounts and helps preventing those risks in advance. Defender for Identity security reports help you identify users and devices that authenticate using clear-text passwords and provide extra insights to improve your organizational security posture and policies.

## Protecting the AD FS in hybrid environments

Active Directory Federation Services (AD FS) plays important role in today's infrastructure when it comes to authentication in hybrid environments. Defender for Identity protects the AD FS in your environment by detecting on-premises attacks on the AD FS and providing visibility into authentication events generated by the AD FS. For more information, see [Microsoft Defender for Identity on Active Directory Federation Services (AD FS)](active-directory-federation-services.md).

## Identify suspicious activities and advanced attacks across the cyber-attack kill-chain

Typically, attacks are launched against any accessible entity, such as a low-privileged user, and then quickly move laterally until the attacker gains access to valuable assets – such as sensitive accounts, domain administrators, and highly sensitive data. Defender for Identity identifies these advanced threats at the source throughout the entire cyber-attack kill chain:

### Reconnaissance

Identify rogue users and attackers' attempts to gain information. Attackers are searching for information about user names, users' group membership, IP addresses assigned to devices, resources, and more, using various methods.

### Compromised credentials

Identify attempts to compromise user credentials using brute force attacks, failed authentications, user group membership changes, and other methods.

### Lateral movements

Detect attempts to move laterally inside the network to gain further control of sensitive users, utilizing methods such as Pass the Ticket, Pass the Hash, Overpass the Hash and more.

### Domain dominance

Highlighting attacker behavior if domain dominance is achieved, through remote code execution on the domain controller, and methods such as DC Shadow, malicious domain controller replication, Golden Ticket activities, and more.

## Investigate alerts and user activities

Defender for Identity is designed to reduce general alert noise, providing only relevant, important security alerts in a simple, real-time organizational attack timeline. The Defender for Identity attack timeline view allows you to easily stay focused on what matters, using the intelligence of smart analytics. Use Defender for Identity to quickly investigate threats, and gain insights across the organization for users, devices, and network resources. Seamless integration with Microsoft Defender for Endpoint provides another layer of enhanced security by extra detection and protection against advanced persistent threats on the operating system.

## More resources for Defender for Identity

### Start a free trial

[https://signup.microsoft.com/Signup?OfferId=87dd2714-d452-48a0-a809-d2f58c4f68b7&ali=1](https://signup.microsoft.com/Signup?OfferId=87dd2714-d452-48a0-a809-d2f58c4f68b7&ali=1 "Enterprise Mobility + Security E5")

### Defender for Identity roadmap

[See the upcoming roadmap for Defender for Identity](https://www.microsoft.com/microsoft-365/roadmap?filters=Microsoft%20Defender%20for%20Identity)

### Follow Defender for Identity on Microsoft Tech Community

[https://aka.ms/MDIcommunity](https://aka.ms/MDIcommunity "Defender for Identity on Microsoft Tech Community")

### Join the Defender for Identity Yammer community

[https://www.yammer.com/azureadvisors/#/threads/inGroup?type=in_group&feedId=9386893](https://www.yammer.com/azureadvisors/#/threads/inGroup?type=in_group&feedId=9386893 "Defender for Identity Yammer community")

### Defender for Identity blog

[Defender for Identity blog](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/bg-p/MicrosoftSecurityandCompliance/label-name/Microsoft%20Defender%20for%20Identity)

### Visit the Defender for Identity product page

[https://www.microsoft.com/microsoft-365/security/identity-defender](https://www.microsoft.com/microsoft-365/security/identity-defender "Defender for Identity product page")

### Learn more about Defender for Identity architecture

[Defender for Identity Architecture](architecture.md)

### Frequently asked questions

[Defender for Identity Frequently Asked Questions](technical-faq.yml)

### Watch our videos

[Bolster your security posture with Defender for Identity](<https://techcommunity.microsoft.com/t5/video-hub/bolster-your-security-posture-with-microsoft-defender-for/m-p/1698841>) - Identify and proactively resolve known bad-practices, leaving your environment in a healthier state and more resilient to bad actors. Watch the [YouTube video](https://youtu.be/nx5rrxVuRTk).

[Incident Investigation with Defender for Identity](<https://techcommunity.microsoft.com/t5/video-hub/incident-investigation-with-microsoft-defender-for-identity/m-p/1698840>) - Learn how to Detect, investigate, and respond to advanced threats targeting identities and domain controllers with Defender for Identity. Starting with an alert in Defender for Identity, we demonstrate how that information is correlated into an incident, how to hunt for threats using information captured by Defender for Identity and how we can initiate an automatic incident response to remediate the incident before it evolves into a bigger problem. Watch the [YouTube video](https://youtu.be/geWU4It6S48).

## What's next?

Get started with [Deploy Microsoft Defender for Identity with Microsoft 365 Defender](deploy-defender-identity.md).

## See also

- [Licensing and privacy](/defender-for-identity/technical-faq#licensing-and-privacy)
- [Defender for Identity frequently asked questions](technical-faq.yml)
- [Working with security alerts](/defender-for-identity/manage-security-alerts)
- [Check out the Defender for Identity forum!](<https://aka.ms/MDIcommunity>)
