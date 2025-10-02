# kubernetes
Learning kubernetes
---

- How ingress works: Access web app on local machine using minikube
    1. Run ingress on minikube: https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/
    2. Start Minikube normally (`minikube start --addons=ingress`)
    3. Always run:
        
        ```bash
        minikube ip
        ```
        
        It will return the current IP
        
    4. Add that IP into `/etc/hosts` for all your ingress hosts.