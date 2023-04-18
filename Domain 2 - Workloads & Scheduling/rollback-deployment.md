
#### Rollback to previous Revision
```sh
kubectl rollout undo deployment/pinelabs-deployment --to-revision=1

kubectl get rs

kubectl describe deployment pinelabs-deployment

kubectl rollout history deployment/pinelabs-deployment
```