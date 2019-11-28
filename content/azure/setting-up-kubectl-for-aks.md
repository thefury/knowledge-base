---
title: "Setting Up kubectl for AKS"
date: 2019-11-28T13:36:55-05:00
---

If you haven't already installed `kubectl`, you can do so with the following:

{{< highlight sh >}}
# if you haven't already sinatlled `kubectl` for your system...
az aks install-cli

# Connect to your cluster
az aks get-credentials--resource-group myGroup --name myAKSCluster
{{< /highlight >}}


