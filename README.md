# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 
 

# Overview 
Multiple Threat actors seen exploiting the authentication bypass flaw in **JetBrains TeamCity** that could lead to remote code execution. If compromised, they can access a TeamCity server, gaining entry to a software developer's source code, signing certificates, and the power to manipulate software building and deployment procedures. This access could also be misused by these malicious actors to carry out supply chain operations.

The **Outbreak Response JetBrains Authentication Bypass Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.0.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

## Background
TeamCity is a continuous integration/continuous deployment (CI/CD) application used by organizations for DevOps and other software development activities. Software developers use TeamCity software to manage and automate software compilation, building, testing, and releasing.

## Announced:
September 6, 2023: Researchers from Sonar discovered a critical TeamCity On-Premises vulnerability (CVE-2023-42793).

September 20, 2023: JetBrains released the advisory and hot fixes for the vulnerability.
https://blog.jetbrains.com/teamcity/2023/09/critical-security-issue-affecting-teamcity-on-premises-update-to-2023-05-4-now/

September 27, 2023: A public exploit for this vulnerability was released by Rapid7.

In mid-October 2023, the FortiGuard Incident Response (IR) team was engaged to investigate a compromised organization's network. See full details on the blog;
https://www.fortinet.com/blog/threat-research/teamcity-intrusion-saga-apt29-suspected-exploiting-cve-2023-42793

Oct 18, 2023: Microsoft Threat Intelligence reported that multiple North Korean threat actors exploiting the TeamCity CVE-2023-42793 vulnerability
https://www.microsoft.com/en-us/security/blog/2023/10/18/multiple-north-korean-threat-actors-exploiting-the-teamcity-cve-2023-42793-vulnerability/

## Latest Developments:
December 13, 2023: FortiGuard Labs released a detailed threat research on a different threat actor, (APT-29) exploiting CVE-2023-42793 https://www.fortinet.com/blog/threat-research/teamcity-intrusion-saga-apt29-suspected-exploiting-cve-2023-42793

December 13, 2023: CISA and Partners Release Advisory on Russian SVR-affiliated Cyber Actors Exploiting CVE-2023-42793 https://www.cisa.gov/news-events/alerts/2023/12/13/cisa-and-partners-release-advisory-russian-svr-affiliated-cyber-actors-exploiting-cve-2023-42793 

According to CISA's advisory, as a result of this latest SVR cyber activity, they identified a few dozen compromised companies in the United States, Europe, Asia, and Australia and the Identified victims included: an energy trade association; companies that provide software for billing, medical devices, customer care, employee monitoring, financial management, marketing, sales, and video games; as well as hosting companies, tools manufacturers, and small and large IT companies.


# Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|--------------------------------|