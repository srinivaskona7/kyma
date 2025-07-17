| **API Group / Version**                                     | **Kind**                         | **Short Name(s)** | **Namespaced** | **API Version**                        |
| ----------------------------------------------------------- | -------------------------------- | ----------------- | -------------- | -------------------------------------- |
| **Core (v1)**                                               |                                  |                   |                |                                        |
|                                                             | Binding                          |                   | Yes            | v1                                     |
|                                                             | ComponentStatus                  | cs                | No             | v1                                     |
|                                                             | ConfigMap                        | cm                | Yes            | v1                                     |
|                                                             | Endpoints                        | ep                | Yes            | v1                                     |
|                                                             | Event                            | ev                | Yes            | v1                                     |
|                                                             | LimitRange                       | limits            | Yes            | v1                                     |
|                                                             | Namespace                        | ns                | No             | v1                                     |
|                                                             | Node                             | no                | No             | v1                                     |
|                                                             | PersistentVolumeClaim            | pvc               | Yes            | v1                                     |
|                                                             | PersistentVolume                 | pv                | No             | v1                                     |
|                                                             | Pod                              | po                | Yes            | v1                                     |
|                                                             | PodTemplate                      |                   | Yes            | v1                                     |
|                                                             | ReplicationController            | rc                | Yes            | v1                                     |
|                                                             | ResourceQuota                    | quota             | Yes            | v1                                     |
|                                                             | Secret                           |                   | Yes            | v1                                     |
|                                                             | ServiceAccount                   | sa                | Yes            | v1                                     |
|                                                             | Service                          | svc               | Yes            | v1                                     |
|                                                             |                                  |                   |                |                                        |
| **AdmissionRegistration (admissionregistration.k8s.io/v1)** | MutatingWebhookConfiguration     |                   | No             | admissionregistration.k8s.io/v1        |
|                                                             | ValidatingAdmissionPolicy        |                   | No             | admissionregistration.k8s.io/v1        |
|                                                             | ValidatingAdmissionPolicyBinding |                   | No             | admissionregistration.k8s.io/v1        |
|                                                             | ValidatingWebhookConfiguration   |                   | No             | admissionregistration.k8s.io/v1        |
|                                                             |                                  |                   |                |                                        |
| **APIExtensions (apiextensions.k8s.io/v1)**                 | CustomResourceDefinition         | crd,crds          | No             | apiextensions.k8s.io/v1                |
|                                                             |                                  |                   |                |                                        |
| **APIRegistration (apiregistration.k8s.io/v1)**             | APIService                       |                   | No             | apiregistration.k8s.io/v1              |
|                                                             |                                  |                   |                |                                        |
| **Apps (apps/v1)**                                          | ControllerRevision               |                   | Yes            | apps/v1                                |
|                                                             | DaemonSet                        | ds                | Yes            | apps/v1                                |
|                                                             | Deployment                       | deploy            | Yes            | apps/v1                                |
|                                                             | ReplicaSet                       | rs                | Yes            | apps/v1                                |
|                                                             | StatefulSet                      | sts               | Yes            | apps/v1                                |
|                                                             |                                  |                   |                |                                        |
| **Authentication**                                          | OpenIDConnect                    | oidc,oidcs        | No             | authentication.gardener.cloud/v1alpha1 |
|                                                             | SelfSubjectReview                |                   | No             | authentication.k8s.io/v1               |
|                                                             | TokenReview                      |                   | No             | authentication.k8s.io/v1               |
|                                                             |                                  |                   |                |                                        |
| **Authorization**                                           | LocalSubjectAccessReview         |                   | Yes            | authorization.k8s.io/v1                |
|                                                             | SelfSubjectAccessReview          |                   | No             | authorization.k8s.io/v1                |
|                                                             | SelfSubjectRulesReview           |                   | No             | authorization.k8s.io/v1                |
|                                                             | SubjectAccessReview              |                   | No             | authorization.k8s.io/v1                |
|                                                             |                                  |                   |                |                                        |
| **Autoscaling**                                             | HorizontalPodAutoscaler          | hpa               | Yes            | autoscaling/v2                         |
|                                                             | VerticalPodAutoscalerCheckpoint  | vpacheckpoint     | Yes            | autoscaling.k8s.io/v1                  |
|                                                             | VerticalPodAutoscaler            | vpa               | Yes            | autoscaling.k8s.io/v1                  |
|                                                             |                                  |                   |                |                                        |
| **Batch (batch/v1)**                                        | Job                              |                   | Yes            | batch/v1                               |
|                                                             | CronJob                          | cj                | Yes            | batch/v1                               |
|                                                             |                                  |                   |                |                                        |
| **CertManager**                                             | CertificateRevocation            | certrevoke        | Yes            | cert.gardener.cloud/v1alpha1           |
|                                                             | Certificate                      | cert              | Yes            | cert.gardener.cloud/v1alpha1           |
|                                                             | Issuer                           |                   | Yes            | cert.gardener.cloud/v1alpha1           |
|                                                             | CertificateSigningRequest        | csr               | No             | certificates.k8s.io/v1                 |
|                                                             |                                  |                   |                |                                        |
| **Coordination (coordination.k8s.io/v1)**                   | Lease                            |                   | Yes            | coordination.k8s.io/v1                 |
|                                                             |                                  |                   |                |                                        |
| **Kyma (core.kyma-project.io/v1beta1)**                     | CustomConfig                     |                   | Yes            | core.kyma-project.io/v1beta1           |
|                                                             | RegistryCacheConfig              |                   | Yes            | core.kyma-project.io/v1beta1           |
|                                                             |                                  |                   |                |                                        |
| **Calico CRDs (crd.projectcalico.org/v1)**                  | BGPConfiguration                 |                   | No             | crd.projectcalico.org/v1               |
|                                                             | BGPFilter                        |                   | No             | crd.projectcalico.org/v1               |
|                                                             | BGPPeer                          |                   | No             | crd.projectcalico.org/v1               |
|                                                             | BlockAffinity                    |                   | No             | crd.projectcalico.org/v1               |
|                                                             | CalicoNodeStatus                 |                   | No             | crd.projectcalico.org/v1               |
|                                                             | ClusterInformation               |                   | No             | crd.projectcalico.org/v1               |
|                                                             | FelixConfiguration               |                   | No             | crd.projectcalico.org/v1               |
|                                                             | GlobalNetworkPolicy              |                   | No             | crd.projectcalico.org/v1               |
|                                                             | GlobalNetworkSet                 |                   | No             | crd.projectcalico.org/v1               |
|                                                             | HostEndpoint                     |                   | No             | crd.projectcalico.org/v1               |
|                                                             | IPAMBlock                        |                   | No             | crd.projectcalico.org/v1               |
|                                                             | IPAMConfig                       |                   | No             | crd.projectcalico.org/v1               |
|                                                             | IPAMHandle                       |                   | No             | crd.projectcalico.org/v1               |
|                                                             | IPPool                           |                   | No             | crd.projectcalico.org/v1               |
|                                                             | IPReservation                    |                   | No             | crd.projectcalico.org/v1               |
|                                                             | KubeControllersConfiguration     |                   | No             | crd.projectcalico.org/v1               |
|                                                             | NetworkPolicy                    |                   | Yes            | crd.projectcalico.org/v1               |
|                                                             | NetworkSet                       |                   | Yes            | crd.projectcalico.org/v1               |
|                                                             | Tier                             |                   | No             | crd.projectcalico.org/v1               |
|                                                             |                                  |                   |                |                                        |
| **Discovery (discovery.k8s.io/v1)**                         | EndpointSlice                    |                   | Yes            | discovery.k8s.io/v1                    |
|                                                             |                                  |                   |                |                                        |
| **Gardener DNS**                                            | DNSAnnotation                    | dnsa              | Yes            | dns.gardener.cloud/v1alpha1            |
|                                                             | DNSEntry                         | dnse              | Yes            | dns.gardener.cloud/v1alpha1            |
|                                                             | DNSProvider                      | dnspr             | Yes            | dns.gardener.cloud/v1alpha1            |
|                                                             |                                  |                   |                |                                        |
| **Events (events.k8s.io/v1)**                               | Event                            | ev                | Yes            | events.k8s.io/v1                       |
|                                                             |                                  |                   |                |                                        |
| **Istio Extensions**                                        | WasmPlugin                       |                   | Yes            | extensions.istio.io/v1alpha1           |
|                                                             |                                  |                   |                |                                        |
| **Flow Control**                                            | FlowSchema                       |                   | No             | flowcontrol.apiserver.k8s.io/v1        |
|                                                             | PriorityLevelConfiguration       |                   | No             | flowcontrol.apiserver.k8s.io/v1        |
|                                                             |                                  |                   |                |                                        |
| **Kyma Gateway**                                            | APIRule                          |                   | Yes            | gateway.kyma-project.io/v2             |
|                                                             | RateLimit                        |                   | Yes            | gateway.kyma-project.io/v1alpha1       |
|                                                             |                                  |                   |                |                                        |
| **Metrics**                                                 | NodeMetrics                      |                   | No             | metrics.k8s.io/v1beta1                 |
|                                                             | PodMetrics                       |                   | Yes            | metrics.k8s.io/v1beta1                 |
|                                                             |                                  |                   |                |                                        |
| **Istio Networking**                                        | DestinationRule                  | dr                | Yes            | networking.istio.io/v1                 |
|                                                             | EnvoyFilter                      |                   | Yes            | networking.istio.io/v1alpha3           |
|                                                             | Gateway                          | gw                | Yes            | networking.istio.io/v1                 |
|                                                             | ProxyConfig                      |                   | Yes            | networking.istio.io/v1beta1            |
|                                                             | ServiceEntry                     | se                | Yes            | networking.istio.io/v1                 |
|                                                             | Sidecar                          |                   | Yes            | networking.istio.io/v1                 |
|                                                             | VirtualService                   | vs                | Yes            | networking.istio.io/v1                 |
|                                                             | WorkloadEntry                    | we                | Yes            | networking.istio.io/v1                 |
|                                                             | WorkloadGroup                    | wg                | Yes            | networking.istio.io/v1                 |
|                                                             |                                  |                   |                |                                        |
| **Networking (networking.k8s.io/v1)**                       | IngressClass                     |                   | No             | networking.k8s.io/v1                   |
|                                                             | Ingress                          | ing               | Yes            | networking.k8s.io/v1                   |
|                                                             | NetworkPolicy                    | netpol            | Yes            | networking.k8s.io/v1                   |
|                                                             |                                  |                   |                |                                        |
| **Oathkeeper**                                              | Rule                             |                   | Yes            | oathkeeper.ory.sh/v1alpha1             |
|                                                             |                                  |                   |                |                                        |
| **Kyma Operator**                                           | APIGateway                       |                   | No             | operator.kyma-project.io/v1alpha1      |
|                                                             | BtpOperator                      |                   | Yes            | operator.kyma-project.io/v1alpha1      |
|                                                             | Istio                            |                   | Yes            | operator.kyma-project.io/v1alpha2      |
|                                                             | Kyma                             |                   | Yes            | operator.kyma-project.io/v1beta2       |
|                                                             | ModuleReleaseMeta                | mrm               | Yes            | operator.kyma-project.io/v1beta2       |
|                                                             | ModuleTemplate                   |                   | Yes            | operator.kyma-project.io/v1beta2       |
|                                                             |                                  |                   |                |                                        |
| **Policy (policy/v1)**                                      | PodDisruptionBudget              | pdb               | Yes            | policy/v1                              |
|                                                             |                                  |                   |                |                                        |
| **Policy Networking**                                       | AdminNetworkPolicy               | anp               | No             | policy.networking.k8s.io/v1alpha1      |
|                                                             |                                  |                   |                |                                        |
| **RBAC (rbac.authorization.k8s.io/v1)**                     | ClusterRoleBinding               |                   | No             | rbac.authorization.k8s.io/v1           |
|                                                             | ClusterRole                      |                   | No             | rbac.authorization.k8s.io/v1           |
|                                                             | RoleBinding                      |                   | Yes            | rbac.authorization.k8s.io/v1           |
|                                                             | Role                             |                   | Yes            | rbac.authorization.k8s.io/v1           |
|                                                             |                                  |                   |                |                                        |
| **Scheduling (scheduling.k8s.io/v1)**                       | PriorityClass                    | pc                | No             | scheduling.k8s.io/v1                   |
|                                                             |                                  |                   |                |                                        |
| **Istio Security (security.istio.io/v1)**                   | AuthorizationPolicy              | ap                | Yes            | security.istio.io/v1                   |
|                                                             | PeerAuthentication               | pa                | Yes            | security.istio.io/v1                   |
|                                                             | RequestAuthentication            | ra                | Yes            | security.istio.io/v1                   |
|                                                             |                                  |                   |                |                                        |
| **SAP Services**                                            | ServiceBinding                   |                   | Yes            | services.cloud.sap.com/v1              |
|                                                             | ServiceInstance                  |                   | Yes            | services.cloud.sap.com/v1              |
|                                                             |                                  |                   |                |                                        |
| **Storage (snapshot.storage.k8s.io/v1)**                    | VolumeSnapshotClass              | vsclass,vsclasses | No             | snapshot.storage.k8s.io/v1             |
|                                                             | VolumeSnapshotContent            | vsc,vscs          | No             | snapshot.storage.k8s.io/v1             |
|                                                             | VolumeSnapshot                   | vs                | Yes            | snapshot.storage.k8s.io/v1             |
|                                                             |                                  |                   |                |                                        |
| **Storage (storage.k8s.io/v1)**                             | CSIDriver                        |                   | No             | storage.k8s.io/v1                      |
|                                                             | CSINode                          |                   | No             | storage.k8s.io/v1                      |
|                                                             | CSIStorageCapacity               |                   | Yes            | storage.k8s.io/v1                      |
|                                                             | StorageClass                     | sc                | No             | storage.k8s.io/v1                      |
|                                                             | VolumeAttachment                 |                   | No             | storage.k8s.io/v1                      |
|                                                             |                                  |                   |                |                                        |
| **Istio Telemetry**                                         | Telemetry                        | telemetry         | Yes            | telemetry.istio.io/v1                  |
# kyma
