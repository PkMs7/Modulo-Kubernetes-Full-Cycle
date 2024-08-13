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