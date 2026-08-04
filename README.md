# Red Hat Enterprise Linux 8 (red-hat-enterprise-linux-8)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution that provides a stable, secure, and high-performance operating system platform for modern IT environments. RHEL 8 is managed and accessed programmatically through Red Hat's cloud console APIs, subscription management APIs, security data APIs, and system management interfaces including Insights, Image Builder, and Cockpit. These APIs enable automated provisioning, configuration, security scanning, patch management, and compliance reporting for RHEL deployments at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### RHEL 8 Subscription Management API

The Red Hat Subscription Management (RHSM) API provides programmatic access to manage Red Hat subscriptions, entitlements, and system registrations. Operators can list, activate, and manage subscriptions, query available SKUs, register and unregister systems, and retrieve entitlement certificates. Authentication uses OAuth 2.0 tokens obtained via the Red Hat SSO service.

- **Human URL:** [https://access.redhat.com/management/api](https://access.redhat.com/management/api)
- **Base URL:** `https://api.access.redhat.com/management/v1`

#### Tags

- Entitlements
- Registration
- Subscriptions
- System Management

#### Properties

- [Documentation](https://access.redhat.com/management/api/rhsm)
- [OpenAPI](https://api.access.redhat.com/management/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://access.redhat.com/articles/3626371)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Insights API

Red Hat Insights is a predictive analytics service for RHEL systems that provides API access to vulnerability assessment, compliance reporting, patch management, drift analysis, and advisor recommendations. The Insights API allows automation of security scanning, patch prioritization, and system health monitoring for registered RHEL hosts. Authentication uses OAuth 2.0 tokens via the console.redhat.com identity service.

- **Human URL:** [https://console.redhat.com/docs/api/insights](https://console.redhat.com/docs/api/insights)
- **Base URL:** `https://console.redhat.com/api/insights/v1`

#### Tags

- Analytics
- Compliance
- Monitoring
- Predictive Analytics
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://console.redhat.com/docs/api/insights)
- [OpenAPI](https://console.redhat.com/api/insights/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://console.redhat.com/insights)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Image Builder API

The Red Hat Image Builder API enables automated creation of custom RHEL system images for cloud, virtual machine, and bare-metal deployments. Users can define image compositions, specify packages and customizations, build images for specific target environments (AWS, Azure, GCP, VMware, ISO), and download completed image artifacts. The API is part of the Red Hat Hybrid Cloud Console.

- **Human URL:** [https://console.redhat.com/docs/api/image-builder](https://console.redhat.com/docs/api/image-builder)
- **Base URL:** `https://console.redhat.com/api/image-builder/v1`

#### Tags

- Cloud
- Deployment
- Image Builder
- Infrastructure
- Provisioning

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/composing_a_customized_rhel_system_image/index)
- [OpenAPI](https://console.redhat.com/api/image-builder/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Tutorial](https://www.redhat.com/en/blog/using-red-hat-image-builder)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Patch Management API

The Red Hat Patch Management API (part of Red Hat Insights) provides endpoints for querying available errata, advisories, and CVE patches for registered RHEL systems. It enables operators to list applicable patches per system, filter by severity or type, and trigger patch installations. The API integrates with Satellite for on-premises patch orchestration.

- **Human URL:** [https://console.redhat.com/docs/api/patch](https://console.redhat.com/docs/api/patch)
- **Base URL:** `https://console.redhat.com/api/patch/v3`

#### Tags

- Errata
- Packages
- Patch Management
- Security
- Updates

#### Properties

- [Documentation](https://console.redhat.com/docs/api/patch)
- [OpenAPI](https://console.redhat.com/api/patch/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Vulnerability Management API

The Red Hat Vulnerability Management API (part of Insights) provides programmatic access to CVE vulnerability data for registered RHEL systems. Operators can query known CVEs affecting their hosts, retrieve severity scores, filter by system or CVE, and export vulnerability reports for compliance and risk management purposes.

- **Human URL:** [https://console.redhat.com/docs/api/vulnerability](https://console.redhat.com/docs/api/vulnerability)
- **Base URL:** `https://console.redhat.com/api/vulnerability/v1`

#### Tags

- CVE
- Risk Management
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://console.redhat.com/docs/api/vulnerability)
- [OpenAPI](https://console.redhat.com/api/vulnerability/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Compliance API

The Red Hat Compliance API (part of Insights) enables automated compliance scanning and reporting against security profiles such as CIS, DISA STIG, and PCI-DSS for RHEL systems. Operators can list compliance policies, query system compliance scores, retrieve rule results, and download compliance reports in SCAP and PDF formats.

- **Human URL:** [https://console.redhat.com/docs/api/compliance](https://console.redhat.com/docs/api/compliance)
- **Base URL:** `https://console.redhat.com/api/compliance/v2`

#### Tags

- Compliance
- SCAP
- Security
- STIG

#### Properties

- [Documentation](https://console.redhat.com/docs/api/compliance)
- [OpenAPI](https://console.redhat.com/api/compliance/v2/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Security Data API

The Red Hat Security Data API provides public access to Red Hat's security advisory and CVE data. Operators can query CVEs affecting RHEL products, retrieve CVSS scores, list security advisories (RHSA), bug fix advisories (RHBA), and enhancement advisories (RHEA), and obtain OVAL XML data for vulnerability scanning integration. No authentication is required for public data.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0](https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0)
- **Base URL:** `https://access.redhat.com/labs/securitydataapi`

#### Tags

- Advisories
- CVE
- OVAL
- Public Data
- Security

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/html/red_hat_security_data_api/index)
- [A P I  Endpoint](https://access.redhat.com/labs/securitydataapi/)
- [Examples](https://access.redhat.com/articles/2915291)
- [OpenAPI](openapi/red-hat-enterprise-linux-8-security-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Host Inventory API

The Red Hat Insights Host Inventory API provides programmatic access to the inventory of RHEL systems registered with Red Hat Insights. Operators can query hosts by attributes, retrieve system facts, manage host groups, query system profiles, and track system metadata including OS version, hardware, and installed packages.

- **Human URL:** [https://console.redhat.com/docs/api/inventory](https://console.redhat.com/docs/api/inventory)
- **Base URL:** `https://console.redhat.com/api/inventory/v1`

#### Tags

- Asset Management
- Inventory
- System Management

#### Properties

- [Documentation](https://console.redhat.com/docs/api/inventory)
- [OpenAPI](https://console.redhat.com/api/inventory/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 Cockpit Web Console API

Cockpit is a web-based system management interface for RHEL that exposes internal D-Bus and system APIs through a WebSocket-based transport. The Cockpit API provides access to system configuration, storage management, network configuration, service management, user accounts, and system logs from a web browser. It operates locally on each managed system at port 9090.

- **Human URL:** [https://cockpit-project.org/guide/latest/api-base1.html](https://cockpit-project.org/guide/latest/api-base1.html)
- **Base URL:** `https://localhost:9090/cockpit`

#### Tags

- Management
- System Administration
- UI
- Web Console

#### Properties

- [Documentation](https://cockpit-project.org/guide/latest/api-base1.html)
- [Git Hub](https://github.com/cockpit-project/cockpit)
- [Guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/managing_systems_using_the_rhel_8_web_console/index)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RHEL 8 System Roles API

RHEL System Roles are a collection of Ansible roles and modules for automating RHEL system configuration tasks including networking, storage, certificate management, SELinux, time sync, and firewall configuration. The roles expose a structured YAML-based API for declarative system state management through Ansible Automation Platform or standalone Ansible.

- **Human URL:** [https://access.redhat.com/articles/3050101](https://access.redhat.com/articles/3050101)
- **Base URL:** `https://console.redhat.com/ansible/automation-hub/`

#### Tags

- Ansible
- Automation
- Configuration Management
- System Roles

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/administration_and_configuration_tasks_using_system_roles_in_rhel/index)
- [Git Hub](https://github.com/linux-system-roles)
- [Ansible  Galaxy](https://galaxy.ansible.com/linux-system-roles)
- [Postman Collection](collections/red-hat-enterprise-linux-8-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-enterprise-linux-8-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://access.redhat.com/)
- [Customer  Portal](https://console.redhat.com/)
- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/)
- [Knowledge  Base](https://access.redhat.com/knowledgebase/)
- [Support](https://access.redhat.com/support/)
- [Downloads](https://access.redhat.com/downloads/)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-enterprise-linux)
- [Release Notes](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.0_release_notes/index)
- [Security](https://access.redhat.com/security/)
- [Training](https://www.redhat.com/en/services/training-and-certification)
- [GitHub Organization](https://github.com/redhat-developer)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [Terms of Service](https://www.redhat.com/en/about/agreements)
- [OpenAPI](openapi/red-hat-enterprise-linux-8-security-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](json-ld/red-hat-enterprise-linux-8-context.jsonld)
- [JSON Schema](json-schema/red-hat-enterprise-linux-8-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/red-hat-enterprise-linux-8-cve-structure.json)
- [Spectral Ruleset](rules/red-hat-enterprise-linux-8-rules.yml)
- [Vocabulary](vocabulary/red-hat-enterprise-linux-8-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
