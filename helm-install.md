wget https://get.helm.sh/helm-v3.9.3-linux-amd64.tar.gz

tar xvf helm-v3.9.3-linux-amd64.tar.gz

sudo mv linux-amd64/helm /usr/local/bin

rm helm-v3.4.1-linux-amd64.tar.gz

rm -rf linux-amd64

helm version

FROM SCRIPTS

curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3

chmod 700 get_helm.sh

 ./get_helm.sh
