#### Generic Commands:
```sh
systemctl status kubelet
cd /etc/systemd/system/kubelet.service.d
```

#### pinelabs-pod.yaml
```sh
apiVersion: v1
kind: Pod
metadata:
  name: pinelabs-pod
spec:
  containers:
  - name: pinelabs-container
    image: nginx
```    
