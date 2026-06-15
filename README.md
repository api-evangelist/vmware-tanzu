# VMware Tanzu (vmware-tanzu)

VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu Service Mesh REST API for cluster and global namespace management, Kubernetes CRD-based APIs for VM Operator, Projects Operator, and NSX Operator, and the Tanzu CLI plugin runtime.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- Containers
- Enterprise
- Kubernetes
- Multi-Cloud
- Service Mesh
- VMware

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### VMware Tanzu Service Mesh API

The Tanzu Service Mesh REST API provides programmatic access to manage clusters, global namespaces, resource groups, and service mesh policies. Authentication uses a CSP API token exchanged for a short-lived Bearer token. The API version is embedded in the URL path (e.g. /v1alpha1/).

- **Human URL:** [https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/index.html](https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/index.html)

#### Tags

- Clusters
- Global Namespaces
- Kubernetes
- Resource Groups
- Service Mesh

#### Properties

- [Documentation](https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/services/api-programming-guide/GUID-6C5044B8-6950-42A6-87A5-3D88BEAE09DB.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-service-mesh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vmware-tanzu-service-mesh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-tanzu-service-mesh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Tanzu Kubernetes Grid API

Kubernetes-native API for provisioning and managing Tanzu Kubernetes clusters using the TanzuKubernetesCluster CRD (v1alpha1/v1alpha2). Runs on vSphere Supervisor clusters via the Tanzu Kubernetes Grid Service.

- **Human URL:** [https://docs.vmware.com/en/VMware-vSphere/index.html](https://docs.vmware.com/en/VMware-vSphere/index.html)

#### Tags

- Cluster Provisioning
- Kubernetes
- TKG
- vSphere

#### Properties

- [Documentation](https://docs.vmware.com/en/VMware-vSphere/7.0/vmware-vsphere-with-tanzu/GUID-31BF8166-5FC8-4D43-933D-5797F3BE4A36.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-kubernetes-grid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Kubernetes C R D](https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/crd/tanzukubernetescluster-crd.yaml)
- [Postman Collection](collections/vmware-tanzu-service-mesh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-tanzu-service-mesh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vmware-tanzu)
- [Website](https://tanzu.vmware.com/)
- [Documentation](https://docs.vmware.com/en/VMware-Tanzu/index.html)
- [GitHub Organization](https://github.com/vmware-tanzu)
- [Blog](https://tanzu.vmware.com/content/blog)
- [Pricing](https://tanzu.vmware.com/pricing)
- [Sign Up](https://tanzu.vmware.com/try)
- [Broadcom  Tech Docs](https://techdocs.broadcom.com/us/en/vmware-tanzu.html)
- [C L I](https://github.com/vmware-tanzu/tanzu-cli)
- [Velero](https://github.com/vmware-tanzu/velero)
- [Sonobuoy](https://github.com/vmware-tanzu/sonobuoy)
- [Cartographer](https://github.com/vmware-tanzu/cartographer)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
