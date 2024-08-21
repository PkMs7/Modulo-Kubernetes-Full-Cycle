# Kubernetes

## Kubernetes Cheat Sheets

- https://cheatsheets.zip/kubernetes

## Kind

- Documentação: https://kind.sigs.k8s.io/

## Kubectl

- Documentação: https://kubernetes.io/docs/tasks/tools/

## Comandos mais utilizados

- *Instalação do kubectl e kind através da documentação*

- *Criando um cluster*

```kind create cluster```

- *Conexão com o cluster com kubectl*

```kubectl cluster-info --context <nome do cluster>```

- *Buscar os nodes dos clusters*

```kubectl get nodes```

- *Buscar clulsters criados*

```kind get clusters```

- *Apagar um clulster*

```kind delete clusters <nome do cluster>```

- *Criar um cluster a partir do arquivo .yaml*

```kind create cluster --config=k8s/kind.yaml --name=fullcycle```

- *Adicionar um pod em um node*

```kubectl apply -f k8s/pod.yaml```

- *Verificar pods criados*

```kubectl get pods```

- *Descrever um pod*

```kubectl describe pod <nome do pod>```

- *Deletar um pod em um node*

```kubectl delete pod <nome do pod>```

- *Redirecionar portas do kubernetes e da máquina*

```kubectl port-forward pod/<nome do pod> <porta:porta>```

- *Criar um ReplicaSet*

```kubectl apply -f k8s/replicaset.yaml```

