# fruits-api demo manifests

Manifests for `quay.io/daytwo/fruits-api:v2`, used as the GitOps demo application
managed by Red Hat ACM + Argo CD (push model).

- UI: `/`
- API: `/fruits` (GET list, POST add)
- Namespace: `demo-gitops`
- OIDC disabled for the demo (`QUARKUS_OIDC_TENANT_ENABLED=false`)
