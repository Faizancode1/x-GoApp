1. Containerizing an application writing an docker file.
2. writing an deployment.yaml , service.yaml, ingress.yaml
3. create an kubernetees eks cluster - pre requisites:- kubectl, eksctl, aws configure.
4. eksctl create cluster --name nameofcluster --region us-east-1
5. kubectl apply -f k8s/manifests/deployment.yaml
6. kubectl apply -f k8s/manifests/service.yaml
7. kubectl apply -f k8s/manifests/ingress.yaml
8. create helm charts
9. CI -> using github actions
10. write an ci.yaml file
11. install argo cd on kubernetees cluster and once you do that run the pipeline.

12. Reference for this project repository:- https://github.com/iam-veeramalla/go-web-app-devops/tree/main 
