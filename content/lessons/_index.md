---
bookFlatSection: true
bookCollapseSection: true

title: 'Lessons'
weight: 1
---


Course plan
===========


The following topics are discussed throughout the course. Depending on the circumstances, like the
length of the semester or student feedback, the actual agenda may vary. This list should be
seen more as a list of possibilities/choices rather than strict TODO or check list.
 
{{< hint >}}
The order of topics below does not necessarily reflect the order in which they are
being discussed.
{{< /hint >}}
 

| Topic                                 | Objectives                       | Technologies           | Activities(s)    |
|---------------------------------------|----------------------------------|------------------------|------------------|
| [What is DevOps and what is it not?]({{< relref "./topics/what-is-devops" >}})                       | DevOps culture, Agile, Site Reliability Engineering                                              | *N/A*                                                                    | 🗣 sticky-notes session  |
| [DevOps Principles]({{< relref "./topics/devops-principles" >}})                                     | [Configuration, Infrastructure]-as-Code, Automation, Dependency Management, Software life cycle  | *N/A*                                                                    | 🙌 demonstrate [*showcase*](https://gitlab.bht-berlin.de/fb6-wp11-devops/showcase)  |
| [Twelve-Factor App]({{< relref "./topics/twelve-factors" >}})                                        | Understand the 12 factors and how to satisfy them                                                | *N/A*                                                                    | 🗣 assess Twelve-Factor compliance of an example app  |
| [Continuous Automation]({{< relref "./topics/continuous-automation" >}})                             | CI/CD, Triggers, GitOps                                                                          | Jenkins, GitLab, Github Actions                                          | 💡 [set up and run a pipeline]({{< ref "/tutorials/define-and-run-pipeline" >}})  |
| [Virtualization vs. Containerization]({{< relref "./topics/virtualization-vs-containerization" >}})  | Differences - similar patterns - usage, hypervisors, container engines, build tools              | Docker, Podman, Buildah, VirtualBox, QEMU, Packer                        | 💡 [Build a container image and start a container]({{< ref "/tutorials/build-container-image-and-start-container" >}})  |
| [Cloud Infrastructure]({{< relref "./topics/cloud-infrastructure" >}})                               | What classifies as Infrastructure, Public vs. Private cloud, XaaS                                | Compute & Network & Storage; AWS, GCP, DigitalOcean                      | 💡 [Spin up a virtual machine locally]({{< ref "/tutorials/spin-up-virtual-machine-locally" >}})  |
| [Infrastructure Allocation]({{< relref "./topics/infrastructure-allocation">}})                      | infrastructure life cycle, apply Infrastructure-as-Code                                          | Terraform, Pulumi                                                        | 💡 [Allocate and access a virtual machine in the cloud]({{< ref "/tutorials/allocate-machine-in-cloud" >}}) |
| [Configuration Management]({{< relref "./topics/configuration-management" >}})                       | Apply Config-as-Code, giving a machine its purpose                                               | Ansible                                                                  | 💡 [Automate web-server installation & configuration]({{< ref "/tutorials/automate-webserver-configuration" >}})  |
| [Deployment Strategies]({{< relref "./topics/deployment-strategies" >}})                             | Resilience, Zero-downtime deployment, Service Discovery, Load balancing                          | Nginx, consul, DNS                                                       | 💡 [Update an instance group of an app behind a load balancer]({{< ref "/tutorials/update-version-as-instance-group" >}})  |
| [Container Orchestration]({{< relref "./topics/container-orchestration" >}})                         | Purpose, implementations, market, basic usage                                                    | Kubernetes                                                               | 💡 [Deploy an application on Kubernetes and make it available from the outside]({{< ref "/tutorials/become-familiar-with-kubernetes" >}})  |
| [Advanced Kubernetes]({{< relref "./topics/advanced-kubernetes" >}})                                 | Architecture, Concepts & Features, Tooling                                                       | Helm                                                                     | 💡 [Deploy an application with Helm]({{< ref "/tutorials/deploy-workload-with-helm" >}}); 💡 [Provision Kubernetes]({{< ref "/tutorials/provision-kubernetes" >}})  |
| [Monitoring & Observability]({{< relref "./topics/monitoring-and-observability" >}})                 | Logging, Metrics, Alerts, Tracing, System health, Exporter vs. Collector, push vs. pull          | Prometheus, Grafana, Alertmanager, EFK (Elasticsearch, Fluentd, Kibana)  | 💡 [Investigate system status & write an exporter]({{< ref "/tutorials/investigate-system-status" >}})  |
| [Persistence & Backups]({{< relref "./topics/persistence-and-backups" >}})                           | distributed, storage, storage types, backup strategies                                           | AWS S3, NFS, Ceph                                                        | 💡 [Encrypt and store a backup offsite]({{< ref "/tutorials/create-encrypted-backup" >}})  |
| [Dev-Security-Ops]({{< relref "./topics/dev-security-ops" >}})                                       | account types, secret & permission management, Identity Provider, 2-Factor-Auth                  | Sops, Vault, SSH, `.gitignore`                                           | *N/A*  | 