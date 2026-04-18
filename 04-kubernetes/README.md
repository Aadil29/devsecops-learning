# Kubernetes

Deploy the app. Lock it down. Enforce policy.

## What to build

- Local cluster with minikube or kind
- Deploy the app from module 01 (Deployment, Service, Ingress)
- Harden it: non-root securityContext, resource limits, NetworkPolicy
- Add Kyverno to reject privileged pods — test that it actually blocks them

## Done when

- [ ] App runs on a local cluster
- [ ] A privileged pod gets rejected by Kyverno
- [ ] NetworkPolicy restricts traffic between pods
- [ ] Notes written up

## Notes

See [notes/](notes/)

## Project repos

_None yet._
