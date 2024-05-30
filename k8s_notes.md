In Kubernetes, controllers are control loops that watch the state of your cluster, then make or request changes where needed. Each controller tries to move the current cluster state closer to the desired state.


Controller pattern A controller tracks at least one Kubernetes resource type. These objects have a spec field that represents the desired state. The controller(s) for that resource are responsible for making the current state come closer to that desired state.



![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/08000036-436e-4d11-8a21-d579f168b8d1)


![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/4db31811-fa24-4def-a111-67cda0afc2a3)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/3bc4c332-3544-4261-a77a-1d1f6ebce4ae)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/5230f160-bbe6-437a-9ba2-e55cef5eb909)


![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/4c93731d-2b6e-49ec-bb38-eb15b7d2259c)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/74301333-b1f5-492a-b326-ccb1d24733fe)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/7d9a9453-f036-4b01-b174-90732983b1fd)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/37143349-9ca6-4ec4-8927-85a0760cd51f)

![image](https://github.com/ayushbikku91/DevSecOps_Notes/assets/54761726/3bc3a815-e08f-4855-ade8-c8742f0314f9)

kubectl config --kubeconfig=/root/my-kube-config use-context research
