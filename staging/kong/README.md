### Deploy Kong and Konga using Helm

## Install Kong
```
$ helm install kong ${Workspace}/infrastructure/staging/kong/kong -f ${Workspace}/infrastructure/staging/kong/values.yaml -n kong
```

###Install Konga
```
$helm install konga ${Workspace}/infrastructure/staging/kong/konga -f ${Workspace}/infrastructure/staging/kong/konga/values.yaml -n kong
```

##Upgrade Kong 
```
$ helm upgrade kong ${Workspace}/infrastructure/staging/kong/kong -f ${Workspace}/infrastructure/staging/kong/values.yaml -n kong
```

##Upgrade Kong 
```
$ helm upgrade konga ${Workspace}/infrastructure/staging/kong/konga -f ${Workspace}/infrastructure/staging/kong/konga/values.yaml -n kong
```