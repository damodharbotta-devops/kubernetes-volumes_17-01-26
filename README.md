# kubernetes-volumes

## commands:

kubectl create -f deployment.yml
kubectl get deploy
kubectl get po
kubectl exec -it podname -c cont1 -- bash
kubectl exec -it podname -c cont2 -- bash

cd /opt/cont1/
cd /opt/cont2/


kubectl create -f pv.yml
kubectl get pv
kubectl delete deploy flm

kubectl create -f pvc-1.yml
kubectl get pvc
