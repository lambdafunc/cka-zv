#### View previous rollout revisions
```sh
kubectl rollout history deployment/pinelabs-deployment
```
#### Rolling Back to previous version of deployment
```sh
kubectl rollout undo deployment/pinelabs-deployment --to-revision=1
```
