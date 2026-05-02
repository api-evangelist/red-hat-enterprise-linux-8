# Red Hat Enterprise Linux 8

Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution that provides a stable, secure, and high-performance operating system platform for modern IT environments. RHEL 8 is managed and accessed programmatically through Red Hat's cloud console APIs, subscription management APIs, security data APIs, and system management interfaces including Insights, Image Builder, and Cockpit. These APIs enable automated provisioning, configuration, security scanning, patch management, and compliance reporting for RHEL deployments at scale.

**URL:** [https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml)

## Tags

Enterprise, Linux, Operating System, Red Hat, RHEL

## APIs

### [RHEL 8 Subscription Management API](https://access.redhat.com/management/api)
The Red Hat Subscription Management (RHSM) API provides programmatic access to manage Red Hat subscriptions, entitlements, and system registrations. Operators can list, activate, and manage subscriptions, query available SKUs, register and unregister systems, and retrieve entitlement certificates.

**Base URL:** `https://api.access.redhat.com/management/v1`

- [Documentation](https://access.redhat.com/management/api/rhsm)
- [OpenAPI](https://api.access.redhat.com/management/v1/openapi.json)
- [Authentication](https://access.redhat.com/articles/3626371)

### [RHEL 8 Insights API](https://console.redhat.com/docs/api/insights)
Red Hat Insights is a predictive analytics service for RHEL systems that provides API access to vulnerability assessment, compliance reporting, patch management, drift analysis, and advisor recommendations.

**Base URL:** `https://console.redhat.com/api/insights/v1`

- [Documentation](https://console.redhat.com/docs/api/insights)
- [OpenAPI](https://console.redhat.com/api/insights/v1/openapi.json)
- [Console](https://console.redhat.com/insights)

### [RHEL 8 Image Builder API](https://console.redhat.com/docs/api/image-builder)
The Red Hat Image Builder API enables automated creation of custom RHEL system images for cloud, virtual machine, and bare-metal deployments. Users can define image compositions, specify packages and customizations, and build images for specific target environments.

**Base URL:** `https://console.redhat.com/api/image-builder/v1`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/composing_a_customized_rhel_system_image/index)
- [OpenAPI](https://console.redhat.com/api/image-builder/v1/openapi.json)
- [Tutorial](https://www.redhat.com/en/blog/using-red-hat-image-builder)

### [RHEL 8 Patch Management API](https://console.redhat.com/docs/api/patch)
The Red Hat Patch Management API (part of Red Hat Insights) provides endpoints for querying available errata, advisories, and CVE patches for registered RHEL systems.

**Base URL:** `https://console.redhat.com/api/patch/v3`

- [Documentation](https://console.redhat.com/docs/api/patch)
- [OpenAPI](https://console.redhat.com/api/patch/v3/openapi.json)

### [RHEL 8 Vulnerability Management API](https://console.redhat.com/docs/api/vulnerability)
The Red Hat Vulnerability Management API (part of Insights) provides programmatic access to CVE vulnerability data for registered RHEL systems. Operators can query known CVEs affecting their hosts, retrieve severity scores, and export vulnerability reports.

**Base URL:** `https://console.redhat.com/api/vulnerability/v1`

- [Documentation](https://console.redhat.com/docs/api/vulnerability)
- [OpenAPI](https://console.redhat.com/api/vulnerability/v1/openapi.json)

### [RHEL 8 Compliance API](https://console.redhat.com/docs/api/compliance)
The Red Hat Compliance API (part of Insights) enables automated compliance scanning and reporting against security profiles such as CIS, DISA STIG, and PCI-DSS for RHEL systems.

**Base URL:** `https://console.redhat.com/api/compliance/v2`

- [Documentation](https://console.redhat.com/docs/api/compliance)
- [OpenAPI](https://console.redhat.com/api/compliance/v2/openapi.json)

### [RHEL 8 Security Data API](openapi/red-hat-enterprise-linux-8-security-data-openapi.yml)
The Red Hat Security Data API provides public access to Red Hat's security advisory and CVE data. Operators can query CVEs affecting RHEL products, retrieve CVSS scores, list security advisories (RHSA), and obtain OVAL XML data for vulnerability scanning integration.

**Base URL:** `https://access.redhat.com/labs/securitydataapi`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/html/red_hat_security_data_api/index)
- [OpenAPI](openapi/red-hat-enterprise-linux-8-security-data-openapi.yml)

### [RHEL 8 Host Inventory API](https://console.redhat.com/docs/api/inventory)
The Red Hat Insights Host Inventory API provides programmatic access to the inventory of RHEL systems registered with Red Hat Insights. Operators can query hosts by attributes, retrieve system facts, manage host groups, and track system metadata.

**Base URL:** `https://console.redhat.com/api/inventory/v1`

- [Documentation](https://console.redhat.com/docs/api/inventory)
- [OpenAPI](https://console.redhat.com/api/inventory/v1/openapi.json)

### [RHEL 8 Cockpit Web Console API](https://cockpit-project.org/guide/latest/api-base1.html)
Cockpit is a web-based system management interface for RHEL that exposes internal D-Bus and system APIs through a WebSocket-based transport. Provides access to system configuration, storage, networking, service management, and user accounts.

**Base URL:** `https://localhost:9090/cockpit`

- [Documentation](https://cockpit-project.org/guide/latest/api-base1.html)
- [GitHub](https://github.com/cockpit-project/cockpit)
- [Guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/managing_systems_using_the_rhel_8_web_console/index)

### [RHEL 8 System Roles API](https://access.redhat.com/articles/3050101)
RHEL System Roles are a collection of Ansible roles and modules for automating RHEL system configuration tasks including networking, storage, certificate management, SELinux, time sync, and firewall configuration.

**Base URL:** `https://console.redhat.com/ansible/automation-hub/`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/administration_and_configuration_tasks_using_system_roles_in_rhel/index)
- [GitHub](https://github.com/linux-system-roles)
- [Ansible Galaxy](https://galaxy.ansible.com/linux-system-roles)

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [Security Data API](openapi/red-hat-enterprise-linux-8-security-data-openapi.yml) |
| JSON Schema | [CVE](json-schema/red-hat-enterprise-linux-8-cve-schema.json) |
| JSON Structure | [CVE Structure](json-structure/red-hat-enterprise-linux-8-cve-structure.json) |
| JSON-LD Context | [RHEL 8 Context](json-ld/red-hat-enterprise-linux-8-context.jsonld) |
| Spectral Rules | [RHEL 8 Rules](rules/red-hat-enterprise-linux-8-rules.yml) |
| Vocabulary | [RHEL 8 Vocabulary](vocabulary/red-hat-enterprise-linux-8-vocabulary.yml) |

## Examples

- [Get CVE](examples/red-hat-enterprise-linux-8-get-cve-example.json)
- [List Advisories](examples/red-hat-enterprise-linux-8-list-advisories-example.json)

## Common Properties

- [Portal](https://access.redhat.com/)
- [Customer Portal](https://console.redhat.com/)
- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/)
- [Knowledge Base](https://access.redhat.com/knowledgebase/)
- [Support](https://access.redhat.com/support/)
- [Downloads](https://access.redhat.com/downloads/)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-enterprise-linux)
- [Release Notes](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.0_release_notes/index)
- [Security](https://access.redhat.com/security/)
- [Training](https://www.redhat.com/en/services/training-and-certification)
- [GitHub Organization](https://github.com/redhat-developer)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [Terms of Service](https://www.redhat.com/en/about/agreements)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
