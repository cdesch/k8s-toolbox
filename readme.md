# k8s-toolbox

Useful Kubernetes tools

## helm

    https://helm.sh/docs/intro/quickstart/
    helm repo add bitnami https://charts.bitnami.com/bitnami
    helm search repo bitnami
    helm install bitnami/mysql --generate-name
    helm ls
    helm uninstall mysql-1622034033

    https://artifacthub.io/packages/helm/bitnami/nginx
    https://artifacthub.io/packages/helm/bitnami/kafka
    https://github.com/bitnami/charts/tree/master/bitnami/kafka

Helm Charts Repository <https://artifacthub.io/>

Adding Helm Charts

    helm repo add --help
    helm repo add --insecure-skip-tls-verify
    helm repo add --insecure-skip-tls-verify

## Charts

    https://github.com/raftAtGit/hl-fabric-operator
    https://github.com/hyfen-nl/PIVT

    https://github.com/kubernetes/dashboard
    https://artifacthub.io/packages/helm/k8s-dashboard/kubernetes-dashboard
