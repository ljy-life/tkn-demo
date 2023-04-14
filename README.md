# tkn-demo
tekton + argoCD DevOps Demo

相关链接： 

https://tekton.dev/vault/pipelines-v0.44.x-lts/

https://github.com/tektoncd/pipeline

https://hub.tekton.dev/

[https://github.com/argoproj/argo-cd/releases](https://github.com/argoproj/argo-cd/releases)

https://killercoda.com/

## 版本说明
```shell
kubernetes version: v1.25.0
Client version: 0.30.0
Pipeline version: v0.44.2
Triggers version: v0.23.0
Dashboard version: v0.34.0
argoCD version: v2.5.16
```

**注意**： 在 `tekton pipeline 0.46.0` 版本之后， tekton 官方移除了对 `pipelineresource` 的支持，所以本次使用的是 `tekton 0.44.2` 版本。
https://github.com/tektoncd/pipeline/blob/main/docs/pipelineresources.md



从 0 快速部署一套 tekton  + argoCD 的 DevOps CICD 流水线，自动触发

通过和实际环境参考，为 https 的 gitlab 和 harbor 环境，http 的场景较为简单，如果有需要，请自行修改

需要提供 Gitlab 、 harbor 地址

![](images/Pasted%20image%2020230412210440.png)

![](images/Pasted%20image%2020230412210500.png)

![](images/Pasted%20image%2020230412210718.png)