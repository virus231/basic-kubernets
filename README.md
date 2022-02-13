# **Basic Kubernets**

## **A First Deployment - Using the Imperative Approach**
    1. docker build -t kube-app .
    2. minikube status
    3. Create hub
    4.  docker tag kube-app virus2310/kube-app
    5.  docker push virus2310/kube-app
    6. kubectl create deployment first-app --image=virus2310/kube-app
    7. kubectl get deployments
    8. kubectl get pods
    9. minikube dashboard
