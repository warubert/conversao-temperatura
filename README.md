# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Revisando conceitos kubernetes

```bash
#!/bin/bash
k3d cluster create meucluster --servers 1 --agents 2

kubectl apply -f ./k8s/deployment.yaml 

kubectl get all

k3d cluster delete --all
```


