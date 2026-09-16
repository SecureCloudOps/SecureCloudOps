# Mohamed A. Mohamed

### Cloud Infrastructure • Automation • Security • Reliability

I build secure cloud platforms, automate application delivery, and test how systems recover when things fail.

**AWS · Kubernetes · Terraform · Python · Go · GitHub Actions**

Boston, MA · [Portfolio](https://securecloudops.github.io/) · [LinkedIn](https://www.linkedin.com/in/mohamed007-cloud/) · [Email](mailto:mohamed0395@gmail.com)

## Selected Engineering Projects

Independent projects with documented validation evidence and limitations. Results below come from controlled lab exercises.

### [EKS Production Operations Lab](https://github.com/SecureCloudOps/eks-production-operations-lab)

AWS EKS operations exercises covering staged upgrades, blocked drains, OOM triage, IAM remediation, and ingress failures.

**Observed result:** Completed a Kubernetes 1.35 → 1.36 upgrade with 9 HTTP 502s across 26,611 requests; the zero-failure objective was not met. [Upgrade evidence](https://github.com/SecureCloudOps/eks-production-operations-lab/blob/main/evidence/cluster-upgrade/summary.md)

### [ForgePath](https://github.com/SecureCloudOps/ForgePath)

A secure self-service delivery platform connecting Backstage, GitOps, policy enforcement, and SLO-gated canary releases.

**Observed result:** Contained a defective canary at 5% exposure and recorded approximately 6.2-minute recovery during a local incident exercise. [Incident evidence](https://github.com/SecureCloudOps/ForgePath/blob/main/docs/evidence/postmortems/INC-20260824T152814Z.md)

### [KubeBackup Operator](https://github.com/SecureCloudOps/database-backup-operator)

A custom Go Kubernetes operator for PostgreSQL backups and checksum-verified restores using MinIO or Amazon S3.

**Validation:** 21 controller specs and 3 Kind end-to-end scenarios passed, including restored-data checks. [Validation evidence](https://github.com/SecureCloudOps/database-backup-operator#validation-evidence)

**More projects:** [Kubernetes Security Triage Agent](https://github.com/SecureCloudOps/kubernetes-security-triage-agent) · [AWS Incident Triage Agent](https://github.com/SecureCloudOps/aws-incident-triage-agent) · [CloudSecOps LLM Fine-Tuning](https://github.com/SecureCloudOps/cloudsecops-llm-finetuning)

## Certifications

- AWS Certified Solutions Architect – Associate
- AWS Certified SysOps Administrator – Associate
- Certified Kubernetes Administrator (CKA)
- CompTIA Security+
