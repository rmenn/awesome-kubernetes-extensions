# awesome-kubernetes-extensions


A resource tracking a number of Kubernetes extensions.

Please send a pull request if you are using Kubernetes Third-Party Resources, Custom Resource Definitions, or the API Server Aggregation and we will add you to the list.
 ### Operators
- Rook Operator: https://github.com/rook/rook/tree/master/demo/kubernetes
- Elasticsearch Operator: https://github.com/upmc-enterprises/elasticsearch-operator
- Etcd Operator: https://coreos.com/blog/introducing-the-etcd-operator.html
- Prometheus Operator: https://coreos.com/blog/the-prometheus-operator.html
- CoreOS Tectonic: https://coreos.com/tectonic
- Kelsey Hightower's kube-cert-manager: https://github.com/kelseyhightower/kube-cert-manager 
- Gravitational Rigging: https://github.com/gravitational/rigging
- PalmStoneGames kube-cert-manager: https://github.com/PalmStoneGames/kube-cert-manager
- linkerd/namerd: https://linkerd.io/config/0.8.6/namerd/index.html#kubernetes
- Flannel Networking: https://github.com/coreos/flannel
- Project Calico Networking: https://github.com/projectcalico/libcalico-go
- Dex OIDC Identity Provider: https://github.com/coreos/dex
- Kubernetes Secrets Manager:  https://github.com/upmc-enterprises/kubernetes-secret-manager
- Giant Swarm's Kubception System: http://blog.kubernetes.io/2017/01/how-we-run-kubernetes-in-kubernetes-kubeception.html
- Digital Ocean's Internal CA: re @fatih
- Icinga2 operator - https://github.com/appscode/searchlight
- HAProxy based Ingress controller - https://github.com/appscode/voyager
- Mirantis App Controller - https://github.com/Mirantis/k8s-AppController
- kubeless https://github.com/skippbox/kubeless 
- hypernetes network stack: https://github.com/hyperhq/hypernetes/
- SOHO House Postgres Operator (TPR): to create/destroy databases in the cluster or in the cloud.
- SOHO House EIP Operator (TPR): whitelisting IPs and management of those IPs/labels
- SAP OpenStack operator creates various resources in OpenStack (currently, Keystone domains, projects, users, groups and roles; will expand to Swift accounts, Designate zones etc. later): https://github.com/sapcc/kubernetes-operators/tree/master/openstack-operator
- KubeVirt - run virtual machines on Kubernetes: https://github.com/kubevirt/kubevirt
- [Archon](http://github.com/kubeup/archon) manages the physical resources that k8s currently doesn't, like Instance, InstanceGroup, Network (defined as TPR)
- Zalando Platform IAM OAuth integration: https://github.com/zalando-incubator/kubernetes-on-aws/pull/154
- Zalando PostgreSQL cluster definition (operator will create a new PostgreSQL/[Patroni](https://github.com/zalando/patroni) cluster)
- Loodse https://beta.kubermatic.io
- Atlassian Smith: https://github.com/atlassian/smith
- Kafka Operator: https://github.com/krallistic/kafka-operator
- CrunchyData PostgreSQL operator: https://github.com/CrunchyData/postgres-operator
- Mongo Operator: https://github.com/kirk-enterprise/mongo-operator
- Kong Operator: https://github.com/upmc-enterprises/kong-operator
- Cilium (L3-L7 network security, loadbalancing, networking for k8s): https://github.com/cilium/cilium

### Controllers

- Kelsey Hoightower's valut controller - https://github.com/kelseyhightower/vault-controller
- Bitnami's controller for one-way encrypted secrets - https://github.com/bitnami/sealed-secrets
- Torch Box's kubernetes ondemand database provisioner - https://github.com/torchbox/k8s-database-controller
- Alexander Staubo's config contrller reloads application on config map changeshttps://github.com/atombender/k8s-config-controller
- uswitch's sqs autoscale controller - https://github.com/uswitch/sqs-autoscaler-controller
- PreviousNext's storage class for provisioning AWS EFS https://github.com/previousnext/k8s-aws-efs
- Martin Linkhorst's remote manifest controller applies remote manifests - https://github.com/linki/manifest-controller

TODO:
- Dig through commits on GitHub: https://github.com/search?q=ThirdPartyResource&type=Commits&utf8=%E2%9C%93

Resources:
- [Kubernetes Docs](https://kubernetes.io/docs/user-guide/thirdpartyresources/)
- [Kubernetes Feature](https://github.com/kubernetes/features/issues/95)

I am interested in documenting all of the users and getting some more feedback on what is and isn't working.
