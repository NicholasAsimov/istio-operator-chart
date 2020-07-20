## istio-operator-chart

Published istio-operator chart from [https://github.com/istio/istio](https://github.com/istio/istio/tree/master/manifests/charts/istio-operator) for easier Terraform provisioning.

### Publishing a new version
```sh
> cd istio/manifests/charts/istio-operator
> git checkout 1.6.5
> helm package .
> mv istio-operator-1.6.0.tgz ~/code/istio-operator-chart/
> helm repo index ~/code/istio-operator-chart --url https://nicholasasimov.github.io/istio-operator-chart
```
