Este repositório é uma aplicação exemplo que demonstra a orquestração de contêineres usando Kubernetes, 
com foco na integração de ferramentas modernas de GitOps para gerenciar infraestrutura e aplicações.

A aplicação é construída com FastAPI e implantada em um cluster Kubernetes local criado com Kind (Kubernetes IN Docker). 
O gerenciamento da entrega contínua é feito via ArgoCD, que utiliza o Git como fonte única de verdade para a infraestrutura e as aplicações.
