# baeldung-helm-demo

This repo was built to learn about Helm, Kubernetes, Docker, Springboot, and Python from the guide over at https://www.baeldung.com/ops/kubernetes-helm.

This is a helm chart repo to deploy a containerized hello world application in Kubernets via Helm charts.

Install instructions.

1. helm repo add chart-repo https://hogwater.github.io/baeldung-helm-demo/gh-pages
2. helm install hello-world chart-repo/hello-world

Note: The application isn't accessible since it's not exposed to the public. Work in progress.
