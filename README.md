# eks-confluent-operator


## FIX ERROR:
The CustomResourceDefinition "kafkas.platform.confluent.io" is invalid:
metadata.annotations: Too long: must have at most 262144 bytes make: ***
[install-crds] Error 1 we should use
https://docs.confluent.io/operator/current/co-troubleshooting.html 

kubectl apply --server-side=true -f crds/platform.confluent.io_kafkas.yaml