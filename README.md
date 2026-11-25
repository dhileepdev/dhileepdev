========================================================================
                      .--.         TERRA TERMINAL PROFILE README
                     |o o|        dhileep kumar
                     | . .|        Lead DevOps Engineer · 9 yrs · SRE · Platform Engineering
                ________________________________________________________
                < BUILDING RESILIENT PLATFORMS, AUTOMATING COMPLIANCE, AND   >
                 KEEPING THE PAGER QUIET.                          >
                 ------------------------------------                  >
                  \    ^     ^      /                          |  >
                   \  /     /     /    TERMINAL THEME: TERRA          |>
                    \/     /     /     GREEN ON BLACK AESTHETIC     |>
                     \     /     /                                  |
                      \   /     /                                   |
                       \ /     /    At a Glance:                     |
                        X   X   /                                    |
                       /| | | |/  .---------------------------. |
                      (_| |_|_)  |  $ whoami                       | |
                      / | | | |   → dhileep-kumar — Lead DevOps Engineer| |
                      | | | | |   .-------------------------------. | |
                      | | | | |  $ kubectl get clusters --context=portfolio | |
                      | | | | |   → platform-prod     Ready 3/3 nodes   | |
                      | | | | |   → platform-staging  Ready 2/2 nodes   | |
                      | | | | |   .-------------------------------. | |
                      | | | | |  $ terraform plan -var-file=prod.tfvars   | |
                      | | | | |   → Plan: 3 to add, 0 to change, 0 destroy.| |
                      | | | | |   .-------------------------------. | |
                      | | | | |  $ tail -f /var/log/incidents.log       | |
                      | | | | |   → WARN sev=1 service=checkout error=timeout retries=3| |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ kubectl get nodes -o wide            | |
                      | | | | |  → ready   master   4   v1.29.0   k8s-node-1   | |
                      | | | | |  → ready   master   4   v1.29.0   k8s-node-2   | |
                      | | | | |  → ready   master   4   v1.29.0   k8s-node-3   | |
                      | | | | |   .-------------------------------. | |
                      | | | | |  $ kubectl get pods -A --field-selector=status.phase=Running | |
                      | | | | |  → kube-system   coredns-5d95...   1/1   Running   0   23d | |
                      | | | | |  → kube-system   kube-dns-...      1/1   Running   0   23d | |
                      | | | | |  → monitoring    prometheus-server-...   2/2   Running   0   23d | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ docker ps                           | |
                      | | | | |  → CONTAINER ID   IMAGE          COMMAND       CREATED       STATUS        PORTS     NAMES | |
                      | | | | |  → abc1234        nginx:latest   "nginx -g 'daemon"   2 hours ago   Up 2 hours   80/tcp   web-server | |
                      | | | | |  → def5678        redis:7-alpine "docker-entrypoint.sh"   23 minutes ago   Up 23 minutes   6379/tcp   redis-cache | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ helm list -A                        | |
                      | | | | |  → NAME            NAMESPACE   REVISION   UPDATED      STATUS      CHART               APP VERSION | |
                      | | | | |  → prometheus      monitoring  1          2 days ago   deployed    prometheus-2.45.0   2.45.0 | |
                      | | | | |  → argocd          kube-system 2          2 days ago   deployed    argocd-5.53.0       5.53.0 | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ gh run list --limit 5               | |
                      | | | | |  → #1234   dhileepdev/dr-incident-dashboard   Finished   2026-01-15   42s | |
                      | | | | |  → #1235   dhileepdev/compliance-security-scanner   Queued     2026-01-15   — | |
                      | | | | |  → #1236   dhileepdev/terraform-landing-zone   Running    2026-01-15   15m | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ aws sts get-caller-identity          | |
                      | | | | |  → Account: 123456789012                | |
                      | | | | |  → UserId: AIDA1234567890123456789      | |
                      | | | | |  → Arn: arn:aws:iam::123456789012:user/dhileep-kumar | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ terraform init                        | |
                      | | | | |  → Initializing the backend...         | |
                      | | | | |  → Initializing provider plugins...    | |
                      | | | | |  → Terraform has been successfully initialized! | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ kubectl logs -n monitoring ... --tail=5 | |
                      | | | | |  → 2026-01-15T10:30:00Z INFO Successfully connected to TSDB | |
                      | | | | |  → 2026-01-15T10:29:00Z INFO Received 15000 series | |
                      | | | | |  → 2026-01-15T10:28:00Z WARN Scraping target removed: job=kubernetes-nodes | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ git log --oneline -5                  | |
                      | | | | |  → 9f8a3b2 feat: add DR dashboard dashboard widget | |
                      | | | | |  → a3b2c1d fix: kyverno policy for image scanning | |
                      | | | | |  → e5d4c3b chore: update terraform module versions | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ argocd app list -o wide                | |
                      | | | | |  → dr-incident-dashboard   ns1   healthy   Synced   2026-01-15T10:30:00Z | |
                      | | | | |  → compliance-scanner    ns2   healthy   Synced   2026-01-15T10:25:00Z | |
                      | | | | |  → landing-zone          ns3   healthy   Synced   2026-01-15T10:20:00Z | |
                      | | | | |   '-------------------------------' | |
                      | | | | |                                       | |
                      | | | | |  .-------------------------------. | |
                      | | | | |  $ kubectl get pods -n prod ... ready      | |
                      | | | | |  → true                                    | |
                      | | | | |   '-------------------------------' | |
                      | | | |                                        | |
                      | | | |   Core Expertise:                         | |
                      | | | |  .-------------------------------.        | |
                      | | | |  | SRE & Reliability: SLI/SLO definition, error budget management, incident command | |
                      | | | |  | CI/CD & Automation: GitOps, pipeline orchestration, infrastructure as code | |
                      | | | |  | Platform Engineering: Kubernetes, Terraform, cost optimization, multi-cluster management | |
                      | | | |  | Compliance & Security: Kyverno policies, Trivy scanning, SOC2/DORA readiness | |
                      | | | |  | Disaster Recovery: DR drills, backup strategies, RTO/RPO planning | |
                      | | | |   '-------------------------------'        | |
                      | | | |                                        | |
                      | |   Pinned Projects:                        | |
                      | |  .-------------------------------.      | |
                      | |  | dr-incident-dashboard-portfolio | DR + incident command dashboard | |
                      | |  | compliance-security-scanner-portfolio | Kyverno + Trivy + CI compliance | |
                      | |  | terraform-landing-zone-portfolio | Terraform landing zone + cost management | |
                      | |   '-------------------------------'      | |
                      | |                                        | |
                      | |   In Progress:                          | |
                      | |  .-------------------------------.    | |
                      | |  | devops-plugin-ecosystem | Plugin discovery & health platform | |
                      | |  | evidence-kit | Audit evidence packs, signed + checksummed | |
                      | |   '-------------------------------'    | |
                      | |                                        | |
                      | |   Let's Connect:                        | |
                      | |  .-------------------------------.  | |
                      | |  | GitHub: [@dhileepdev](https://github.com/dhileepdev) | |
                      | |  | Email: dhileep@example.com       | |
                      | |  | Location: [Coimbatore, Tamil Nadu]   | |
                      | |  | Blog: [https://dhileep.info] (coming soon) | |
                      | |   '-------------------------------'  | |
                      | |                                        | |
                      | |   Fun fact: I run Kubernetes clusters on homelab hardware on weekends. Yes, I live the dream 24/7. | |
                      | |                                        | |
                      | |   Tech stack: Kubernetes • Terraform • GitHub Actions • ArgoCD • Prometheus • Grafana • Kyverno • Trivy • Python • Go | |
                      | |                                        | |
                      |   © 2026 dhileepdev. All rights reserved.   | |
                      |                                        | |
                      |    TERMINAL SESSION ENDED                         |>
========================================================================