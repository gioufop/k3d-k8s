# K3D

## Install k3d MacOS

## Create a cluster
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
```# k3d-k8s
