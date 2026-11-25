# dhileep kumar — Lead DevOps Engineer

**9 years · SRE · Platform Engineering · Disaster Recovery & Compliance**

> Building resilient platforms, automating compliance, and keeping the pager quiet.

---

## 📊 At a Glance

```bash
$ whoami
→ dhileep-kumar — Lead DevOps Engineer

$ kubectl get clusters --context=portfolio
→ platform-prod     Ready 3/3 nodes
→ platform-staging  Ready 2/2 nodes

$ terraform plan -var-file=prod.tfvars
→ Plan: 3 to add, 0 to change, 0 destroy.

$ tail -f /var/log/incidents.log
→ WARN sev=1 service=checkout error=timeout retries=3
```

---

## 💻 Terminal Showcase

A snapshot of the tools I work with daily:

```bash
$ whoami
→ dhileep-kumar — Lead DevOps Engineer

$ kubectl get clusters --context=portfolio
→ platform-prod     Ready 3/3 nodes
→ platform-staging  Ready 2/2 nodes

$ terraform plan -var-file=prod.tfvars
→ Plan: 3 to add, 0 to change, 0 destroy.

$ tail -f /var/log/incidents.log
→ WARN sev=1 service=checkout error=timeout retries=3
```
```bash
$ kubectl get nodes -o wide
→ ready   master   4   v1.29.0   k8s-node-1   <none>   <none>   Ready
→ ready   master   4   v1.29.0   k8s-node-2   <none>   <none>   Ready
→ ready   master   4   v1.29.0   k8s-node-3   <none>   <none>   Ready

$ kubectl get pods -A --field-selector=status.phase=Running
→ kube-system   coredns-5d95...   1/1   Running   0   23d
→ kube-system   kube-dns-...      1/1   Running   0   23d
→ monitoring    prometheus-server-...   2/2   Running   0   23d
```
```bash
$ docker ps
→ CONTAINER ID   IMAGE          COMMAND       CREATED       STATUS        PORTS     NAMES
→ abc1234        nginx:latest   "nginx -g 'daemon"   2 hours ago   Up 2 hours   80/tcp   web-server
→ def5678        redis:7-alpine "docker-entrypoint.sh"   23 minutes ago   Up 23 minutes   6379/tcp   redis-cache
```
```bash
$ helm list -A
→ NAME            NAMESPACE   REVISION   UPDATED      STATUS      CHART               APP VERSION
→ prometheus      monitoring  1          2 days ago   deployed    prometheus-2.45.0   2.45.0
→ argocd          kube-system 2          2 days ago   deployed    argocd-5.53.0       5.53.0
```
```bash
$ gh run list --limit 5
→ #1234   dhileepdev/dr-incident-dashboard   Finished   2026-01-15   42s
→ #1235   dhileepdev/compliance-security-scanner   Queued     2026-01-15   —
→ #1236   dhileepdev/terraform-landing-zone   Running    2026-01-15   15m
```
```bash
$ aws sts get-caller-identity
→ Account: 123456789012
→ UserId: AIDA1234567890123456789
→ Arn: arn:aws:iam::123456789012:user/dhileep-kumar
```
```bash
$ terraform init
→ Initializing the backend...
→ Initializing provider plugins...
→ Terraform has been successfully initialized!
```
```bash
$ kubectl logs -n monitoring $(kubectl get pods -n monitoring -l app=prometheus -o jsonpath='{.items[0].metadata.name}') --tail=5
→ 2026-01-15T10:30:00Z INFO Successfully connected to TSDB
→ 2026-01-15T10:29:00Z INFO Received 15000 series
→ 2026-01-15T10:28:00Z WARN Scraping target removed: job=kubernetes-nodes
```
```bash
$ git log --oneline -5
→ 9f8a3b2 feat: add DR dashboard dashboard widget
→ a3b2c1d fix: kyverno policy for image scanning
→ e5d4c3b chore: update terraform module versions
→ 7c6b5a2 docs: update README with new commands
→ 2a1b0c9 refactor: simplify CI pipeline
```
```bash
$ argocd app list -o wide
→ dr-incident-dashboard   ns1   healthy   Synced   2026-01-15T10:30:00Z
→ compliance-scanner    ns2   healthy   Synced   2026-01-15T10:25:00Z
→ landing-zone          ns3   healthy   Synced   2026-01-15T10:20:00Z
```
```bash
$ kubectl get pods -n prod -o jsonpath='{.items[0].status.containerStatuses[0].ready}'
→ true
```

---

## 🛠️ Core Expertise

- **SRE & Reliability**: SLI/SLO definition, error budget management, incident command
- **CI/CD & Automation**: GitOps, pipeline orchestration, infrastructure as code
- **Platform Engineering**: Kubernetes, Terraform, cost optimization, multi-cluster management
- **Compliance & Security**: Kyverno policies, Trivy scanning, SOC2/DORA readiness
- **Disaster Recovery**: DR drills, backup strategies, RTO/RPO planning

---

## 📌 Pinned Projects

| Project | Description |
|---------|-------------|
| [dr-incident-dashboard-portfolio](https://github.com/dhileepdev/dr-incident-dashboard-portfolio) | DR + incident command dashboard |
| [compliance-security-scanner-portfolio](https://github.com/dhileepdev/compliance-security-scanner-portfolio) | Kyverno + Trivy + CI compliance |
| [terraform-landing-zone-portfolio](https://github.com/dhileepdev/terraform-landing-zone-portfolio) | Terraform landing zone + cost management |

---

## 🚧 In Progress

| Project | Description |
|---------|-------------|
| [devops-plugin-ecosystem](https://github.com/dhileepdev/devops-plugin-ecosystem) | Plugin discovery & health platform |
| [evidence-kit](https://github.com/dhileepdev/evidence-kit) | Audit evidence packs, signed + checksummed |

---

## 📫 Let's Connect

- **GitHub**: [@dhileepdev](https://github.com/dhileepdev)
- **Email**: dhileep@example.com
- **Location**: [Your City, Country]
- **Blog**: [your-blog.com] (coming soon)

---

## 💡 Philosophy

> "Automate everything that can be automated, and document the rest. A good SRE makes themselves obsolete by building systems that run themselves."

---

*⚡️ Fun fact: I run Kubernetes clusters on homelab hardware on weekends. Yes, I live the dream 24/7.*

*🛠️ Tech stack: Kubernetes • Terraform • GitHub Actions • ArgoCD • Prometheus • Grafana • Kyverno • Trivy • Python • Go*