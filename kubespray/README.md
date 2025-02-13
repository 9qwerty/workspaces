### หลังจากลง Kubespray

- Copy kubeconfig to user path

```bash
sudo mkdir -p $HOME/.kube
sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
sudo chown $(id -u):$(id -g) $HOME/.kube/config
```

- Get node status

```bash
kubectl get nodes
```
