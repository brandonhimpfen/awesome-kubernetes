# Awesome Kubernetes [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1012651521.svg)](https://doi.org/10.5281/zenodo.19680483)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of awesome tools, resources, and projects for Kubernetes.

Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications. This list is for developers, DevOps engineers, SREs, and anyone building or operating systems on Kubernetes.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Getting Started](#getting-started)
- [Learning Resources](#learning-resources)
- [Tools](#tools)
- [Operators](#operators)
- [Monitoring & Logging](#monitoring--logging)
- [Security](#security)
- [Helm](#helm)
- [Networking & Ingress](#networking--ingress)
- [CI/CD](#cicd)
- [Serverless](#serverless)
- [Service Mesh](#service-mesh)
- [Distributions](#distributions)
- [Cloud Platforms](#cloud-platforms)
- [Open Source Projects](#open-source-projects)
- [Related Awesome Lists](#related-awesome-lists)

## Getting Started

- [Kubernetes Official Docs](https://kubernetes.io/docs/) – The official documentation and user guides.
- [Play with Kubernetes](https://labs.play-with-k8s.com/) – A free online Kubernetes lab environment.
- [Katacoda Kubernetes Courses](https://www.katacoda.com/courses/kubernetes) – Interactive scenarios for learning Kubernetes.

## Learning Resources

- [Awesome Kubernetes (Learnk8s)](https://learnk8s.io/awesome-kubernetes) – A categorized list of Kubernetes learning resources.
- [Kubernetes by Example](https://kubernetesbyexample.com/) – Real-world Kubernetes examples and tutorials.
- [The Illustrated Children's Guide to Kubernetes](https://www.cncf.io/phippy/) – Friendly introduction to Kubernetes concepts.
- [Kubernetes Patterns](https://www.oreilly.com/library/view/kubernetes-patterns/9781492050278/) – O’Reilly book on reusable Kubernetes design patterns.

## Tools

- [kubectl](https://kubernetes.io/docs/reference/kubectl/) – CLI to interact with Kubernetes clusters.
- [k9s](https://k9scli.io/) – Terminal UI for managing Kubernetes clusters.
- [Lens](https://k8slens.dev/) – The Kubernetes IDE for monitoring and management.
- [Skaffold](https://skaffold.dev/) – Workflow tool for continuous development on Kubernetes.
- [kubectx/kubens](https://github.com/ahmetb/kubectx) – Switch contexts and namespaces easily.

## Operators

- [Operator SDK](https://sdk.operatorframework.io/) – Build Kubernetes Operators using Go, Helm, or Ansible.
- [Prometheus Operator](https://github.com/prometheus-operator/prometheus-operator) – Manages Prometheus monitoring in Kubernetes.
- [Elastic Operator](https://github.com/elastic/cloud-on-k8s) – Run Elastic Stack on Kubernetes.

## Monitoring & Logging

- [Prometheus](https://prometheus.io/) – Monitoring system and time-series database.
- [Grafana](https://grafana.com/) – Dashboarding and visualization tool.
- [Loki](https://grafana.com/oss/loki/) – Logging system for cloud-native infrastructure.
- [Fluent Bit](https://fluentbit.io/) – Lightweight log processor and forwarder.
- [Kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) – Exposes Kubernetes objects as Prometheus metrics.

## Security

- [Kube-bench](https://github.com/aquasecurity/kube-bench) – Checks your cluster against the CIS Kubernetes Benchmark.
- [Kubesec](https://kubesec.io/) – Security risk analysis for Kubernetes resources.
- [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper) – Policy controller for Kubernetes.
- [Trivy](https://github.com/aquasecurity/trivy) – Vulnerability scanner for container images.

## Helm

- [Helm](https://helm.sh/) – Package manager for Kubernetes.
- [Artifact Hub](https://artifacthub.io/) – Find, install, and publish Helm charts.
- [Helmfile](https://github.com/helmfile/helmfile) – Declarative configuration management for Helm.

## Networking & Ingress

- [NGINX Ingress Controller](https://kubernetes.github.io/ingress-nginx/) – Popular ingress controller using NGINX.
- [Traefik](https://doc.traefik.io/traefik/) – Cloud-native edge router with Kubernetes integration.
- [Cilium](https://cilium.io/) – Networking and security using eBPF.

## CI/CD

- [Argo CD](https://argo-cd.readthedocs.io/) – Declarative GitOps continuous delivery.
- [Tekton](https://tekton.dev/) – Kubernetes-native CI/CD pipelines.
- [Flux](https://fluxcd.io/) – GitOps tool for continuous delivery.

## Serverless

- [Knative](https://knative.dev/) – Serverless workloads on Kubernetes.
- [OpenFaaS](https://www.openfaas.com/) – Functions-as-a-Service for Kubernetes.
- [Kubeless](https://kubeless.io/) – Kubernetes-native serverless framework.

## Service Mesh

- [Istio](https://istio.io/) – Connect, secure, and observe services.
- [Linkerd](https://linkerd.io/) – Lightweight and fast service mesh.
- [Consul](https://www.consul.io/docs/k8s) – Service mesh and service discovery.

## Distributions

- [K3s](https://k3s.io/) – Lightweight Kubernetes distribution by Rancher.
- [MicroK8s](https://microk8s.io/) – Low-ops Kubernetes for developers and IoT.
- [Minikube](https://minikube.sigs.k8s.io/) – Run Kubernetes locally.

## Cloud Platforms

- [Amazon EKS](https://aws.amazon.com/eks/) – Managed Kubernetes on AWS.
- [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine) – Managed Kubernetes on Google Cloud.
- [Azure AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/) – Managed Kubernetes on Microsoft Azure.
- [DigitalOcean Kubernetes](https://www.digitalocean.com/products/kubernetes/) – Simple Kubernetes hosting.

## Open Source Projects

- [Kustomize](https://kubectl.docs.kubernetes.io/pages/app_management/introduction.html) – Kubernetes native configuration management.
- [Kubecost](https://www.kubecost.com/) – Cost monitoring and optimization.
- [Keda](https://keda.sh/) – Kubernetes Event-driven Autoscaling.
- [Velero](https://velero.io/) – Backup and restore for Kubernetes.

## Related Awesome Lists

- **[Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)** – Tools and resources for DevOps practices.
- **[Awesome CI](https://github.com/awesomelistsio/awesome-ci)** – Continuous integration tools.
- **[Awesome MLOps](https://github.com/awesomelistsio/awesome-mlops)** – Machine learning operations tools and platforms.
  
## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
