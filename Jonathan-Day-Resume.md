# Jonathan Day

(989) 818-2861 | jonathan.d4y@gmail.com | Barryton, MI (open to remote/hybrid)  
**LinkedIn:** [https://www.linkedin.com/in/jonathanlday](https://www.linkedin.com/in/jonathanlday)  

## Professional Summary

Senior Cloud & Platform Engineer with 10+ years architecting production Kubernetes platforms (EKS at scale). Delivered FedRAMP-compliant GovCloud environments, high-throughput LLM workloads on GPU clusters, and SRE transformations achieving 99.999%+ SLOs while cutting cloud costs 30%+. Expert in GitOps, IRSA/OIDC security, OpenTelemetry observability, and AI workflow enablement. Seeking senior Kubernetes/SRE roles with ownership over reliability and innovation at scale.

## Impact Highlights

- Cut cloud compute costs 35%+ via Karpenter, Spot Instances, and Graviton optimization on production EKS clusters.
- Achieved sub-15-minute EKS provisioning, enabling 5x faster dev/test environments.
- Delivered zero-downtime LLM inference scaling to millions of daily requests on GPU nodes.
- Improved team delivery velocity 30% through AI-assisted workflows and GitOps standardization.

## Technical Proficiencies

- **Container Orchestration & Kubernetes**: EKS (P4d/GPU nodes, IRSA, Karpenter autoscaling), AKS, GKE, OpenShift, Docker, Rancher, ArgoCD, FluxCD, Helm, custom controllers/operators
- **Infrastructure as Code & Automation**: Terraform, AWS CloudFormation, Ansible, Jenkins, GitLab CI/CD (OIDC/IRSA), Azure DevOps
- **Cloud Platforms & Cost Optimization**: AWS (GovCloud, EC2 Spot/Savings Plans, Graviton, Image Builder, Packer), Azure, OpenStack; right-sizing, Karpenter provisioning, Spot Instances, Kubecost-style allocation
- **AI/ML Enablement**: LLM inference/deployment (EKS GPU clusters), generative AI tooling, prompt engineering, AI agents (Cursor, MCP plugins), MLOps integration
- **Observability & Monitoring**: OpenTelemetry (OTLP/Collector), Datadog (metrics/traces/logs), Prometheus, Grafana, ELK Stack, SumoLogic, Nagios, PagerDuty alerts
- **SRE & Reliability**: SLO/SLI definition, error budgets, chaos engineering, on-call rotations & incident response (PagerDuty), root-cause analysis
- **Databases & Big Data**: Postgres, MySQL, Redis, Cassandra, Hadoop (CDH), RDS, Hive/Impala
- **Programming & Scripting**: Python, Go, Bash, Perl, Node.js, HCL (Terraform)
- **Other**: Atlassian Suite, Git/GitHub/GitLab, Packer, Artifactory

## Professional Experience

**Senior Cloud Engineer**  
**Zoom** | Barryton, MI (Remote) | December 2023 – Present  
- Chaired Architecture Review Board: Conducted reviews of new systems/architectures for compliance (FedRAMP), security, scalability, and enterprise alignment—mitigating risks across mission-critical deployments.  
- Architected and maintained full AWS infrastructure via IaC (primary Terraform/CloudFormation author), incorporating cost-optimized designs with Karpenter for dynamic node provisioning, Spot Instances/Savings Plans, and Graviton instances—achieving 30–50% reduction in compute costs.  
- Designed and deployed secure GovCloud environments for regulated FedRAMP customers, with cross-account IAM, dedicated capacity, and shared resources (AMI/ECR).  
- Automated EKS provisioning reducing spin-up time from days to <15 minutes, enabling 5x faster developer environments. Refactored existing Terraform to enable zero-downtime node rotations.  
- Engineered high-performance AI chatbot/LLM inference workloads on EKS GPU clusters, optimizing for cost, throughput, and reliability using right-sizing and autoscaling. Led deployments supporting millions of daily LLM inference requests on P4d GPU clusters with zero-downtime upgrades.  
- Accelerated developer productivity by deploying internal platforms (Artifactory, GitLab runners) on EKS and standardizing GitOps pipelines with ArgoCD "app of apps" patterns for multi-region/account consistency.  
- Implemented IRSA-based authentication for GitLab CI/CD, eliminating long-lived credentials and enhancing security posture.  
- Automated AMI creation pipelines using AWS Image Builder and HashiCorp Packer for consistent, hardened images.  
- Developed custom Kubernetes controllers and operators via AI-assisted coding (prompt-driven agents, Cursor, MCP plugins) to extend EKS functionality, automate complex logic, and support observability/chaos experiments.  
- Championed SRE practices: Defined SLIs/SLOs for critical services (latency, availability, error rates), managed error budgets to balance innovation velocity and reliability, and conducted chaos engineering experiments to validate resilience.
- Participated in on-call rotations using PagerDuty: Led incident response, post-mortems, and blameless RCA presentations to executives, reducing MTTR and toil through automation.  
- Enabled AI adoption: Built prompt-driven agents and generative AI workflows, empowering teams to integrate AI tools into daily tasks—driving faster iteration and operational efficiency.  
- Mentored junior engineers on GitOps best practices and AI-assisted development, accelerating team delivery by 30%.

**Staff Operations Engineer**  
**Khoros** | Barryton, MI (Remote) | April 2021 – December 2023  
- Architected comprehensive AWS infrastructure (EKS, EC2, VPC, RDS, S3, Route53, IAM) using Terraform/CloudFormation as code, with cost-aware designs including right-sized resources and Karpenter autoscaling.  
- Served as Kubernetes Architect: Created standardized EKS bootstrap templates covering core add-ons (CSI, IAM authenticator, AWS LB Controller, ExternalDNS/Secrets Store, Cluster Autoscaler/Karpenter, monitoring/logging) via CloudFormation + Ansible.  
- Managed Kubernetes add-ons through GitOps (Flux/ArgoCD/Helm) for declarative, auditable deployments.  
- Automated end-to-end EKS cluster provisioning and bootstrapping in under 45 minutes, enabling rapid, cost-efficient environment spin-up.  
- Implemented advanced observability: Deployed Prometheus/Grafana for metrics collection, integrated Datadog for alerting/dashboards, and laid groundwork for OpenTelemetry adoption in traces/logs.  
- Authored Ansible roles for configuration-as-code across multi-OS environments; supplemented with Chef for EC2 management.  
- Administered Jenkins: Designed pipelines, managed plugins, and handled user/job administration.  
- Contributed to SRE maturity: Supported SLO/SLI tracking, error budget monitoring, and on-call processes with PagerDuty integration for reliable incident handling.

**DevEx Engineer (Developer Experience) / Unix Engineer II**  
**Jackson National Life** | Lansing, MI | December 2019 – December 2019 (DevEx) / January 2018 – December 2019 (Unix)  
- Earned **Certified Kubernetes Administrator (CKA)** certification (CNCF, September 2020).  
- Architected on-premises OpenShift clusters (physical Dell R630 installs, Red Hat integrations) and deployed Rook Ceph for persistent storage.  
- Led Kubernetes core team, piloted Azure Big Data + application workloads using Terraform, and provisioned Kubernetes clusters with Node.js APIs and Dockerfiles.  
- Key contributor to root-cause analysis, performance tuning, automation, and architecture; delivered executive-level presentations.  
- Deployed Ansible Tower (AWX), developed APIs/playbooks/roles, onboarded Cloudera Hadoop (CDH) with encryption/Kerberos, and created internal "JTS Cloud" for on-demand Linux VM provisioning.  
- Automated extensively with Ansible, Perl, Python; enforced security via SELinux, SSSD, PAM.

**Early Career Highlights**  
**Jackson National Life** (Senior Storage Administrator) | Lansing, MI | August 2011 – January 2018  
**Scientific Retail Systems** (Senior Linux Administrator) | Caro, MI | July 2007 – July 2011  

- Managed 10+ PB enterprise storage (Cisco MDS, IBM SVC/Hitachi/FlashSystem/3PAR) and provided senior leadership on architecture, budgeting, and procurement.  
- Pioneered automation through multi-year data collection, scripting, and standardized processes to enable level-1 off-hours support.  
- Scaled and managed 500+ remote Linux systems across 300+ retail locations; administered PostgreSQL with HIPAA-sensitive data and defined standardized OS configurations for Red Hat/Windows environments.

## Education & Certifications

- **B.S. Electrical Engineering**, Minor in Mathematics – Cedarville University, Cedarville, OH (May 2004)  
  Focus: VLSI/CMOS design & fabrication, FPGA/logic  
- **Certified Kubernetes Administrator (CKA)** – Cloud Native Computing Foundation (September 2020)  
- High School Diploma (Honors) – Calvary Baptist Academy, Midland, MI (June 2000)
