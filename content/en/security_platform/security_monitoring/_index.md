---
title: Security Monitoring
kind: documentation
---

## Overview

{{< img src="security_platform/security_monitoring/overview_top.png" alt="Datadog Security Monitoring" >}}

Datadog Security Monitoring unify developer, operation, and security teams through one platform. Use a single dashboard to display DevOps content, business metrics, and security content. Detect threats, like a targeted attack, an IP communicating with your systems which matches a threat intel list, or an insecure configuration, to your application and infrastructure in real time, and notify your team of security issues by email, slack, Jira, PagerDuty, or a webhook.

{{< img src="security_platform/security_monitoring/takeover_ex.png" alt="Slack Example"  style="width:75%;">}}

Threats are surfaced in Datadog as Security Signals and can be correlated and triaged in the [Security Signals Explorer][1]. Security Signals are generated by Datadog Security Monitoring with [Detection Rules][2]. Detection Rules detect threats across different sources and are available out of the box for immediate use. You can clone any of the provided detection rules to change the configuration. You can also add a [new rule][3] from scratch to fit your specific use case.

{{< img src="security_platform/security_monitoring/explorer.png" alt="Security Signals Explorer"  >}}

## Get Started

{{< whatsnext >}}
  {{< nextlink href="/security_platform/security_monitoring/getting_started">}}Get started with Security Monitoring{{< /nextlink >}}
  {{< nextlink href="/security_platform/default_rules">}}Implement default detection rules{{< /nextlink >}}
  {{< nextlink href="/security_platform/detection_rules">}}Learn about creating custom detection rules{{< /nextlink >}}
{{< /whatsnext >}}

[1]: https://app.datadoghq.com/security
[2]: https://app.datadoghq.com/security/configuration/rules
[3]: https://app.datadoghq.com/security/configuration/rules/new