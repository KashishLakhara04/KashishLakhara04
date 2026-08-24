## Kashish Lakhara

DevOps Engineer at Cloud Solitaire Technologies, Ahmedabad.
I build infrastructure that holds when things fail.

I keep production Kubernetes clusters running across AWS, GCP, Azure and air-gapped bare metal, from control-plane bootstrap to the incidents that page at 3am.

**Some of the work:**

- Automated bare-metal Kubernetes deployment with Ansible and kubeadm, including etcd setup and node tuning
- Brought a control plane back after etcd hit NOSPACE, then automated compaction
- HA control planes with HAProxy and Keepalived on virtual IPs
- Migrated production from on-premise to EKS, added Karpenter for autoscaling, then cut the bill back down afterwards
- Centralised logging with Fluent Bit and OpenSearch; AlertManager routed to Teams by severity
- API server certificate renewal on a CronJob, because doing that by hand is how you forget
- On-device software for a fleet of OpenWrt edge routers: OTA updates with rollback, scheduled backups, DNS/SSL, health alerting
- Traced a control plane's latency to a seven-year-old SSD, using fsync numbers rather than guesswork

### Stack

<p>
<a href="https://kubernetes.io" target="_blank"><img src="https://raw.githubusercontent.com/cncf/artwork/master/projects/kubernetes/icon/color/kubernetes-icon-color.svg" alt="Kubernetes" title="Kubernetes" width="38" height="38"/></a>&nbsp;
<a href="https://etcd.io" target="_blank"><img src="https://raw.githubusercontent.com/cncf/artwork/master/projects/etcd/icon/color/etcd-icon-color.svg" alt="etcd" title="etcd" width="38" height="38"/></a>&nbsp;
<a href="https://fluxcd.io" target="_blank"><img src="https://raw.githubusercontent.com/cncf/artwork/master/projects/flux/icon/color/flux-icon-color.svg" alt="Flux CD" title="Flux CD" width="38" height="38"/></a>&nbsp;
<a href="https://www.terraform.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/terraformio/terraformio-icon.svg" alt="Terraform" title="Terraform" width="38" height="38"/></a>&nbsp;
<a href="https://www.ansible.com" target="_blank"><img src="https://cdn.simpleicons.org/ansible" alt="Ansible" title="Ansible" width="38" height="38"/></a>&nbsp;
<a href="https://aws.amazon.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" alt="AWS" title="AWS / EKS" width="38" height="38"/></a>&nbsp;
<a href="https://cloud.google.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud" title="Google Cloud / GKE" width="38" height="38"/></a>&nbsp;
<a href="https://azure.microsoft.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="Azure" title="Azure" width="38" height="38"/></a>&nbsp;
<a href="https://prometheus.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/prometheusio/prometheusio-icon.svg" alt="Prometheus" title="Prometheus" width="38" height="38"/></a>&nbsp;
<a href="https://grafana.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="Grafana" title="Grafana" width="38" height="38"/></a>&nbsp;
<a href="https://opensearch.org" target="_blank"><img src="https://cdn.simpleicons.org/opensearch" alt="OpenSearch" title="OpenSearch" width="38" height="38"/></a>&nbsp;
<a href="https://fluentbit.io" target="_blank"><img src="https://cdn.simpleicons.org/fluentbit" alt="Fluent Bit" title="Fluent Bit" width="38" height="38"/></a>&nbsp;
<a href="https://longhorn.io" target="_blank"><img src="https://raw.githubusercontent.com/cncf/artwork/master/projects/longhorn/icon/color/longhorn-icon-color.svg" alt="Longhorn" title="Longhorn" width="38" height="38"/></a>&nbsp;
<a href="https://cratedb.com" target="_blank"><img src="https://cdn.simpleicons.org/cratedb" alt="CrateDB" title="CrateDB" width="38" height="38"/></a>&nbsp;
<a href="https://www.postgresql.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="38" height="38"/></a>&nbsp;
<a href="https://www.haproxy.org" target="_blank"><img src="https://www.vectorlogo.zone/logos/haproxy/haproxy-icon.svg" alt="HAProxy" title="HAProxy" width="38" height="38"/></a>&nbsp;
<a href="https://www.proxmox.com" target="_blank"><img src="https://cdn.simpleicons.org/proxmox" alt="Proxmox" title="Proxmox" width="38" height="38"/></a>&nbsp;
<a href="https://www.linux.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="38" height="38"/></a>&nbsp;
<a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://cdn.simpleicons.org/gnubash" alt="Bash" title="Bash" width="38" height="38"/></a>&nbsp;
<a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="38" height="38"/></a>
</p>

### Writing

I write up the failures worth understanding at [techwithkashish.com](https://techwithkashish.com).

- [HikariCP Pool Sizing for Postgres: Why Smaller Is Faster](https://techwithkashish.com/blogs/hikaricp-connection-pool-sizing-postgres): 16 Aug 2026
- [etcd NOSPACE: Recovering a Kubernetes Control Plane Without kubectl](https://techwithkashish.com/blogs/etcd-database-space-exceeded): 15 Aug 2026
- [When a 7-Year-Old Disk Takes Down Your Control Plane](https://techwithkashish.com/blogs/kubeapierrorbudgetburn-etcd-fsync-latency-dying-ssd): 30 May 2026

---

<p>
<a href="https://techwithkashish.com" target="_blank"><img src="https://techwithkashish.com/favicon.svg" alt="techwithkashish.com" title="techwithkashish.com" width="32" height="32"/></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/kashishtwts/" target="_blank"><img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="LinkedIn" title="LinkedIn" width="32" height="32"/></a>&nbsp;&nbsp;
<a href="https://x.com/kashishtwts" target="_blank"><img src="https://cdn.simpleicons.org/x/8b949e" alt="X" title="X" width="32" height="32"/></a>&nbsp;&nbsp;
<a href="mailto:kashishlakhara04@gmail.com"><img src="https://cdn.simpleicons.org/gmail" alt="Email" title="kashishlakhara04@gmail.com" width="32" height="32"/></a>
</p>
