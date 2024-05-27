1. Install Script

curl -sfL https://get.k3s.io | sh -

Note: K3s will restart auto even if sever reboots. 
      1.2: kubeconfig file location: /etc/rancher/k3s/k3s.yaml
2. 
A kubeconfig file will be written to /etc/rancher/k3s/k3s.yaml and the kubectl installed by K3s will automatically use it

3. Add Worker Node. 
To install additional agent nodes and add them to the cluster, run the installation script with the K3S_URL and K3S_TOKEN environment variables. 

curl -sfL https://get.k3s.io | K3S_URL=https://myserver:6443 K3S_TOKEN=mynodetoken sh -

Note: The value to use for K3S_TOKEN is stored at /var/lib/rancher/k3s/server/node-token on your server node.

If you are getting an error ! 

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/7aa8d057-3f9c-412c-beda-19264f609877)

Use below command then try again. 

export KUBECONFIG=/etc/rancher/k3s/k3s.yaml

