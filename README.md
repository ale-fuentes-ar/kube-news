# kube-news : with Kubernete
![](https://img.shields.io/badge/by-Alejandro.Fuentes-informational?style=flat&logoColor=white&color=cdcdcd)

> NOTE: this project use [kubectl][link-kubectl] and [k3d][link-k3d] <br/>
> Need [docker][link-docker] desktope install and running

### Steps

1. clone poject
```
git clone https://github.com/ale-fuentes-ar/kube-news.git
```
2.  
```bash
# create clusterwith k3d
k3d cluster create mycluster --servers 3 --agents 3

# get k8s folder
cd k8s

# execute deployment
kubectl appply -f deployment

```

<!-- link and tools -->
[link-k3d]: https://k3d.io/v5.4.4/
[link-kubectl]: https://kubernetes.io/docs/tasks/tools/
[link-docker]: https://www.docker.com/
