# k8s 架构图
![架构图](https://raw.githubusercontent.com/xiaoxianglun/k8studay/main/image.png)

## k8s主要组件
- kubelet：
- kubeproxy：
- api-server：k8s的api服务，对外开放api接口，可以通过http调用，kubectl也是通过调用api接口实现的集群操作。
- controller-manager：控制器管理器，控制各种controller。
- scheduler：
- etcd：etcd内存储集群的各种基本信息。
- cloud-cm：云端控制器管理器。
