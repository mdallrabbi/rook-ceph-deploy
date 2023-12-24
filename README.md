### clone the repo and deploy rook ceph

```
git clone https://github.com/mdallrabbi/rook-ceph-deploy.git
cd rook-ceph-deploy
kubectl create -f .
kubectl create -f /csi/cephfs/.
kubectl create -f /csi/rbd/.
kubectl create -f /csi/rgw/.
```

