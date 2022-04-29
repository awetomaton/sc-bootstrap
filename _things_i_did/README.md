1. Moved argo images to harbor, set image repo url in argo-cd
2. `helm create namespace argo-cd`
3. tried to set up global values structure but it's tricky, putting off for now.
4. argo-cd - set storageclass to 'aws-efs' (retrieve from `kubectl get storeageclass`)
5. helm install of redis does not clean up persistentvolumeclaims, need to be deleted manually
6. install worked. going to tear it down an configure it to have it be self-managed.
