# Multi-Container App With Kubernetes

![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/b3dd74a3-959b-4052-baa3-5ac7526ee075)


![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/e0418a04-c812-4463-ad2d-7491c2e8a81a)

- Node - virtual machine or physical computer 
- Master - controls what each node does 
- Master + Node form what is called a cluster 

- Development 
- Production (EKS)


config files used to create Objects 

Object types:
- pods run one or more closely related containers
- service sets up networking in a k8 cluster 
  - sub types ClusterIP, NodePort, LoadBalancer, Ingress
- ReplicaController
- StatefulSet

Linking it all

![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/2cdcad92-5ae0-45f0-bdcd-861e4b7bf8eb)
![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/9011f46d-02c9-4d1f-8859-f68c57917500)

key value pair component:web links service & pod in this example but they can be anything

Ports

![image](https://github.com/ASalad42/Multi-Container-App-With-K8/assets/104793540/6a453ed1-fa18-489a-91c9-04c1b1bd08b3)

tagetport (send incoming traffic to) = containerport (inside the pod)
nodeport gets exposed to the outside world i.e ip:port in browser
