# Solaris Zones (solaris-zones)

API for managing Solaris Zones (containers) and virtualization on Oracle Solaris systems.

**APIs.json:** [https://docs.oracle.com/en/operating-systems/solaris.html](https://docs.oracle.com/en/operating-systems/solaris.html)

## Tags

- Containers
- Kernel Zones
- Operating Systems
- Oracle
- RAD
- Resource Management
- Solaris
- StatsStore
- Virtualization
- Zones

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Solaris Zones Management API

Core API for creating, managing, and monitoring Solaris Zones.

- **Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html)
- **Base URL:** `https://solaris-host.example.com/api/v1`

#### Tags

- Containers
- Oracle
- Solaris
- Virtualization
- Zones

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zones.html)
- [OpenAPI](openapi/solaris-zones-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-zones-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-zones-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zone Configuration API

API endpoints for zone configuration and resource management.

- **Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones`

#### Tags

- Configuration
- Networking
- Resources

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zonecfg-1m.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61040/)
- [OpenAPI](openapi/solaris-zone-configuration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-zone-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-zone-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zone Administration API

API for zone lifecycle management including install, boot, halt, and delete operations.

- **Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones/admin`

#### Tags

- Administration
- Lifecycle
- Management

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zoneadm-1m.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61038/gqhar.html)
- [OpenAPI](openapi/solaris-zone-administration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-zone-administration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-zone-administration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zone Monitoring API

API for monitoring zone status, resource usage, and performance metrics.

- **Human URL:** [https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html](https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones/monitoring`

#### Tags

- Metrics
- Monitoring
- Performance

#### Properties

- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E37839/zonestat-1.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61043/gklfb.html)
- [OpenAPI](openapi/solaris-zone-monitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-zone-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-zone-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RAD Zone Management REST API

Remote Administration Daemon REST API for programmatic zone management via the com.oracle.solaris.rad.zonemgr module, supporting zone creation, configuration, migration, and lifecycle operations over HTTP/JSON.

- **Human URL:** [https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html)
- **Base URL:** `https://solaris-host.example.com/api/com.oracle.solaris.rad.zonemgr`

#### Tags

- Management
- RAD
- Remote Administration
- REST API
- Zones

#### Properties

- [Documentation](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/rad-client/rest-api-reference.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpd.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpv.html)
- [Documentation](https://docs.oracle.com/cd/E88353_01/html/E76189/zonemgr-1-3rad.html)
- [OpenAPI](openapi/solaris-rad-zonemgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-rad-zonemgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-rad-zonemgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zones Monitoring Statistics API (libzonestat)

The libzonestat.so.1 C library API used to retrieve and compute zone-related resource utilization information including physical memory, virtual memory, and CPU resources with sorting and filtering options.

- **Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E61043/](https://docs.oracle.com/cd/E37838_01/html/E61043/)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones/stats`

#### Tags

- CPU
- Libzonestat
- Memory
- Monitoring
- Resource Utilization
- Statistics

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61043/)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61043/gklfn.html)
- [Documentation](https://docs.oracle.com/cd/E23824_01/html/821-1499/gloag.html)
- [OpenAPI](openapi/solaris-zone-stats-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-zone-stats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-zone-stats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Solaris Kernel Zones API

API for creating and managing Oracle Solaris Kernel Zones, which are non-global zones with their own kernel providing greater independence and enhanced security isolation.

- **Human URL:** [https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones/kernel`

#### Tags

- Isolation
- Kernel Zones
- Security
- Virtualization

#### Properties

- [Documentation](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/kernel-zones/oracle-solaris-kernel-zones.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61041/gnzfn.html)
- [OpenAPI](openapi/solaris-kernel-zones-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-kernel-zones.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-kernel-zones.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Solaris StatsStore and Analytics API

REST API and web interface for accessing the Oracle Solaris 11.4 StatsStore, providing consolidated zone resource statistics, system performance data, and historical analytics via CLI, C, Python, and RAD interfaces.

- **Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E56520/index.html](https://docs.oracle.com/cd/E37838_01/html/E56520/index.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/statsstore`

#### Tags

- Analytics
- Monitoring
- Performance
- REST API
- StatsStore
- Web Interface

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E56520/index.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E56520/sstoreintro.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E56520/ssids.html)
- [OpenAPI](openapi/solaris-statsstore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-statsstore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-statsstore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Solaris Unified Archives Zones API

API for creating, deploying, and managing Unified Archives for zone system recovery, cloning, and migration across Oracle Solaris systems.

- **Human URL:** [https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html](https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html)
- **Base URL:** `https://solaris-host.example.com/api/v1/zones/archives`

#### Tags

- Backup
- Cloning
- Migration
- Recovery
- Unified Archives

#### Properties

- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E60984/gmrlo.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E60984/gmwen.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61039/gpoiu.html)
- [OpenAPI](openapi/solaris-unified-archives-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solaris-unified-archives.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solaris-unified-archives.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Authentication](https://docs.oracle.com/en/cloud/paas/api-platform/authentication.html)
- [Support](https://www.oracle.com/support/)
- [Blog](https://blogs.oracle.com/solaris/)
- [Portal](https://docs.oracle.com/en/operating-systems/solaris/oracle-solaris/11.4/index.html)
- [Resources](https://www.oracle.com/solaris/technologies/solarisdeveloper.html)
- [GitHub Organization](https://github.com/oracle/oraclesolaris-contrib)
- [Getting Started](https://docs.oracle.com/cd/E37838_01/html/E61038/gitsf.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61037/zonesoverview.html)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E61040/)
- [Documentation](https://docs.oracle.com/cd/E37838_01/html/E68270/gpzpd.html)
- [JSON-LD](json-ld/solaris-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/solaris-zone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/solaris-zone-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/solaris-zone-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/solaris-zone-migration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/solaris-zone-evacuation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
**FN:** Oracle Corporation
**Email:** solaris-feedback@oracle.com
**URL:** https://www.oracle.com/solaris/
