| **API Group**         | **Kind**                         | **API Version**                        | **Cluster-Level** | **Short Names**   |
| --------------------- | -------------------------------- | -------------------------------------- | :---------------: | ----------------- |
| Core                  | Binding                          | v1                                     |         ❌         |                   |
| Core                  | ComponentStatus                  | v1                                     |         ✅         | cs                |
| Core                  | ConfigMap                        | v1                                     |         ❌         | cm                |
| Core                  | Endpoints                        | v1                                     |         ❌         | ep                |
| Core                  | Event                            | v1                                     |         ❌         | ev                |
| Core                  | LimitRange                       | v1                                     |         ❌         | limits            |
| Core                  | Namespace                        | v1                                     |         ✅         | ns                |
| Core                  | Node                             | v1                                     |         ✅         | no                |
| Core                  | PersistentVolumeClaim            | v1                                     |         ❌         | pvc               |
| Core                  | PersistentVolume                 | v1                                     |         ✅         | pv                |
| Core                  | Pod                              | v1                                     |         ❌         | po                |
| Core                  | PodTemplate                      | v1                                     |         ❌         |                   |
| Core                  | ReplicationController            | v1                                     |         ❌         | rc                |
| Core                  | ResourceQuota                    | v1                                     |         ❌         | quota             |
| Core                  | Secret                           | v1                                     |         ❌         |                   |
| Core                  | ServiceAccount                   | v1                                     |         ❌         | sa                |
| Core                  | Service                          | v1                                     |         ❌         | svc               |
| AdmissionRegistration | MutatingWebhookConfiguration     | admissionregistration.k8s.io/v1        |         ✅         |                   |
| AdmissionRegistration | ValidatingAdmissionPolicy        | admissionregistration.k8s.io/v1        |         ✅         |                   |
| AdmissionRegistration | ValidatingAdmissionPolicyBinding | admissionregistration.k8s.io/v1        |         ✅         |                   |
| AdmissionRegistration | ValidatingWebhookConfiguration   | admissionregistration.k8s.io/v1        |         ✅         |                   |
| APIExtensions         | CustomResourceDefinition         | apiextensions.k8s.io/v1                |         ✅         | crd,crds          |
| APIRegistration       | APIService                       | apiregistration.k8s.io/v1              |         ✅         |                   |
| Apps                  | ControllerRevision               | apps/v1                                |         ❌         |                   |
| Apps                  | DaemonSet                        | apps/v1                                |         ❌         | ds                |
| Apps                  | Deployment                       | apps/v1                                |         ❌         | deploy            |
| Apps                  | ReplicaSet                       | apps/v1                                |         ❌         | rs                |
| Apps                  | StatefulSet                      | apps/v1                                |         ❌         | sts               |
| Authentication        | OpenIDConnect                    | authentication.gardener.cloud/v1alpha1 |         ✅         | oidc,oidcs        |
| Authentication        | SelfSubjectReview                | authentication.k8s.io/v1               |         ✅         |                   |
| Authentication        | TokenReview                      | authentication.k8s.io/v1               |         ✅         |                   |
| Authorization         | LocalSubjectAccessReview         | authorization.k8s.io/v1                |         ❌         |                   |
| Authorization         | SelfSubjectAccessReview          | authorization.k8s.io/v1                |         ✅         |                   |
| Authorization         | SelfSubjectRulesReview           | authorization.k8s.io/v1                |         ✅         |                   |
| Authorization         | SubjectAccessReview              | authorization.k8s.io/v1                |         ✅         |                   |
| Autoscaling           | HorizontalPodAutoscaler          | autoscaling/v2                         |         ❌         | hpa               |
| Autoscaling           | VerticalPodAutoscalerCheckpoint  | autoscaling.k8s.io/v1                  |         ❌         | vpacheckpoint     |
| Autoscaling           | VerticalPodAutoscaler            | autoscaling.k8s.io/v1                  |         ❌         | vpa               |
| Batch                 | Job                              | batch/v1                               |         ❌         |                   |
| Batch                 | CronJob                          | batch/v1                               |         ❌         | cj                |
| CertManager           | CertificateRevocation            | cert.gardener.cloud/v1alpha1           |         ❌         | certrevoke        |
| CertManager           | Certificate                      | cert.gardener.cloud/v1alpha1           |         ❌         | cert              |
| CertManager           | Issuer                           | cert.gardener.cloud/v1alpha1           |         ❌         |                   |
| CertManager           | CertificateSigningRequest        | certificates.k8s.io/v1                 |         ✅         | csr               |
| Coordination          | Lease                            | coordination.k8s.io/v1                 |         ❌         |                   |
| Kyma                  | CustomConfig                     | core.kyma-project.io/v1beta1           |         ❌         |                   |
| Kyma                  | RegistryCacheConfig              | core.kyma-project.io/v1beta1           |         ❌         |                   |
| Calico CRDs           | BGPConfiguration                 | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | BGPFilter                        | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | BGPPeer                          | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | BlockAffinity                    | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | CalicoNodeStatus                 | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | ClusterInformation               | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | FelixConfiguration               | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | GlobalNetworkPolicy              | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | GlobalNetworkSet                 | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | HostEndpoint                     | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | IPAMBlock                        | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | IPAMConfig                       | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | IPAMHandle                       | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | IPPool                           | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | IPReservation                    | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | KubeControllersConfiguration     | crd.projectcalico.org/v1               |         ✅         |                   |
| Calico CRDs           | NetworkPolicy                    | crd.projectcalico.org/v1               |         ❌         |                   |
| Calico CRDs           | NetworkSet                       | crd.projectcalico.org/v1               |         ❌         |                   |
| Calico CRDs           | Tier                             | crd.projectcalico.org/v1               |         ✅         |                   |
| Discovery             | EndpointSlice                    | discovery.k8s.io/v1                    |         ❌         |                   |
| Gardener DNS          | DNSAnnotation                    | dns.gardener.cloud/v1alpha1            |         ❌         | dnsa              |
| Gardener DNS          | DNSEntry                         | dns.gardener.cloud/v1alpha1            |         ❌         | dnse              |
| Gardener DNS          | DNSProvider                      | dns.gardener.cloud/v1alpha1            |         ❌         | dnspr             |
| Events                | Event                            | events.k8s.io/v1                       |         ❌         | ev                |
| Istio Extensions      | WasmPlugin                       | extensions.istio.io/v1alpha1           |         ❌         |                   |
| Flow Control          | FlowSchema                       | flowcontrol.apiserver.k8s.io/v1        |         ✅         |                   |
| Flow Control          | PriorityLevelConfiguration       | flowcontrol.apiserver.k8s.io/v1        |         ✅         |                   |
| Kyma Gateway          | APIRule                          | gateway.kyma-project.io/v2             |         ❌         |                   |
| Kyma Gateway          | RateLimit                        | gateway.kyma-project.io/v1alpha1       |         ❌         |                   |
| Metrics               | NodeMetrics                      | metrics.k8s.io/v1beta1                 |         ✅         |                   |
| Metrics               | PodMetrics                       | metrics.k8s.io/v1beta1                 |         ❌         |                   |
| Istio Networking      | DestinationRule                  | networking.istio.io/v1                 |         ❌         | dr                |
| Istio Networking      | EnvoyFilter                      | networking.istio.io/v1alpha3           |         ❌         |                   |
| Istio Networking      | Gateway                          | networking.istio.io/v1                 |         ❌         | gw                |
| Istio Networking      | ProxyConfig                      | networking.istio.io/v1beta1            |         ❌         |                   |
| Istio Networking      | ServiceEntry                     | networking.istio.io/v1                 |         ❌         | se                |
| Istio Networking      | Sidecar                          | networking.istio.io/v1                 |         ❌         |                   |
| Istio Networking      | VirtualService                   | networking.istio.io/v1                 |         ❌         | vs                |
| Istio Networking      | WorkloadEntry                    | networking.istio.io/v1                 |         ❌         | we                |
| Istio Networking      | WorkloadGroup                    | networking.istio.io/v1                 |         ❌         | wg                |
| Networking            | IngressClass                     | networking.k8s.io/v1                   |         ✅         |                   |
| Networking            | Ingress                          | networking.k8s.io/v1                   |         ❌         | ing               |
| Networking            | NetworkPolicy                    | networking.k8s.io/v1                   |         ❌         | netpol            |
| Oathkeeper            | Rule                             | oathkeeper.ory.sh/v1alpha1             |         ❌         |                   |
| Kyma Operator         | APIGateway                       | operator.kyma-project.io/v1alpha1      |         ✅         |                   |
| Kyma Operator         | BtpOperator                      | operator.kyma-project.io/v1alpha1      |         ❌         |                   |
| Kyma Operator         | Istio                            | operator.kyma-project.io/v1alpha2      |         ❌         |                   |
| Kyma Operator         | Kyma                             | operator.kyma-project.io/v1beta2       |         ❌         |                   |
| Kyma Operator         | ModuleReleaseMeta                | operator.kyma-project.io/v1beta2       |         ❌         | mrm               |
| Kyma Operator         | ModuleTemplate                   | operator.kyma-project.io/v1beta2       |         ❌         |                   |
| Policy                | PodDisruptionBudget              | policy/v1                              |         ❌         | pdb               |
| Policy Networking     | AdminNetworkPolicy               | policy.networking.k8s.io/v1alpha1      |         ✅         | anp               |
| RBAC                  | ClusterRoleBinding               | rbac.authorization.k8s.io/v1           |         ✅         |                   |
| RBAC                  | ClusterRole                      | rbac.authorization.k8s.io/v1           |         ✅         |                   |
| RBAC                  | RoleBinding                      | rbac.authorization.k8s.io/v1           |         ❌         |                   |
| RBAC                  | Role                             | rbac.authorization.k8s.io/v1           |         ❌         |                   |
| Scheduling            | PriorityClass                    | scheduling.k8s.io/v1                   |         ✅         | pc                |
| Istio Security        | AuthorizationPolicy              | security.istio.io/v1                   |         ❌         | ap                |
| Istio Security        | PeerAuthentication               | security.istio.io/v1                   |         ❌         | pa                |
| Istio Security        | RequestAuthentication            | security.istio.io/v1                   |         ❌         | ra                |
| SAP Services          | ServiceBinding                   | services.cloud.sap.com/v1              |         ❌         |                   |
| SAP Services          | ServiceInstance                  | services.cloud.sap.com/v1              |         ❌         |                   |
| Storage Snapshots     | VolumeSnapshotClass              | snapshot.storage.k8s.io/v1             |         ✅         | vsclass,vsclasses |
| Storage Snapshots     | VolumeSnapshotContent            | snapshot.storage.k8s.io/v1             |         ✅         | vsc,vscs          |
| Storage Snapshots     | VolumeSnapshot                   | snapshot.storage.k8s.io/v1             |         ❌         | vs                |
| Storage               | CSIDriver                        | storage.k8s.io/v1                      |         ✅         |                   |
| Storage               | CSINode                          | storage.k8s.io/v1                      |         ✅         |                   |
| Storage               | CSIStorageCapacity               | storage.k8s.io/v1                      |         ❌         |                   |
| Storage               | StorageClass                     | storage.k8s.io/v1                      |         ✅         | sc                |
| Storage               | VolumeAttachment                 | storage.k8s.io/v1                      |         ✅         |                   |
| Istio Telemetry       | Telemetry                        | telemetry.istio.io/v1                  |         ❌         | telemetry         |
