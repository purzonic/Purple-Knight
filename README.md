Purple Knight
Introduction

Purple Knight is a free identity security assessment tool developed by Semperis to help IT professionals identify security vulnerabilities, misconfigurations, and indicators of compromise across enterprise identity environments. It is designed primarily for Active Directory (AD), Microsoft Entra ID, and Okta security assessments, providing administrators and cybersecurity teams with practical insights into identity infrastructure risks.

The software performs automated security checks to detect Indicators of Exposure (IOEs) and Indicators of Compromise (IOCs). Indicators of Exposure highlight weaknesses in system configurations that could create opportunities for attackers, while Indicators of Compromise identify suspicious conditions that may indicate malicious activity or previous security breaches. This distinction helps security teams evaluate both preventive security controls and potential signs of unauthorized access.

Purple Knight analyzes identity-related configurations, permissions, privileged accounts, authentication mechanisms, and other security-sensitive components. Its assessment results are presented through a graphical report containing an overall security score, categorized findings, risk information, and actionable remediation recommendations.

Another important capability is the integration of security findings with the MITRE ATT&CK framework. This mapping provides additional context about how identified weaknesses may relate to recognized adversary tactics and techniques. It helps security engineers understand potential attack scenarios and prioritize corrective actions.

Purple Knight is particularly useful for Active Directory security audits, hybrid identity infrastructure assessments, vulnerability management, and proactive security hardening. IT administrators can use it to establish a security baseline, identify configuration weaknesses, investigate suspicious identity-related conditions, and evaluate improvements after remediation. The assessment results also support internal security reviews, risk management activities, and continuous improvement of enterprise identity protection.

How to Run a Purple Knight Security Assessment and Configure Identity Scans

Purple Knight uses a guided assessment workflow that allows administrators to select the identity environment and execute relevant security checks. Before starting an audit, prepare a Windows workstation with appropriate network connectivity to the target environment. Review organizational security policies and ensure that the account used for the assessment has the permissions required for the selected checks.

After launching the application, accept the license terms and select the identity platform to assess. Depending on the available product version, the supported targets include Active Directory, Microsoft Entra ID, and Okta. For an Active Directory assessment, select the appropriate domain or domains and proceed to the security indicator selection stage.

The assessment can include multiple security checks covering different aspects of identity infrastructure. These checks examine configuration weaknesses, account security, privilege management, delegation, authentication, and other relevant security conditions. Select the required indicators or categories according to the audit scope.

Start the assessment and allow Purple Knight to execute its checks. The application collects relevant configuration information and evaluates it against predefined security indicators. The process is designed for security assessment rather than exploitation: it identifies weaknesses without requiring penetration testing against the detected issues.

For example, an administrator auditing a corporate Active Directory environment can use the assessment to identify potentially excessive privileges, risky delegation settings, and insecure account configurations.

After execution, review the generated results and preserve the assessment report. For repeatable security audits, maintain consistent assessment scopes and execution conditions. This makes it easier to compare results, track changes, and establish a measurable baseline for identity security improvements.

How to Analyze Purple Knight Reports and Remediate Security Findings

The Purple Knight security report provides a structured view of identity infrastructure security risks. Its overall security score helps administrators understand the current security posture, while category-level results provide additional visibility into specific areas requiring attention. Individual findings describe detected conditions and include information that helps technical teams investigate and correct identified weaknesses.

Security indicators are divided into Indicators of Exposure (IOEs) and Indicators of Compromise (IOCs). IOEs identify configurations that increase the attack surface, such as excessive permissions, insecure delegation, or insufficient protection of privileged accounts. IOCs highlight suspicious conditions that may indicate unauthorized modifications, malicious persistence, or other signs of compromise. A detected indicator should be investigated in its operational context rather than automatically treated as confirmation of a successful attack.

Each finding should be evaluated according to its severity, affected objects, business impact, and potential attack implications. MITRE ATT&CK mappings provide useful context by connecting security weaknesses with recognized adversary techniques. This information helps security engineers understand why a particular configuration matters and how it could contribute to an identity-based attack.

For example, if an assessment identifies excessive permissions assigned to a service account, administrators should examine its group memberships, access rights, dependencies, and actual business requirements. Corrective actions may include removing unnecessary privileges, restricting delegation, strengthening authentication policies, or disabling obsolete accounts.

After implementing changes, run another Purple Knight assessment using the same scope. Compare the new report with the initial results to verify whether the identified weaknesses have been addressed. Retain historical reports to support security audits, remediation tracking, compliance reviews, and vulnerability management processes.

Purple Knight is an assessment tool, not a replacement for continuous monitoring, incident response, or comprehensive identity threat detection. Its findings should therefore be incorporated into a broader security program that includes regular Active Directory audits, privileged access management, configuration reviews, and ongoing investigation of suspicious identity activity.
