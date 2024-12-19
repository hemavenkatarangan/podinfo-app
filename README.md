Introduction to Flux

FluxCD is a Continuous Delivery (CD) and GitOps tool for Kubernetes.

Flux is a Kubernetes-based application deployment and management solution. It works by monitoring your source code repository for changes and automatically generating deployments to keep your applications up to date.

Flux manages deployments using the GitOps concept, which implies that your application’s desired state is stated in source code and version-controlled using Git. This method makes it simple to track deployment modifications and collaborate with other team members.

GitOps:

GitOps is a method of managing your infrastructure and apps in such a way that the entire system is described declaratively and version controlled (most likely in a Git repository), with an automated mechanism ensuring that the deployed environment matches the state indicated in the repository.

Flux Supported Tools:

Flux works well with the below open source (CNCF Landscape) tools.

    Kubernetes
    Helm
    Grafana
    Istio
    Prometheus
    Linkerd
    Kyverno
    SOPS

Features of FluxCD:

    Source configuration from Git and Helm repositories, and S3-compatible buckets (e.g., Minio)
    Kustomize and Helm support
    Event-triggered and periodic reconciliation
    Integration with Kubernetes RBAC
    Health assessment (clusters and workloads)
    Dependency management (infrastructure and workloads)
    Alerting to external systems (webhook senders)
    External events handling (webhook receivers)
    Automated container image updates to Git (image scanning and patching)
    Policy-driven validation (OPA, Kyverno, admission controllers)
    Seamless integration with Git providers (GitHub, GitLab, Bitbucket)
    Interoperability with workflow providers (GitHub Actions, Tekton, Argo)
    Interoperability with Cluster API (CAPI) providers