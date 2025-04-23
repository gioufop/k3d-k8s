# K3D

## Install k3d - MacOS

```bash
brew install k3d
```

## Install k3d - Arch Linux

```bash
yay -S rancher-k3d-bin
```

## Instal k3d - Ubuntu

```bash
sudo curl -s https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
```


## Create a cluster

To create a simple k3d cluster:

```bash
k3d cluster create k3d-cluster-do-gio
```

To create a complete k3d cluster:

```bash
k3d cluster create k3d-cluster-do-gio --servers 3 --agents 3 -p "8080:30000@loadbalancer"
```

## List a cluster

To list a k3d cluster:

```bash
k3d cluster list
```

## Delete a cluster

To delete a k3d cluster:

```bash
k3d cluster delete k3d-cluster-do-gio
```
