# Windows Failed Login Detection Using Wazuh

## Project Overview
This is my first hands-on SOC Analyst project. I used Wazuh SIEM to practise monitoring Windows security events and investigating failed login attempts.

## Objective
To understand how SOC Analysts monitor Windows authentication events and investigate suspicious login activity.

## Tools Used
- Wazuh SIEM
- Ubuntu Linux
- Windows
- Oracle VirtualBox

## Lab Architecture
- Ubuntu: Wazuh Manager
- Windows: Wazuh Agent
- Wazuh Dashboard: Security monitoring and investigation

## Practical Tasks
1. Installed and configured Wazuh Server.
2. Installed Wazuh Agent on Windows.
3. Connected Windows Agent to Wazuh Manager.
4. Verified that the agent was Active.
5. Practised searching for Windows failed login events.

## Important Windows Security Events

| Event ID | Description |
|---|---|
| 4624 | Successful login |
| 4625 | Failed login |

## Detection Query

```text
data.win.system.eventID:4625
```

## Learning Outcomes
- Understanding SIEM monitoring.
- Understanding Windows security events.
- Learning basic security event investigation.
- Understanding Wazuh Agent and Manager communication.

## Screenshots
Add screenshots of:
- Wazuh dashboard
- Active Windows Agent
- Threat Hunting search
- Event details (if matching events were found)

## Conclusion
This project helped me understand the basics of Windows security monitoring using Wazuh and gave me practical experience with a beginner SOC Analyst home lab.

**Project Status:** Practical lab completed.
