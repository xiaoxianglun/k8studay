# k8s 架构图
![架构图](https://raw.githubusercontent.com/xiaoxianglun/k8studay/main/image.png)

## k8s主要组件
- kubelet：k8s的守护进程
- kubeproxy：k8s的节点代理，网络通讯通过这个代理进行
- api-server：k8s的api服务，对外开放api接口，可以通过http调用，kubectl也是通过调用api接口实现的集群操作。
- controller-manager：控制器管理器，控制各种controller。
- scheduler：k8s集群的调度器
- etcd：etcd内存储集群的各种基本信息。
- cloud-cm：云端控制器管理器。
