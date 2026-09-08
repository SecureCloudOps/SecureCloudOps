# Mohamed A. Mohamed

### Cloud Infrastructure • Automation • Security • Reliability

I build secure cloud platforms, automate application delivery, and test how systems recover when things fail.

My independent projects focus on GitOps, least-privilege access, Kubernetes operators, and AI-assisted incident investigation. Each project documents its implementation, validation evidence, and limitations.

[Portfolio](https://securecloudops.github.io/) · [LinkedIn](https://www.linkedin.com/in/mohamed007-cloud/) · [Email](mailto:mohamed0395@gmail.com)

## Selected Engineering Projects

### [ForgePath](https://github.com/SecureCloudOps/ForgePath)

A developer platform that turns a Backstage request into a secured FastAPI service delivered through GitOps.

- Enforces workload policies and verifies signed, immutable artifacts.
- Demonstrated 5% canary containment and approximately 6.2-minute recovery during a controlled local incident exercise.
- Includes architecture decisions, negative tests, and an incident postmortem.

**Backstage · Argo CD · Argo Rollouts · Kyverno · Prometheus**

### [KubeBackup Operator](https://github.com/SecureCloudOps/database-backup-operator)

A Go Kubernetes operator for declarative PostgreSQL backups and checksum-verified restores.

- Supports MinIO and Amazon S3 storage.
- Validated through 21 controller specs and 3 Kind end-to-end scenarios.
- Includes hardened workloads, signed release artifacts, and recovery documentation.

**Go · Kubernetes · PostgreSQL · S3 · Terraform**

### [Kubernetes Security Triage Agent](https://github.com/SecureCloudOps/kubernetes-security-triage-agent)

A read-only security scanner that correlates Kubernetes misconfigurations and image vulnerabilities, with optional OpenAI analysis.

- Separates confirmed findings, plausible attack paths, and AI interpretation.
- Restricts cluster access and prevents AI from changing deterministic findings.
- Includes 189 automated tests and documented secure/vulnerable workload demonstrations.

**Python · Kubernetes RBAC · Trivy · OpenAI · JSON Schema**

### [AWS Incident Triage Agent](https://github.com/SecureCloudOps/aws-incident-triage-agent)

An AI-assisted investigation tool that collects ECS and CloudWatch evidence and produces structured incident analyses.

- Uses read-only AWS permissions.
- Separates observed facts from hypotheses and recommended next steps.

**Python · AWS ECS · CloudWatch · IAM · OpenAI**

## Core Technologies

- **Cloud & Infrastructure:** AWS, Terraform, Linux, networking
- **Platform & Delivery:** Kubernetes, Docker, Helm, GitHub Actions, Argo CD, Backstage
- **Security:** IAM, OIDC, Kyverno, Trivy, Checkov, Gitleaks
- **Observability:** Prometheus, Grafana
- **Languages:** Python, Go, Bash

## Certifications

- AWS Certified Solutions Architect – Associate
- AWS Certified SysOps Administrator – Associate
- Certified Kubernetes Administrator
- CompTIA Security+
