
# Demo-Ressourcen Java Aktuell - Artikel "Kubernetes Basics – wie kommt die App in die Cloud"

Benutzung über 
```bash
kubectl apply -f <filename>
```
die deployment-resourcen bauen aufeinander auf

die app-sourcen in der passenden Version findet man unter [cy4n/hello](https://github.com/cy4n/hello/tree/hello-0.0.4-jug)


zur Demo und zum Üben empfiehlt sich Minikube oder docker-for-desktop
(und für das ingress-Beispiel ein "dns"-Eintrag in der /etc/hosts, die verwendete url auf die entsprechende IP von Minikube mapped)

## basis - pod ohne weitere sinnvolle Verwendung :-)
* pod.yml

## basis - deployment mit Aussenanbindung
* deployment.yml
* service.yml
* ingress.yml

## Erweiterung 1 - readiness und liveness checks
* deployment-health.yml

## Erweiterung 2 - configmap und volume mit application.yml für springboot app
* config.yml
* deployment-volume.yml

