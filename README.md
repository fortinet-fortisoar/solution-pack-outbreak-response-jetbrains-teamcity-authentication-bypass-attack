# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 
 

# Overview 

The *JetBrains TeamCity Authentication Bypass Vulnerability* or [CVE-2023-42793](https://cve.report/CVE-2023-42793), is a critical security vulnerability in TeamCity, a popular Continuous Integration and Continuous Deployment (CI/CD) server from JetBrains. The discovered vulnerability allows unauthenticated attackers to execute arbitrary code on the TeamCity server via remote code execution (RCE). Attackers could leverage this access to steal source code, service secrets, and private keys, control attached build agents, and corrupt build-artifacts.

The **Outbreak Response JetBrains Authentication Bypass Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.0.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/jetbrains-teamcity-rce) contains detailed information about **Outbreak Response JetBrains Authentication Bypass Attack**.

## Background

TeamCity is a widely used Continuous Integration and Continuous Deployment (CI/CD) server from JetBrains deployed by more than 30,000 customers worldwide. The application can either be used via the cloud-hosted solution TeamCity Cloud, or a self-hosted solution via TeamCity on-premises. According to [*Shodan*](https://www.shodan.io/), more than 3,000 of these on-premises servers are directly exposed to the Internet.

CI/CD servers like TeamCity help automate the process of building, testing, and deploying software applications. Hence, these servers have access to one of the most valuable assets of a company: source code. Since they are responsible for building and deploying source code, they store sensitive secrets and keys, control the build artifacts, and are an integral part of a software release. As a result, CI/CD servers become a high-value target for attackers.

## Announced:

- September 6, 2023: Sonar researchers discovered a critical TeamCity On-Premises vulnerability (CVE-2023-42793).

- September 20, 2023: JetBrains released the advisory and hotfixes for the vulnerability.
https://blog.jetbrains.com/teamcity/2023/09/critical-security-issue-affecting-teamcity-on-premises-update-to-2023-05-4-now/

- September 27, 2023: Rapid7 released a public exploit for this vulnerability.

- In mid-October 2023, the FortiGuard Incident Response (IR) team investigated a compromised organization's network. See full details on the blog;
https://www.fortinet.com/blog/threat-research/teamcity-intrusion-saga-apt29-suspected-exploiting-cve-2023-42793

- October 18, 2023: Microsoft Threat Intelligence reported that multiple North Korean threat actors exploiting the TeamCity CVE-2023-42793 vulnerability
https://www.microsoft.com/en-us/security/blog/2023/10/18/multiple-north-korean-threat-actors-exploiting-the-teamcity-cve-2023-42793-vulnerability/

## Latest Developments:

- December 13, 2023: FortiGuard Labs released detailed threat research on a different threat actor, (APT-29) exploiting CVE-2023-42793 https://www.fortinet.com/blog/threat-research/teamcity-intrusion-saga-apt29-suspected-exploiting-cve-2023-42793

- December 13, 2023: CISA and Partners Release Advisory on Russian SVR-affiliated Cyber Actors Exploiting CVE-2023-42793 https://www.cisa.gov/news-events/alerts/2023/12/13/cisa-and-partners-release-advisory-russian-svr-affiliated-cyber-actors-exploiting-cve-2023-42793 

CISA issued an advisory, as a result of this latest SVR (associated with Russian Foreign Intelligence Service) cyber activity, where they identified a few dozen compromised companies in the United States, Europe, Asia, and Australia. The victims included an energy trade association, companies that provide software for billing, medical devices, customer care, employee monitoring, financial management, marketing, sales, and video games; as well as hosting companies, tools manufacturers, and small and large IT companies.


# Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|--------------------------------|