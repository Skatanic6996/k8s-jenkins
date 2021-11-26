# jenkins
 k8s-jenkins
Replace all "exapmle" values

ServiceAccount -> Volume -> Deployment -> Service -> Ingress -> Default Jenkins Settings

kubectl exec -it <jenkins_pod_name> -n example cat /var/jenkins_home/secrets/initialAdminPassword -n devops-tools


or 

kubectl get pods -n example

kubectl logs <jenkins_pod_name> -n example