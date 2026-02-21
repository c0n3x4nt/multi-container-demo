# Multi-Container Demo

Tento repozitář slouží pro jednoduchou **OpenShift Sandbox** demonstraci více kontejnerů v jednom Podu.

## Obsah

- `web/` – Apache web server
- `api/` – Flask API server
- `worker/` – jednoduchý worker script
- `multi-container-pod.yaml` – YAML pro nasazení multi-container Podu v OpenShiftu

## Nasazení v OpenShift Sandboxu

1. Přihlaš se do Sandboxu:
```bash
oc login --token=TVUJ_SANDBOX_TOKEN --server=https://api.rm1.0a51.p1.openshiftapps.com:6443
