On Your jenkins server perform below commands

git clone https://github.com/anilbidari/kube.git

cp kube/config /var/lib/jenkins/.kube/config

sudo chown jenkins:jenkins /var/lib/jenkins/.kube/config

sudo su - jenkins

kubectl get nodes
