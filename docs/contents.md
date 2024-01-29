| [Home](../README.md) |
|----------------------|

# Contents

The **Outbreak Response - JetBrains TeamCity Authentication Bypass Attack** solution pack contains the following resources.

## Outbreak Alerts Record set 

| Name                                            | Description                                                                                                                                                                                                                                                                                                                                                                                                         |
|:------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| JetBrains TeamCity Authentication Bypass Attack | A simulated outbreak alert created in FortiSOAR&trade that simulates the critical security vulnerability in TeamCity, a popular Continuous Integration and Continuous Deployment (CI/CD) server from JetBrains. This flaw could enable an unauthenticated attacker with HTTP(S) access to a TeamCity server to perform a remote code execution (RCE) attack and gain administrative control of the TeamCity server. |

## Threat Hunt Rules Record set 

| Name                                                                                                     | Rule Type       |
|:---------------------------------------------------------------------------------------------------------|:----------------|
| FortiAnalyzer Threat Hunting - Outbreak Alert - JetBrains TeamCity RCE Event-Handler                     | Fortinet Fabric |
| FortiSIEM Threat Hunting - Outbreak: JetBrains TeamCity Authentication Bypass Attack Detected on Network | Fortinet Fabric |
| FortiSIEM Threat Hunting - Outbreak: JetBrains TeamCity Authentication Bypass Attack Detected on Host    | Fortinet Fabric |
| Security Tools Keyword Lookup Via `Findstr.exe`                                                          | Sigma           |
| Diamond Sleet APT Scheduled Task Creation - Registry                                                     | Sigma           |
| Diamond Sleet APT File Creation Indicators                                                               | Sigma           |
| Diamond Sleet APT DLL Side-loading Indicators                                                            | Sigma           |
| Onyx Sleet APT File Creation Indicators                                                                  | Sigma           |
| Diamond Sleet APT Process Activity Indicators                                                            | Sigma           |



# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|