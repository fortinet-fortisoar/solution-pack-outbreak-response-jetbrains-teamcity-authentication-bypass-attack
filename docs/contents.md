| [Home](../README.md) |
|----------------------|

# Contents

The **Outbreak Response - JetBrains TeamCity Authentication Bypass Attack** solution pack contains the following resources.

## Outbreak Alerts Recordset 

| Name               | Description                                                                                                                                                                                                                                        |
|:-------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| JetBrains TeamCity Authentication Bypass Attack | Multiple Threat actors seen exploiting the authentication bypass flaw in JetBrains TeamCity that could lead to remote code execution. If compromised, they can access a TeamCity server, gaining entry to a software developer's source code, signing certificates, and the power to manipulate software building and deployment procedures. This access could also be misused by these malicious actors to carry out supply chain operations. |

## Threat Hunt Rules Recordset 

| Name                                              | Rule Type       |
|:--------------------------------------------------|:----------------|
| FortiAnalyzer Threat Hunting - Outbreak Alert - JetBrains TeamCity RCE Event-Handler | Fortinet Fabric |
| FortiSIEM Threat Hunting - Outbreak: JetBrains TeamCity Authentication Bypass Attack Detected on Network  | Fortinet Fabric |
| FortiSIEM Threat Hunting - Outbreak: JetBrains TeamCity Authentication Bypass Attack Detected on Host     | Fortinet Fabric |
| Security Tools Keyword Lookup Via Findstr.EXE     | Sigma |
| Diamond Sleet APT Scheduled Task Creation - Registry     | Sigma |
| Diamond Sleet APT File Creation Indicators     | Sigma |
| Diamond Sleet APT DLL Sideloading Indicators     | Sigma |
| Onyx Sleet APT File Creation Indicators | Sigma |
| Diamond Sleet APT Process Activity Indicators | Sigma |



# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|