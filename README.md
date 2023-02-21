# Infrastructure Manifests

The applications to deploy onto the WaffleHacks K3S cluster as defined in [infrastructure/cluster][].

Currently, this deploys:
- [ArgoCD][]
- [cert-manager][]
- [Contour][]
- [external-dns][]
- [External Secrets Operator][]
- [governor][] pod reaper

Everything is automatically deployed with [ArgoCD][] using the [app of apps][] pattern.


[infrastructure/cluster]: https://github.com/WaffleHacks/infrastructure/tree/main/cluster
[ArgoCD]: https://argo-cd.readthedocs.io/en/stable/
[cert-manager]: https://cert-manager.io/
[Contour]: https://projectcontour.io/
[external-dns]: https://github.com/kubernetes-sigs/external-dns
[External Secrets Operator]: https://external-secrets.io/
[governor]: https://github.com/keikoproj/governor
[app of apps]: https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/#app-of-apps-pattern
