# Security Policy — School Guardian

**Project:** School Guardian  
**Organization:** school-guardian-project  
**Version:** 1.0

---

## 1. Purpose

This policy establishes the guidelines for identifying, reporting, assessing, and managing security vulnerabilities that may affect School Guardian and the technological components that are part of its infrastructure.

Its purpose is to promote responsible vulnerability disclosure, protect the information managed by the platform, and maintain the confidentiality, integrity, and availability of its services.

## 2. Scope

This policy applies to the repositories, applications, services, software components, and technological infrastructure that are part of School Guardian and are under the administration of the `school-guardian-project` organization.

It includes, but is not limited to:

- Backend applications and services.
- Mobile applications and user-facing clients.
- API Gateway and authentication and authorization mechanisms.
- Databases and persistence components.
- Deployment infrastructure and configuration.
- Third-party dependencies and components integrated into the platform.

This policy does not grant authorization to access, modify, test, or interfere with systems, data, or services without the appropriate permission.

## 3. Security Principles

School Guardian's security management is guided by the following principles:

- **Confidentiality:** Protect information against unauthorized access or disclosure.
- **Integrity:** Prevent unauthorized modification, alteration, or deletion of information.
- **Availability:** Endeavor to keep services and technological resources available to authorized users.
- **Least privilege:** Grant only the permissions necessary for each role or function.
- **Defense in depth:** Apply complementary security controls across the different layers of the architecture.
- **Traceability:** Maintain records that allow relevant security events to be investigated and understood.
- **Responsible disclosure:** Manage vulnerability reports in a coordinated and controlled manner.

## 4. Vulnerability Reporting

Anyone who identifies a potential vulnerability affecting School Guardian should report it to the project maintainers through the official security reporting channel.

**Official reporting channel:** Pending definition.

Until this channel is established, technical details of vulnerabilities that could facilitate exploitation must not be publicly disclosed. Credentials and confidential project information must not be exposed.

### 4.1. Recommended Report Information

Whenever possible, a report should include:

- Description of the identified vulnerability.
- Affected repository, service, or component.
- Steps required to reproduce the behavior.
- Technical evidence that helps explain the issue.
- Potential impact on the platform or its users.
- Possible mitigation measures, if known.

Reports must not include real personal data, credentials, access tokens, or sensitive user information. When evidence is required to demonstrate an issue, fictitious data or authorized test environments must be used.

## 5. Report Handling

School Guardian's maintainers will assess submitted reports and determine the appropriate actions.

The handling process includes the following stages:

1. **Acknowledgment:** Record the information provided about the potential vulnerability.
2. **Assessment:** Verify its existence, scope, reproducibility, and impact.
3. **Prioritization:** Determine the urgency of remediation based on the identified risk.
4. **Mitigation:** Establish and implement the necessary measures to reduce or eliminate the risk.
5. **Verification:** Confirm that the vulnerability has been fixed or that the risk is under control.
6. **Closure:** Document the actions taken and close the report when appropriate.

The priority assigned to a report will depend on factors such as the impact on information, exploitability, required privileges, and affected components.

## 6. Responsible Disclosure

Information related to security vulnerabilities must be handled confidentially while the issue is being assessed and addressed.

Individuals reporting vulnerabilities are expected to:

- Avoid publicly disclosing technical information that could enable exploitation before coordinating with the project maintainers.
- Avoid accessing information belonging to users, schools, or third parties.
- Avoid extracting, modifying, deleting, or disclosing data.
- Avoid disrupting services or affecting platform operations.
- Avoid using the vulnerability for personal or third-party gain.
- Avoid sharing credentials, tokens, private configurations, or other secrets discovered during the investigation.

School Guardian will endeavor to handle good-faith reports appropriately and maintain reasonable communication with the reporter whenever possible.

## 7. Security Research and Testing

Security testing of School Guardian systems must only be conducted in environments and on components for which explicit authorization has been granted.

The existence of this policy does not constitute general authorization to perform penetration testing, automated scanning, vulnerability exploitation, or any other activity against production services.

Any security assessment activity must have a defined scope and prior authorization from the appropriate project maintainers.

## 8. Incident Management

When a security incident is confirmed, the project maintainers must assess its scope and take the necessary measures to contain it, investigate it, and reduce its consequences.

Depending on the nature of the incident, actions may include:

- Revoking or rotating compromised credentials.
- Temporarily restricting access.
- Correcting insecure configurations.
- Applying updates or security patches.
- Restoring affected services.
- Analyzing available technical logs.
- Documenting the actions and decisions taken.

When an incident may compromise personal information, applicable legal and contractual obligations must be assessed, including any required communication or notification measures.

## 9. Information and Credential Protection

Individuals with authorized access to School Guardian repositories or components must protect confidential information and authentication mechanisms to which they have access.

The following actions are prohibited:

- Publishing passwords, private keys, access tokens, or secrets in repositories.
- Sharing access credentials with unauthorized individuals.
- Including real personal data in tests or code examples without authorization and justification.
- Storing confidential information in unauthorized external services.
- Using granted access for purposes other than those authorized.

Any accidental exposure of credentials or sensitive information must be reported immediately through the appropriate channel.

## 10. Third-Party Dependencies and Components

Third-party dependencies and components used by School Guardian must be evaluated considering their origin, maintenance status, licensing, and known vulnerabilities.

When a vulnerability is identified in a dependency, the technical maintainers will assess its impact on affected components and determine whether the component should be updated, replaced, reconfigured, or mitigated.

The addition of new dependencies must follow the project's architecture and dependency management policies.

## 11. Scope of Protection and Limitations

School Guardian does not guarantee that its systems are completely free of vulnerabilities or security incidents.

The project will endeavor to apply reasonable technical and organizational measures to prevent, detect, and manage risks, as well as continuously improve its security practices.

Submitting a report does not guarantee a financial reward, contractual relationship, specific recognition, or additional access permissions. Any specific recognition or agreement must be expressly established.

## 12. Policy Violations

Failure to comply with this policy may result in the suspension or revocation of access permissions to the project's repositories, services, or resources.

Where appropriate, the circumstances may be assessed in accordance with applicable agreements and current legislation.

## 13. Related Documents

This policy should be interpreted together with the applicable School Guardian documents, including:

- `GOVERNANCE.md`
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `LICENSE`
- `ARCHITECTURE-POLICY.md`
- `DEVELOPMENT-STANDARDS.md`
- `DEPENDENCY-POLICY.md`

## 14. Administration and Review

The administration of this policy is the responsibility of the authorized maintainers of the `school-guardian-project` organization.

This document must be reviewed whenever relevant changes occur in the architecture, infrastructure, security mechanisms, development processes, or applicable legal requirements.

**Document owner**: School Guardian Organization Team (school-guardian-project).
**Responsible team**: Organization Team.
**Document date**: November 2, 2026.
**Last updated**: November 2, 2026.
**Review**: Whenever significant changes occur in the project's architecture, infrastructure, security mechanisms, development processes, or applicable requirements.
**Approval authority**: School Guardian Organization Team.
