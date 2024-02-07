# KubernetesNotes

## get pods & logs
microk8s kubectl get pods -n tf
microk8s kubectl logs .. -n tf

# get inferenceservice
microk8s kubectl get inferenceservice -n tf
microk8s kubectl describe inferenceservice tf-model -n tf


# get svc
microk8s kubectl get svc istio-ingressgateway -n istio-system

