# k8s-elastic
Elastic on kubernetes

1. Create physical Volume using xfs.
2 run local-storage-provisioner.yaml to create pv and attach with physical storage.
3 run elastic serarch SVC
4 Run elastic Statefull Yml to create container .
5. once all server Container up and running then go ahead and deploy kibana.yml 


Note : You have to create physical volume on all node. 
