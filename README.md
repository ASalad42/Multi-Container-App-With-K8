# Multi-Container App With Kubernetes

![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/b3dd74a3-959b-4052-baa3-5ac7526ee075)


![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/e0418a04-c812-4463-ad2d-7491c2e8a81a)

- Node - virtual machine or physical computer 
- Master - controls what each node does 
- Master + Node form what is called a cluster 

- Development (Minikube command line tool) 
- Production (EKS)

![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/0177cf2e-87b9-4fe0-b630-521419d99226)
![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/2ef4784b-c7ba-48f8-b2ce-a233c9c8b1d8)

config files used to create Objects 

Object types:
- pods run one or more closely related containers
- service sets up networking in a k8 cluster 
  - sub types ClusterIP, NodePort, LoadBalancer, Ingress
- ReplicaController
- StatefulSet
