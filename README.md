# Install Kubernetes With Kind

Install Go
```
wget https://golang.org/dl/go1.16.darwin-amd64.pkg
```

Install Docker
```

```


Install Kind
```
brew install kind
# or
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.10.0/kind-darwin-amd64
mv kind /usr/local/bin/
chmod +x /usr/local/bin/kind
```


Create the cluster
```
kind create cluster
kubectl cluster-info --context kind-kind

kind get kubeconfig

kind delete cluster

unset KUBECONFIG
```








