# VMware Tanzu

VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu Service Mesh REST API, Tanzu Kubernetes Grid CRD-based API, and Kubernetes operators for VMs, NSX, and projects.

**Human URL:** https://tanzu.vmware.com  
**Documentation:** https://docs.vmware.com/en/VMware-Tanzu/index.html  
**GitHub Org:** https://github.com/vmware-tanzu  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml

## Scope

- **Type:** Index

## Tags

Cloud Native, Containers, Enterprise, Kubernetes, Multi-Cloud, Service Mesh, VMware

## APIs

### VMware Tanzu Service Mesh API

REST API for managing clusters, global namespaces, and resource groups in Tanzu Service Mesh. CSP token-based authentication.

**Human URL:** https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/index.html

#### Properties

- [Documentation](https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/services/api-programming-guide/GUID-6C5044B8-6950-42A6-87A5-3D88BEAE09DB.html)
- [OpenAPI](openapi/vmware-tanzu-service-mesh-openapi.yml)

---

### VMware Tanzu Kubernetes Grid API

Kubernetes-native CRD API for provisioning workload clusters using TanzuKubernetesCluster on vSphere Supervisor.

**Human URL:** https://docs.vmware.com/en/VMware-vSphere/index.html

#### Properties

- [Documentation](https://docs.vmware.com/en/VMware-vSphere/7.0/vmware-vsphere-with-tanzu/GUID-31BF8166-5FC8-4D43-933D-5797F3BE4A36.html)
- [OpenAPI](openapi/vmware-tanzu-kubernetes-grid-openapi.yml)
- [KubernetesCRD](crd/tanzukubernetescluster-crd.yaml)

---

## OpenAPI Specifications

| File | Description |
|---|---|
| [vmware-tanzu-service-mesh-openapi.yml](openapi/vmware-tanzu-service-mesh-openapi.yml) | TSM clusters, global namespaces, resource groups, authentication |
| [vmware-tanzu-kubernetes-grid-openapi.yml](openapi/vmware-tanzu-kubernetes-grid-openapi.yml) | TanzuKubernetesCluster CRD operations on vSphere Supervisor |

## Kubernetes CRDs

| File | Description |
|---|---|
| [tanzukubernetescluster-crd.yaml](crd/tanzukubernetescluster-crd.yaml) | TanzuKubernetesCluster CRD (v1alpha1/v1alpha2) for workload cluster provisioning |

## Spectral Rules

| File | Description |
|---|---|
| [vmware-tanzu-rules.yml](rules/vmware-tanzu-rules.yml) | Spectral ruleset for Tanzu API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | APIs |
|---|---|
| [shared/tanzu-service-mesh.yaml](capabilities/shared/tanzu-service-mesh.yaml) | Tanzu Service Mesh API |

### Workflow Capabilities

| File | Description |
|---|---|
| [kubernetes-platform.yaml](capabilities/kubernetes-platform.yaml) | Unified REST + MCP for multi-cluster Kubernetes platform management |

## JSON Schema

| File | Description |
|---|---|
| [vmware-tanzu-cluster-schema.json](json-schema/vmware-tanzu-cluster-schema.json) | TSM cluster schema with state, cloud provider, and version fields |
| [vmware-tanzu-global-namespace-schema.json](json-schema/vmware-tanzu-global-namespace-schema.json) | Global namespace schema with cluster configs and mTLS settings |

## JSON Structure

| File | Description |
|---|---|
| [vmware-tanzu-cluster-structure.json](json-structure/vmware-tanzu-cluster-structure.json) | Field-level structure for Tanzu Service Mesh Cluster |

## JSON-LD Context

| File | Description |
|---|---|
| [vmware-tanzu-context.jsonld](json-ld/vmware-tanzu-context.jsonld) | Linked data context for Tanzu vocabulary aligned with schema.org |

## Examples

| File | Description |
|---|---|
| [vmware-tanzu-service-mesh-list-clusters-example.json](examples/vmware-tanzu-service-mesh-list-clusters-example.json) | GET /v1alpha1/clusters — list TSM clusters |
| [vmware-tanzu-kubernetes-grid-create-cluster-example.json](examples/vmware-tanzu-kubernetes-grid-create-cluster-example.json) | POST TanzuKubernetesCluster — create workload cluster |

## Vocabulary

| File | Description |
|---|---|
| [vmware-tanzu-vocabulary.yml](vocabulary/vmware-tanzu-vocabulary.yml) | Tanzu terminology: TSM, Global Namespace, TKR, mTLS, CSP Token, Supervisor |

## Common Properties

- [Website](https://tanzu.vmware.com/)
- [Documentation](https://docs.vmware.com/en/VMware-Tanzu/index.html)
- [Broadcom TechDocs](https://techdocs.broadcom.com/us/en/vmware-tanzu.html)
- [GitHub Organization](https://github.com/vmware-tanzu)
- [Blog](https://tanzu.vmware.com/content/blog)
- [Tanzu CLI](https://github.com/vmware-tanzu/tanzu-cli)
- [Velero](https://github.com/vmware-tanzu/velero)
- [Cartographer](https://github.com/vmware-tanzu/cartographer)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
