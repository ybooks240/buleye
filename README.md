# buleye


## init project 

```
mkdir buleye && cd buleye
go mod init  buleye.com/m

kubebuilder init --domain ybooks240.github.com --license apache2 --owner "james.liu"

kubebuilder create api --group buleye --version v2 --kind DeployK8s
```
