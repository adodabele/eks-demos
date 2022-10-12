# eks-demos
Readme file to be updated

eksctl create cluster --name ananth-ekscluster --nodegroup-name ng-default --node-type t3.micro --nodes 2
eksctl delete cluster --region=us-east-1 --name=ananth-ekscluster

You can just download the previous version binary and replace the one you have now.

Linux:
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.5.2/bin/linux/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl

macOS:
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.5.2/bin/darwin/amd64/kubectl
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.2.2/bin/darwin/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl


Windows:
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.5.2/bin/windows/amd64/kubectl.exe
And add it to PATH.

If not follow instructions for other Operating Systems here: https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-binary-via-curl