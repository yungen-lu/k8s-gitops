## k8s-gitops

### 簡介

使用 [Flux](https://github.com/fluxcd/flux2) 管理 kubernetes 上的部署，[Flux](https://github.com/fluxcd/flux2) 會監控這個 Git repo 然後根據 [cluster](./cluster/) 裡面的變動更動 kubernetes cluster 的部署。