  ```
  
  34  kubectl get pods -n kube-system -o wide
   35  ls
   36  kubectl cluster-info
   37  kubectl version 
   38  kubectl api-versions
   39  kubectl api-resources
   40  history 
   41  ls
   42  kubectl cluster-info
   43  kubectl version 
   44  kubectl api-versions
   45  kubectl api-resources
   46  ls
   47  kubectl proxy --port=8080 & 
   48  curl http://localhost
   49  curl http://localhost:8080
   50  curl http://localhost:8080/api
   51  curl http://localhost:8080/apis
   52  curl http://localhost:8080/api/v1
   53  curl http://localhost:8080/api/v1/pods
   54  curl http://localhost:8080/api/v1/pods > hello.txt
   55  cat hello.txt 
   56  grep -A50 k8s-hello  hello.txt 
   57  kubectl get pods 
   58  grep -A50 hello-k8s  hello.txt 
   59  kubectl get pods 
   60  kubectl describe pod hello-k8s
   61  kubectl config get-cluster
   62  kubectl config get-clusters
   63  kubectl config get-clusters kubernetes
   64  kubectl config view
   65  ls
   66  cat .kube/config 
   67  history 
   68  ls
   69  cd K8s-docker-ericsson-2020-Dec-07/
   70  ls
   71  cd 02-Kubernetes/
   72  ls
   73  mkdir 03-Kube-Api
   74  cd 03-Kube-Api/
   75  history > README.md
```
