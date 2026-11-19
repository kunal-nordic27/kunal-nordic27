Contact & Profile
GitHub: https://github.com/kunal-nordic27/kunal-nordic27
Email: kashyapgi8957@gmail.com
Target Markets:🌍🇩🇰🇫🇮🇸🇪 Denmark, Finland, Sweden, Europe
# Enterprise Platform Engineering & DevSecOps

Hands-on platform engineering repository focused on multi-cloud infrastructure, container orchestration, GitOps delivery, zero-trust security, observability, and internal developer platform (IDP) automation—validated by an automated GitHub Actions CI pipeline (`.github/workflows/platform-ci.yml`).

## Target Scope & Architecture Focus

Designed for **Platform Engineer / Senior & Staff Platform Engineer** roles across **Denmark, Finland, Sweden, and Europe**, prioritizing:
- Reproducible Infrastructure as Code (IaC) and multi-cloud foundations
- Hardened container builds, Kubernetes workloads, and Helm packaging
- GitOps-driven desired-state delivery and least-privilege access (IAM/RBAC & OIDC)
- Shift-left and supply-chain security (Semgrep, Trivy, Cosign)
- Standardized telemetry, metrics, dashboards, and service cataloging (OpenTelemetry, Prometheus, Grafana, Backstage)
- Python automation and pipeline validation

## Core Stack (19 Tools)

| Domain | Tools |
| --- | --- |
| **Cloud & IaC** | AWS, Azure, Google Cloud, Terraform |
| **Containers & Kubernetes** | Docker, Kubernetes (EKS, AKS, GKE), Helm |
| **CI/CD & GitOps** | GitHub Actions, GitOps |
| **Security & Zero-Trust** | IAM & RBAC, OIDC, Trivy, Semgrep, Cosign |
| **Observability, IDP & Automation** | Prometheus, Grafana, OpenTelemetry, Backstage, Python |

## Repository Structure

```text
.
├── .github/
│   └── workflows/
│       └── platform-ci.yml      # Automated CI validation and pass gate
├── infrastructure/
│   ├── aws/
│   ├── azure/
│   └── gcp/
├── workloads/
│   ├── docker/
│   ├── kubernetes/
│   └── helm/
├── gitops/
├── security/
├── observability/
│   ├── prometheus/
│   ├── grafana/
│   └── opentelemetry/
├── backstage/
└── scripts/
CI / CD & Validation
All changes are verified through .github/workflows/platform-ci.yml, which checks:
Terraform formatting and module validation
Container image builds and Helm chart linting/rendering validation
Workflow permissions, static analysis (Semgrep), vulnerability/misconfiguration scanning (Trivy), and signature verification hooks (Cosign / OIDC)
Python syntax/test automation, Backstage catalog checks, and repository component structure
Final pass gate (pipeline-gate) requiring all upstream checks to succeed
Contact & Profile
GitHub: https://github.com/kunal-nordic27/kunal-nordic27
Email: kashyapgi8957@gmail.com
Target Markets:🌍🇩🇰🇫🇮🇸🇪 Denmark, Finland, Sweden, Europe
