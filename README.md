# k8s
Using these configuration files, you can deploy your own Multi Container Application.
First of all, you need to setup a kubernetes cluster. There are several ways to do this like single node setup using minikube or cluster setup using kubeadm on local VM or on Cloud.
For single node setup, download minikube installer file for windows from here https://github.com/kubernetes/minikube/releases/latest/download/minikube-installer.exe
For Linux and MacOS Users follow the steps from here https://kubernetes.io/docs/tasks/tools/install-minikube/

## After then
Clone this repository to create multi container app. And run command
# kubectl apply -f .
This will creates all the services and depployments. Then you can run your app inside browser on 192.168.43.100 (This might be different in your case...you can check it by using command ***  #minikube ip  *** )
