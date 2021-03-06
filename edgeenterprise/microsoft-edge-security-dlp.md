---
title: "Data Loss Prevention in Microsoft Edge"
ms.author: archandr
author: dan-wesley
manager: seanlynd
ms.date: 10/08/2020
audience: ITPro
ms.topic: conceptual
ms.prod: microsoft-edge
ms.localizationpriority: high
ms.collection: M365-modern-desktop
description: "Data Loss Prevention (DLP) in Microsoft Edge"
---

# Data Loss Prevention (DLP) in Microsoft Edge

Data loss prevention (DLP) is a system of technologies that identify and safeguard sensitive enterprise data from unauthorized disclosure. To comply with business standards and industry regulations, organizations must protect sensitive information and prevent its unauthorized disclosure. Sensitive information includes financial data or personally identifiable information (PII) such as credit card numbers, social security numbers, or health records, among many other things.

Remote work has increased the emphasis on using DLP. With the growing use of personal and work activities on devices, enterprises are seeing an increased risk of unauthorized sharing of corporate data outside the workplace.

This blending of user activities has spread to devices as well, where data is moved between personal and corporate devices over a variety of public and private networks. The net result is a dramatically increased risk of exposing sensitive data.

Microsoft Edge natively supports two different DLP solutions, Microsoft Endpoint DLP and Windows Information Protection (WIP).

## Microsoft Endpoint DLP

Microsoft Endpoint DLP is the next generation of DLP using modern concepts such as data-centric protection. It's  built-in to Windows 10 and Microsoft Edge so it doesn't need additional agents or plugins on the device. To learn more about endpoint DLP, read [Learn about Microsoft 365 Endpoint data loss prevention](https://docs.microsoft.com/microsoft-365/compliance/endpoint-dlp-learn-about?view=o365-worldwide).

> [!NOTE]
> This applies to Microsoft Edge version 85 or later.

Microsoft Edge enforces admin configured policies for sensitive files and records audit events for non-compliant activities.

Some of the user activities that you can audit and manage on devices running Windows 10 include the following activities:

- File Upload: Protect sensitive file upload to unauthorized cloud locations. The next 3 screenshots show a sequence where a user tries to drop a sensitive data file on to their local storage.
- Clipboard Protection: Protect sensitive data from being copied out of the file.
- Print Protection: Protect sensitive file from being printed.
- Save to USB/Network: Protect sensitive file from being saved to removable USB storage or unauthorized network locations.

For more detailed information about user activities you can audit and manage, see [Endpoint activities you can monitor and take action on](https://docs.microsoft.com/microsoft-365/compliance/endpoint-dlp-learn-about?view=o365-worldwide#endpoint-activities-you-can-monitor-and-take-action-on).

## Windows Information Protection

Check out [Support for Windows Information Protection](https://docs.microsoft.com/deployedge/microsoft-edge-security-windows-information-protection), which describes how Microsoft Edge supports Windows Information Protection (WIP). You can learn moe about system requirements, benefits, and supported features in the following sections:

- [System Requirements](https://docs.microsoft.com/deployedge/:microsoft-edge-security-windows-information-protection#system-requirements)
- [Windows Information Protection Benefits](https://docs.microsoft.com/deployedge/microsoft-edge-security-windows-information-protection#windows-information-protection-benefits)
- [WIP features supported in Microsoft Edge](https://docs.microsoft.com/DeployEdge/microsoft-edge-security-windows-information-protection#wip-features-supported-in-microsoft-edge)

## See also

- [Microsoft Edge Enterprise landing page](https://aka.ms/EdgeEnterprise)
- [Video: Data loss prevention - Microsoft Edge](https://www.youtube.com/watch?v=dLD04U9eTqg)
- [Overview of data loss prevention](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide)
- [Protect your enterprise data using Windows Information Protection](https://docs.microsoft.com/windows/security/information-protection/windows-information-protection/protect-enterprise-data-using-wip)
