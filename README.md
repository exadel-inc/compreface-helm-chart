# Helm Chart
This tutorial shows how to deploy CompreFace using Helm. To use helm you need to install it first, see the instructions [here](https://helm.sh/docs/intro/install/)

In order to use compreface helm chart you need to configure your own Helm client.

```commandline
$ helm repo add compreface  https://exadel-inc.github.io/compreface-helm-chart/
“compreface” has been added to your repositories
```

You can check compreface chart version by command:
```commandline
helm search repo compreface

NAME                                    CHART VERSION   APP VERSION     DESCRIPTION                              
compreface/compreface-kubernetes        0.1.0           1.16.0          A Helm chart of compreface for Kubernetes

```
