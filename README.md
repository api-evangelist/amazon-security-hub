# Amazon Security Hub
AWS Security Hub is a cloud security posture management service that provides a comprehensive view of your security state across AWS accounts. It aggregates, organizes, and prioritizes security findings from multiple AWS services and third-party tools, enabling centralized security monitoring, compliance checking, and automated remediation workflows.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/security-hub/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Compliance, Monitoring, Security

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### AWS Security Hub API
The AWS Security Hub API provides programmatic access to manage centralized security findings across your AWS environment. It enables developers to import and manage security findings, configure security standards and controls, manage integrations with other AWS services and third-party tools, and automate security workflows.

**Human URL:** [https://docs.aws.amazon.com/securityhub/latest/APIReference/](https://docs.aws.amazon.com/securityhub/latest/APIReference/)

#### Tags:

 - AWS, Compliance, Monitoring, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/securityhub/latest/APIReference/)
- [OpenAPI](openapi/amazon-security-hub-openapi.yml)
- [JSONSchema](json-schema/amazon-security-hub-finding-schema.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [GettingStarted](https://aws.amazon.com/security-hub/getting-started/)
- [Documentation](https://docs.aws.amazon.com/securityhub/)
- [APIReference](https://docs.aws.amazon.com/securityhub/latest/APIReference/)
- [Console](https://console.aws.amazon.com/securityhub/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Pricing](https://aws.amazon.com/security-hub/pricing/)
- [FAQ](https://aws.amazon.com/security-hub/faqs/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/premiumsupport/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [GitHubOrganization](https://github.com/aws)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-security-hub)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [SpectralRules](rules/amazon-security-hub-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-security-hub-vocabulary.yaml)
- [NaftikoCapability](capabilities/cloud-security-posture.yaml)
- [JSON-LD](json-ld/amazon-security-hub-context.jsonld)
- [JSONStructure](json-structure/amazon-security-hub-finding-structure.json)
- [Example](examples/amazon-security-hub-finding-example.json)
- [NaftikoCapability](capabilities/shared/amazon-security-hub.yaml)

## Features

| Name | Description |
|------|-------------|
| Multi-Account Findings Aggregation | Aggregate security findings from across multiple AWS accounts and regions into a single pane of glass. |
| AWS Security Finding Format (ASFF) | Standardized JSON format for all security findings enabling consistent analysis and automation. |
| Built-in Compliance Standards | Automated compliance checks against CIS AWS Foundations, PCI DSS, NIST, SOC 2, and AWS Foundational Security Best Practices. |
| Third-Party Integrations | Ingest findings from 80+ third-party security partners including CrowdStrike, Palo Alto Networks, and Splunk. |
| Automated Remediation | Trigger automated remediation via Amazon EventBridge and AWS Security Hub automated response and remediation. |
| Security Insights | Correlated views of security findings to highlight areas needing attention. |
| Custom Actions | Create custom actions to send findings to ticketing, chat, and SOAR platforms. |
| Cross-Region Aggregation | Aggregate findings across multiple AWS regions into a designated aggregation region. |

## Use Cases

| Name | Description |
|------|-------------|
| Cloud Security Posture Management | Continuously monitor your AWS environment for security misconfigurations and compliance gaps. |
| Compliance Reporting | Automate compliance checks and generate reports for CIS, PCI DSS, NIST, and other frameworks. |
| Multi-Account Security Operations | Centralize security monitoring across dozens or hundreds of AWS accounts in an organization. |
| Threat Detection Aggregation | Aggregate findings from GuardDuty, Inspector, Macie, and third-party tools in one place. |
| Automated Incident Response | Trigger automated remediation workflows when critical findings are detected. |
| Security Tool Consolidation | Replace multiple point solutions with centralized finding aggregation and normalized data. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon GuardDuty | Native integration to ingest GuardDuty threat detection findings. |
| Amazon Inspector | Aggregate Inspector vulnerability assessment findings. |
| Amazon Macie | Ingest Macie sensitive data discovery findings. |
| AWS Config | Integration with Config rules for configuration compliance findings. |
| Amazon EventBridge | Trigger automated remediation and notification workflows based on findings. |
| AWS Lambda | Execute custom remediation actions in response to security findings. |
| AWS Organizations | Enable Security Hub across all accounts in an AWS Organization. |
| CrowdStrike | Third-party integration for endpoint detection and response findings. |
| Splunk | Export Security Hub findings to Splunk SIEM for advanced analysis. |
| Palo Alto Networks | Ingest Prisma Cloud and other Palo Alto findings via Security Hub integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-security-hub-openapi.yml](openapi/amazon-security-hub-openapi.yml)

### JSON Schema

- [amazon-security-hub-finding-schema.json](json-schema/amazon-security-hub-finding-schema.json)

### JSON Structure

- [amazon-security-hub-finding-structure.json](json-structure/amazon-security-hub-finding-structure.json)

### JSON-LD

- [amazon-security-hub-context.jsonld](json-ld/amazon-security-hub-context.jsonld)

### Examples

- [amazon-security-hub-finding-example.json](examples/amazon-security-hub-finding-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-security-hub.yaml](capabilities/shared/amazon-security-hub.yaml)

### Workflow Capabilities

- [cloud-security-posture.yaml](capabilities/cloud-security-posture.yaml)

## Vocabulary

- [amazon-security-hub-vocabulary.yaml](vocabulary/amazon-security-hub-vocabulary.yaml)

## Rules

- [amazon-security-hub-spectral-rules.yml](rules/amazon-security-hub-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

