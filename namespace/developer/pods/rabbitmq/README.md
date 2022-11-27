## Source
[https://medium.com/nerd-for-tech/deploying-rabbitmq-on-kubernetes-using-rabbitmq-cluster-operator-ef99f7a4e417][def]


### Install the RabbitMQ operator 
```bahs
kubectl apply -f https://github.com/rabbitmq/cluster-operator/releases/latest/download/cluster-operator.yml
```

### Check if the components are healthy in the rabbitmq-system namespace
```bash
kubectl get all -o wide -n rabbitmq-system
```
[def]: https://medium.com/nerd-for-tech/deploying-rabbitmq-on-kubernetes-using-rabbitmq-cluster-operator-ef99f7a4e417