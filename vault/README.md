#### # This is an example of how to deploy the vault operator
##### # 
```
oc create -f https://raw.githubusercontent.com/coreos/vault-operator/master/example/etcd_crds.yaml
```
##### # 
```
oc create -f https://raw.githubusercontent.com/coreos/vault-operator/master/example/etcd-operator-deploy.yaml -n default
```
##### #
```
oc create -f https://raw.githubusercontent.com/coreos/vault-operator/master/example/vault_crd.yaml
```
##### # 
```
oc create -f https://raw.githubusercontent.com/coreos/vault-operator/master/example/deployment.yml
```