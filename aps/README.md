# Helm chart sources for the alfresco process services
### Usage:
<br>helm install --debug --name=aps activiti-process-services-helm
### For helm repository
1. First is to add repository
<br> helm repo add almerico https://almerico.github.com/helmrepo/
2. then install
<br>helm install almerico/aps --name=aps
<br>

# In case if Jenkins X is used simply add 

```
  - name: aps
    repository: https://almerico.github.com/helmrepo
    version: 0.1.0
```


To the requirements.yaml 
