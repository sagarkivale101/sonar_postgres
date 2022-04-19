kubectl create -f secrets.yml
kubectl create -f postgres-pv.yml
kubectl create -f postgres-deployment.yml
kubectl create -f postgres-service.yml
kubectl create -f sonar-pvc.yml
kubectl create -f sonar-deployment.yml
kubectl create -f sonar-service.yml
