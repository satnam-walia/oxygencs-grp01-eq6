WINDOWS

$env:KUBECONFIG = "C:\Users\fredg\OneDrive\Bureau\ETS\LOG680\oxygencs-grp01-eq6\kubernetes\kubeconfig.yaml"

kubectl get pods (optional)

kubectl get deployments (optional)

kubectl config view --minify | findstr namespace (optional)

kubectl config set-context --current --namespace=grp01eq6-namespace

kubectl apply -f kubernetes/configmap.yaml

kubectl apply -f kubernetes/secret.yaml

kubectl apply -f kubernetes/hvac-deployment.yaml

kubectl apply -f kubernetes/service.yaml

kubectl apply -f kubernetes/ingress.yaml

