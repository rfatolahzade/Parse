Run these commands on your machine:
``bash
helm repo add <alias> https://<orgname>.github.io/helm-charts
helm repo add Parse https://rfinland.github.io/Parse
helm repo list
helm search repo Parse
helm install mongo-parse parse/helm-parse
helm delete mongo-parse
```
Here you go.
