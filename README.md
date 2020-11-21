# kubernetes-workshop

## Deployment on kubernetes cluster
`kubectl create deployment hello-world-rest-api --image=adanlessossi/hello-world-rest-api:0.0.1.RELEASE`

## Exposing the deployment
`kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080`

## Scale the deployment
`kubectl scale deployment hello-world-rest-api --replicas=3`
