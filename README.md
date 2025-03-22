principais comandos 
docker build -t fernando8312/fake-shop-desafio:v1 kubectl apply -f k8s/deployment.yaml kubectl get all

PUBLICANDO: docker container ls docker push fernando8312/fake-shop-desafio:v1

kubectl rollout history deployment fakeshop kubectl rollout undo deployment fakeshop && watch ‘kubectl get po’

DELETANDO POD E RECRIANDO
kubectl get pod 

kubectl delete pod/fakeshop-bf5c75c95-p4p4n

PARA VER A DISTRIBUIÇÃO NOS PODS
kubectl get pod -o wide
