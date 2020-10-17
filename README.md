# 🐙 k8s-course

This Repo includes all files from [this](https://www.udemy.com/course/kubernetes-microservices/) course on Udemy

## Commands

Get all running pods

```bash
kubectl get all
```

Apply a configuration

```bash
kubectl apply -f <file.yml>
```

Get all information about a specific Pod

```bash
kubectl describe pod <pod-name>
```

Execute a command inside a container

```bash
kubectl exec <pod-name> -- <command>
```

get into the container via shell

```bash
 kubectl exec -it <pod-name> -- sh
```

Get only the pods with there lable and a filter for selector (eg release=0)

```bash
kubectl get po --show-labels -l <selector>
```
