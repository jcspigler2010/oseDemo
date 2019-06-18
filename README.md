####
oc create -f f5-cluster_router-deployment.yaml
oc create -f f5-hello-world-deployment.yaml
oc create -f f5-hello-world-configmap.yaml
oc create -f f5-hello-world-service.yaml
oc create -f f5-hello-world-route.yaml
