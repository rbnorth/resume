# Hi, I'm Robert "Brent" Northcutt 👋

**Senior DevOps / SRE Engineer**

📧 rbnorthcutt@gmail.com &nbsp;|&nbsp; 📱 (406) 570-1893

---

## About Me

Senior DevOps/SRE engineer with 15+ years of experience keeping production stable at scale — from managing 400+ MySQL servers across 30 datacenters to migrating monolithic applications to cloud-native infrastructure on AWS, GCP, and Azure. I build the things that hold up under pressure, write everything down so the next person isn't starting from scratch at 2am, and find the unglamorous fixes that save everyone headaches later. I've worked across the full compliance stack — DoD, DISA, FedRAMP, HIPAA, PCI, SOC Type 2 — including classified environments under Secret clearance. I don't just keep the lights on. I make sure they don't go out in the first place.

---

## 🛠️ Technical Skills

| Category | Tools |
|---|---|
| **Cloud Platforms** | AWS, Google Cloud Platform (GCP), Microsoft Azure |
| **CI/CD Pipelines** | GitLab CI/CD, AWS CodePipeline |
| **Containers & Orchestration** | Docker, Docker Compose, Kubernetes, Helm |
| **Programming & Scripting** | Python, Bash, Go |
| **Monitoring & Logging** | New Relic, Grafana, Datadog, CloudWatch, Cloud Monitoring |
| **Infrastructure as Code** | Terraform, CloudFormation, Terragrunt, OpenTofu |
| **Config Management** | Ansible |
| **Security & Compliance** | DoD, DISA, FedRAMP, HIPAA, PCI, SOC Type 2 |
| **Version Control** | Git, GitHub, GitLab |
| **AI Tools** | Claude AI (documentation, runbook drafting, code, sanity checks) |

---

## 💼 Professional Experience

### DevOps Engineer — Medical Home Network
*Remote | Sep 2025 – Present*

- Migrated alerting from PRTG to Datadog across 55 VMs — building 200+ alerts from scratch covering CPU, memory, load, network, and SSL cert tracking, plus custom log-based alerts for a legacy SAS environment.
- Embedded runbook steps directly into alerts so on-call engineers have clear, actionable guidance at 2am — not a blank page. The SAS runbooks have effectively eliminated escalations from that team.
- Contributing to infrastructure as code across prod, dev, and UAT environments using Terragrunt and OpenTofu — extending and maintaining existing configurations to keep deployments consistent.
- Ongoing decommissioning of legacy Azure resources — identifying and removing unused VMs, disks, and services as part of a broader environment modernization effort.
- Driving early-stage VM-to-container migration — set up container repositories and laying groundwork for replacing static virtual machines with containerized workloads.
- Owning documentation and runbook creation across the team — capturing institutional knowledge that previously lived nowhere, embedding fix steps directly into alerts, and using Claude AI to accelerate drafting. The goal: whoever is on call at 2am has what they need without having to ask.

### DevOps Engineer — Viralhog
*Hybrid | Feb 2024 – Feb 2025*

- Built and deployed Cloud Run services on GCP, introducing auto-scaling to a media platform that had none — giving the infrastructure the ability to handle traffic demands without manual intervention.
- Replaced a manual build and deploy process with a full GitLab CI/CD pipeline — introducing Git Flow for branch structure and automating linting, vulnerability scanning, Docker builds, and deployment to Cloud Run.
- Identified and cleaned up over-provisioned and idle GCP resources, reducing monthly cloud spend by roughly 20% without impacting performance.
- Built Docker and Docker Compose environments from scratch so developers could run production-equivalent setups locally — eliminating the "works on my machine" problem.
- Built a Grafana dashboard from scratch on top of Google Cloud Monitoring — the network spike alerting caught a DDoS attack early enough to stop it.
- Wrote Python scripts to automate VM migrations across GCP projects — turning a tedious manual process into something repeatable and clean.

### DevOps Engineer — Tiled
*Remote | Sep 2021 – Jan 2023*

- Improved existing AWS CI/CD pipelines using CodePipeline, CodeBuild, and CodeDeploy — adding a manual approval gate before production deployments to eliminate accidental releases while keeping the automated build process intact.
- Set up CloudWatch and Grafana dashboards to track application performance metrics and surface trends that informed release decisions.
- Monitored build pipelines for failures, triaged issues, and coordinated with developers to get fixes in — keeping releases on track and unblocked.
- Acted as release manager — moving code through repos, coordinating with Dev and QA, and handling hotfixes and cherry-picks to make sure only the right changes made it to production.
- Managed Docker containers built through the CI/CD pipeline and supported a customer running a local Kubernetes cluster with our product — handling operational issues and keeping their environment stable.

### DevOps Engineer — Wisetail
*Bozeman, MT | May 2019 – Jul 2020*

- Led a 6-month migration of a monolithic Learning Management System from DigitalOcean to AWS — rebuilding infrastructure from scratch with CloudFormation, standing up EC2, RDS, S3, and ALB, and deploying via blue/green CI/CD with zero downtime. Moved the product from a single server to a scalable cloud architecture.
- Built New Relic alerting from scratch across dev, staging, and production AWS environments — giving the team early warning on performance issues and reducing time to detection.
- Used Ansible to automate routine MySQL administration tasks — schema management, performance tuning, and ops that previously required manual intervention, freeing up time for infrastructure work.

### MySQL Database Administrator — Oracle
*Bozeman, MT | Mar 2010 – May 2019*

- Managed MySQL database infrastructure at scale — 400+ servers and thousands of schemas across 30 datacenters, with cross-datacenter replication for high availability and disaster recovery.
- Proactively tuned query performance during downtime — using MySQL EXPLAIN to identify bottlenecks and resolving issues through compound indexes, statistics adjustments, and WHERE clause optimization.
- Configured hardware and OS-level settings for optimal IOPS using Flashcache and Fusion-IO cards — including software RAID on Oracle Linux to work around a single-threaded kcrypt limitation until the kernel backport caught up.
- Maintained compliance with DoD, DISA, FedRAMP, HIPAA, PCI, and SOC Type 2 standards across production database environments — including work on classified environments under Secret clearance.

---

## 🎓 Education

**Associate of Applied Science, Computer Information Systems – Programming**
State Fair Community College, Sedalia, MO

---

## 📜 Certifications

- AWS Certified SysOps Administrator, Associate — earned 2021
- AWS Certified Developer, Associate — earned 2021
- AWS Certified Solutions Architect, Associate — earned 2020
- PCEP – Certified Entry-Level Python Programmer

---

📫 Reach me at **rbnorthcutt@gmail.com**
