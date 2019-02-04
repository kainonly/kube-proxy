# kube-proxy

拉取 k8s.gcr.io 镜像

```shell
docker push kainonly/kube-proxy:v1.13.3
// or
docker pull ccr.ccs.tencentyun.com/kainonly/kube-proxy:v1.13.3
```

重命名镜像

```shell
docker tag kainonly/kube-proxy:v1.13.3 k8s.gcr.io/kube-proxy:v1.13.3
// or
docker tag ccr.ccs.tencentyun.com/kainonly/kube-proxy:v1.13.3 k8s.gcr.io/kube-proxy:v1.13.3
```

删除镜像

```shell
docker rmi kainonly/kube-proxy:v1.13.3
// or
docker rmi ccr.ccs.tencentyun.com/kainonly/kube-proxy:v1.13.3
```
