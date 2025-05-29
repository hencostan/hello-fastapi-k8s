Este repositório é uma aplicação exemplo que demonstra a orquestração de contêineres usando Kubernetes, 
com foco na integração de ferramentas modernas de GitOps para gerenciar infraestrutura e aplicações.

A aplicação é construída com FastAPI e implantada em um cluster Kubernetes local criado com Kind (Kubernetes IN Docker). 
O gerenciamento da entrega contínua é feito via ArgoCD, que utiliza o Git como fonte única de verdade para a infraestrutura e as aplicações.

Nota: Não foi possível conectar o argo pois dava esse erro:
"Unable to create application: application spec for hello-fastapi-k8s is invalid: InvalidSpecError: repository not accessible: repositories not accessible: &Repository{Repo: "https://github.com/hencostan/hello-fastapi-k8s", Type: "", Name: "", Project: ""}: repo client error while testing repository: rpc error: code = Unknown desc = error testing repository connectivity: unable to ls-remote HEAD on repository: failed to list refs: Get "https://github.com/hencostan/hello-fastapi-k8s/info/refs?service=git-upload-pack": tls: failed to verify certificate: x509: certificate is valid for *.araquari.ifc.edu.br, araquari.ifc.edu.br, not github.com"

Todos os arquivos foram inseridos porém não foi possível realizar os testes.
