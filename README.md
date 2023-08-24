# imersao-devops-cloud-02

### Comando para criar o cluster com k3d e executar a aplicação:
```k3d cluster create meucluster -p "30000:30000@loadbalancer"```

```k3d cluster create meucluster -p "3000:30000@loadbalancer" -p "3001:30001@loadbalancer" -p 9021:30002@loadbalancer"```

### Aplica deployment recursivo:
```kubectl apply -f . -R``` 

### Acessar a app:
http://localhost:3001/wallet1
http://localhost:3001/wallet2


