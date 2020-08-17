# kubectl

kubectl create deployment --image=u1ih/hello hello1

kubectl expose deployment hello1 --port=80 --name=hello1-http

kubectl get services

kubectl autoscale deployment hello1 --min=2 --max=10

kubectl delete pods abc123


