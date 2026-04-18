# Solaris Zones (solaris-zones)
API for managing Solaris Zones (containers) and virtualization on Oracle Solaris systems.

**URL:** [Visit APIs.json URL](https://docs.oracle.com/en/operating-systems/solaris.html)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Containers, Kernel Zones, Operating Systems, Oracle, RAD, Resource Management, Solaris, StatsStore, Virtualization, Zones

## Timestamps

- **Created:** 2024 
- **Modified:** 2026-04-18 

## APIs

### Solaris Zones Management API
Core API for creating, managing, and monitoring Solaris Zones.

**Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html)

#### Tags:

 - Containers, Oracle, Solaris, Virtualization, Zones

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html)
- [OpenAPI](openapi/solaris-zones-management-openapi.yml)

### Zone Configuration API
API endpoints for zone configuration and resource management.

**Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html)

#### Tags:

 - Configuration, Networking, Resources

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html)
- [OpenAPI](openapi/solaris-zone-configuration-openapi.yml)

### Zone Administration API
API for zone lifecycle management including install, boot, halt, and delete operations.

**Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html)

#### Tags:

 - Administration, Lifecycle, Management

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html)
- [OpenAPI](openapi/solaris-zone-administration-openapi.yml)

### Zone Monitoring API
API for monitoring zone status, resource usage, and performance metrics.

**Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html)

#### Tags:

 - Metrics, Monitoring, Performance

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html)
- [OpenAPI](openapi/solaris-zone-monitoring-openapi.yml)

### RAD Zone Management REST API
Remote Administration Daemon REST API for programmatic zone management via the com.oracle.solaris.rad.zonemgr module.

**Human URL:** [https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html)

#### Tags:

 - Management, RAD, Remote Administration, REST API, Zones

#### Properties

- [Documentation](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html)
- [OpenAPI](openapi/solaris-rad-zonemgr-openapi.yml)

### Zones Monitoring Statistics API (libzonestat)
The libzonestat.so.1 C library API used to retrieve and compute zone-related resource utilization information.

**Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E61043/](https://docs.oracle.com/cd/E37838_01/html/E61043/)

#### Tags:

 - CPU, Libzonestat, Memory, Monitoring, Resource Utilization, Statistics

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61043/)
- [OpenAPI](openapi/solaris-zone-stats-openapi.yml)

### Oracle Solaris Kernel Zones API
API for creating and managing Oracle Solaris Kernel Zones with enhanced security isolation.

**Human URL:** [https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html)

#### Tags:

 - Isolation, Kernel Zones, Security, Virtualization

#### Properties

- [Documentation](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html)
- [OpenAPI](openapi/solaris-kernel-zones-openapi.yml)

### Oracle Solaris StatsStore and Analytics API
REST API for accessing the Oracle Solaris 11.4 StatsStore with consolidated zone resource statistics and historical analytics.

**Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E56520/index.html](https://docs.oracle.com/cd/E37838_01/html/E56520/index.html)

#### Tags:

 - Analytics, Monitoring, Performance, REST API, StatsStore, Web Interface

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E56520/index.html)
- [OpenAPI](openapi/solaris-statsstore-openapi.yml)

### Oracle Solaris Unified Archives Zones API
API for creating, deploying, and managing Unified Archives for zone system recovery, cloning, and migration.

**Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html](https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html)

#### Tags:

 - Backup, Cloning, Migration, Recovery, Unified Archives

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html)
- [OpenAPI](openapi/solaris-unified-archives-openapi.yml)

## Common Properties

- [TermsOfService](https://www.oracle.com/legal/terms.html)
- [PrivacyPolicy](https://www.oracle.com/legal/privacy/)
- [Authentication](https://docs.oracle.com/en/cloud/paas/api-platform/authentication.html)
- [Support](https://www.oracle.com/support/)
- [Blog](https://blogs.oracle.com/solaris/)
- [Portal](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/index.html)
- [GitHubOrganization](https://github.com/oracle/oraclesolaris-contrib)
- [GettingStarted](https://docs.oracle.com/cd/E37838_01/html/E61038/gitsf.html)

## Features

| Name | Description |
|------|-------------|
| Zone Isolation | Hardware-enforced isolation between zones providing secure multi-tenant environments on a single physical system. |
| Live Migration | Move running zones between physical systems without downtime using live migration capabilities. |
| Kernel Zones | Non-global zones with their own independent kernel for enhanced security isolation and OS independence. |
| Unified Archives | Create portable system archives for zone cloning, recovery, and migration across Solaris systems. |
| StatsStore Analytics | Consolidated resource statistics and historical analytics for monitoring zone performance and capacity planning. |
| RAD Remote Administration | RESTful remote administration daemon enabling programmatic zone management over HTTP/JSON. |
| Resource Capping | Fine-grained CPU, memory, and swap resource controls with configurable caps per zone. |

## Use Cases

| Name | Description |
|------|-------------|
| Server Consolidation | Consolidate multiple workloads onto a single physical system using zones for resource isolation and management. |
| Development and Testing | Create isolated development and testing environments that mirror production without dedicated hardware. |
| Disaster Recovery | Use Unified Archives and zone migration to implement disaster recovery workflows across Solaris systems. |
| Performance Monitoring | Monitor zone resource utilization and system performance using StatsStore and zonestat APIs. |
| Automated Provisioning | Programmatically create, configure, and deploy zones using RAD REST APIs for automated infrastructure provisioning. |

## Integrations

| Name | Description |
|------|-------------|
| Oracle Enterprise Manager | Manage Solaris Zones through Oracle Enterprise Manager for centralized infrastructure monitoring and control. |
| Ansible | Automate zone provisioning and configuration management using Ansible playbooks with Oracle Solaris modules. |
| Puppet | Configure and manage Solaris Zones infrastructure as code using Puppet modules for Oracle Solaris. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Solaris Zones Management API](openapi/solaris-zones-management-openapi.yml)
- [Zone Configuration API](openapi/solaris-zone-configuration-openapi.yml)
- [Zone Administration API](openapi/solaris-zone-administration-openapi.yml)
- [Zone Monitoring API](openapi/solaris-zone-monitoring-openapi.yml)
- [RAD Zone Management API](openapi/solaris-rad-zonemgr-openapi.yml)
- [Zone Statistics API](openapi/solaris-zone-stats-openapi.yml)
- [Kernel Zones API](openapi/solaris-kernel-zones-openapi.yml)
- [StatsStore API](openapi/solaris-statsstore-openapi.yml)
- [Unified Archives API](openapi/solaris-unified-archives-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zones Management API](capabilities/shared/zones-management.yaml) -- 16 operations for zone lifecycle, configuration, and migration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Zone Lifecycle Management](capabilities/zone-lifecycle.yaml) | Zones Management | 14 | System Administrator / Platform Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
