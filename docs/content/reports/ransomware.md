---
title: "Ransomware report"
date: 2021-08-05T13:23:10+03:00
draft: false
description: "Provides information about ransomware simulation on your network"
---

{{% notice info %}}
Check out [the documentation for other reports available in the Infection Monkey]({{< ref "/reports" >}}).
{{% /notice %}}

The Infection Monkey's **Ransomware Report** provides you with information and insight into ransomware simulation on your network.

## Breach

The breach section is showing report of the machines that the ransomware simulation started from, as well as the ip address and starting time.

![Breach](/images/usage/reports/ransomware_report_1_breach.png "Breach")


## Lateral Movement

This section provides information about lateral movement phase of the attack in the network. That mean employing various
techniques in order to exploit other systems in the network.

[See real-world examples on Guardicore's blog.](https://www.guardicore.com/blog/stopping-ransomware-with-segmentation/)


![Lateral Movement](/images/usage/reports/ransomware_report_2_lateral_movement.png "Lateral Movement")


## Attack

Attack section is how much and which files were successfully encryption on the compromised systems.

![Attack](/images/usage/reports/ransomware_report_3_attack.png "Attack")
