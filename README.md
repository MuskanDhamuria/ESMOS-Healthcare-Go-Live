# ESMOS Healthcare Go-Live

## Structure

- `app/`: application source code
- `infra/`: infrastructure as code
  - `infra/k8s/`: Kubernetes manifests (`base/` + `overlays/`)
- `.github/workflows/`: CI/CD workflows (e.g. build + push to ACR)

