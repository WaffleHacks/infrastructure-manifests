[![Status](https://deploy.wafflehacks.cloud/api/badge?name=apps&revision=true)](https://deploy.wafflehacks.cloud/applications/apps)

# Infrastructure Manifests

The applications to deploy onto the WaffleHacks K3S cluster as defined in [infrastructure/cluster][].

Currently, this deploys:
- [ArgoCD][] [![Status](https://deploy.wafflehacks.cloud/api/badge?name=argocd&revision=true)](https://deploy.wafflehacks.cloud/applications/argocd)
- [cert-manager][] [![Status](https://deploy.wafflehacks.cloud/api/badge?name=cert-manager&revision=true)](https://deploy.wafflehacks.cloud/applications/cert-manager)
- [Contour][] [![Status](https://deploy.wafflehacks.cloud/api/badge?name=contour&revision=true)](https://deploy.wafflehacks.cloud/applications/contour)
- [external-dns][] [![Status](https://deploy.wafflehacks.cloud/api/badge?name=external-dns&revision=true)](https://deploy.wafflehacks.cloud/applications/external-dns)
- [External Secrets Operator][]
  - Operator [![Status](https://deploy.wafflehacks.cloud/api/badge?name=external-secrets&revision=true)](https://deploy.wafflehacks.cloud/applications/external-secrets)
  - Secret Store [![Status](https://deploy.wafflehacks.cloud/api/badge?name=secret-store&revision=true)](https://deploy.wafflehacks.cloud/applications/secret-store)
- [governor][] pod reaper [![Status](https://deploy.wafflehacks.cloud/api/badge?name=governor&revision=true)](https://deploy.wafflehacks.cloud/applications/governor)
- [New Relic][] [![App Status](https://deploy.wafflehacks.cloud/api/badge?name=new-relic&revision=true)](https://deploy.wafflehacks.cloud/applications/new-relic)

Everything is automatically deployed with [ArgoCD][] using the [app of apps][] pattern.


[infrastructure/cluster]: https://github.com/WaffleHacks/infrastructure/tree/main/cluster
[ArgoCD]: https://argo-cd.readthedocs.io/en/stable/
[cert-manager]: https://cert-manager.io/
[Contour]: https://projectcontour.io/
[external-dns]: https://github.com/kubernetes-sigs/external-dns
[External Secrets Operator]: https://external-secrets.io/
[governor]: https://github.com/keikoproj/governor
[New Relic]: https://newrelic.com/
[app of apps]: https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/#app-of-apps-pattern
