# K8s Microservices with ELK Stack

This is a part of my course on [Udemy](https://www.udemy.com/course/kubernetes-microservices). This project was deployed on EKS (Amazon Elastic Kubernetes Service)

## Microservices Structure

![alt text](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/b0edd05c-0fd8-43e1-82b3-87fdd410b384)
Because data of the Position Tracker needs to saved to keep track like this.
![image](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/52e595eb-2e79-43cf-bdc4-6956c8b7f031)
 I'll implement  a microservice use mongoDB to save the data.
![db](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/92e90725-f0dc-45c3-a920-edc0a5f4174f)
## Website GUI
![app](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/dd69cf85-8de4-4b5c-9293-f38bcdbe1512)
## ELK Stack
We'll use ELK Stack to take logs from the pod running in all nodes. ELK Stack Stucture:
![ELKStack](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/be53678f-4baa-4232-bc3e-8b60b9b3e52c)
I'll implement it in this project like this:
![elk2](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/f8f1a4f7-701f-43cc-b061-73859f913ee9)
In case of the Queue failure:
![queuefail](https://github.com/huynguyendev02/k8s-microservices/assets/109943707/23038581-9c22-460c-9585-6e9c14e411a7)


## References
- Udemy Course: https://www.udemy.com/course/kubernetes-microservices
- Docker Container: https://hub.docker.com/r/richardchesterwood/
