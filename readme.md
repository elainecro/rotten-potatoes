1) Criar Dockerfile
2) docker build -t elainecro/rotten-potatoes:v1 .
3) docker images
4) docker login
5) docker push elainecro/rotten-potatoes:v1
6) docker tag elainecro/rotten-potatoes:v1 elainecro/rotten-potatoes:latest
7) docker push elainecro/rotten-potatoes:latest
8) criar pasta k8s
9) criar cluster - kind create cluster --name clusterpotatoe --config cluster.yaml
10) criar deployment.yaml - kubectl apply -f deployment.yaml
11) kubectl get all