# Kubernetes-vs-Docker-Swarm
Difference between kubernetes and docker swarm

Containers have become quite popular in recent years. They help developers maintain consistency across various platforms, right from development to the production process. Although there are multiple significant in the market when it comes to container orchestration, including Mesosphere and Amazon ECS, this blog aims to take a comparative look at two of the popular ones - Kubernetes vs Docker Swarm.
# What is Kubernetes?
Kubernetes has been developed by Google and it was introduced in the year 2014. In essence, it is an IT management tool that has been specifically designed to simplify the scalability of workloads using containers. It has the ability to automate deployment, scaling, and operating application containers.
By using Kubernetes, you will be able to define how your applications should run and the manner in which they interact with other applications. Empowering the user with interfaces and composable platform primitives, Kubernetes allows high degrees of flexibility and reliability.
# What is Docker Swarm?
Docker Swarm has been a popular open source standard for packaging and distributing containerized applications. In essence, it is native clustering for Docker. A pool of Docker hosts can be turned into a single virtual host.

# Kubernetes
 
Kubernetes Setup is very complicated, but once installed cluster is robust
For Kubernetes, GUI is the Kubemetes Dashboard
Kubernetes is Highly scalable and scales fast
Kubemetes can do auto-scaling
In Kubernetes, manual intervention needed for load balancing traffic between different containers and pods
Kubernetes can deploy rolling updates and does automatic rollbacks
Kubernetes Can share storage volumes only with the other container  the same pod
Kubernetes has In-built tools for logging and monitoring
Kubernetes can do auto-scaling.
In Kubernetes, manual intervention needed for load balancing traffic between different containers and pods.
Kubernetes can deploy rolling updates and does automatic rollbacks.
Kubernetes Can share storage volumes only with the other containers in the same pod.
Kubernetes has In-built tools for logging and monitoring.

# Docker Swarm
 
Docker Swarm's Installation is very simple, but the cluster is not robust
In Docker Swarm, there is no GUI
Docker Swarm is highly scalable and scales 5xfaster than Kubernetes
Docker swarm cannot do auto-scaling
Docker swarm does auto load balancing of traffic between containers in the cluster
Docker Swarm can deploy rolling updates, but not automatic rollback
Docker Swarm can share storage volumes with any other container
Docker Swarm uses 3rd party tools like ELK stack should be used for logging and monitoring
Docker swarm cannot do auto-scaling
Docker swarm does auto load balancing of traffic between containers in the cluster
Docker Swarm can deploy rolling updates, but not automatic rollback
Docker Swarm can share storage volumes with any other container
Docker Swarm uses 3rd party tools like ELK stack should be used for logging and monitoring

