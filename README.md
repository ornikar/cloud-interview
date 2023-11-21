#  Site reliability engineering Interview

Welcome to ornikar SRE (Site reliability engineering) test, your successfull integration into our team is very important for us.
So, we need to :
  - Check skills about code organization (Structure)
  - Check skills about documentation (Code, Markdown, Wiki, etc.)
  - Check skills about SCM ([Git](https://git-scm.com/))
  - Check skills about scripting ([Python](https://pypi.org/), [Go](https://golang.org/), *sh, etc.)
  - Check skills about containerization ([Docker](https://www.docker.com/))
  - Check skills about packaging ([Helm Chart](https://helm.sh/))
  - Check skills about orchestration ([Kubernetes](https://kubernetes.io/))

## Getting Started

In this repository we have two applications, one of which is in php `apps/hello`and the other in nodejs `apps/word`

#### 1. **Containerization of applications**
Create and build the application image of  `apps/hello` and `apps/world`, each Dockerfile must be:
   - [ ] Light as possible
   - [ ] Embedded security notion
   - [ ] Test with docker-compose

#### 2. **Deployment of Kubernetes and ingress controller**

 - [ ] Install [Minikube](https://github.com/kubernetes/minikube) or [Kind](https://kind.sigs.k8s.io/) with script (shell , go ,or python)
 - [ ] Deploy [Traefik](https://docs.traefik.io/getting-started/install-traefik/) as Ingress Controller with script (shell , go ,or python)

#### 3. **Package applications with helm**

 - [ ] Create the application charts of `apps/hello` and `apps/world`  
 - [ ] Add autoscalling notion

#### 4. **Deploy applications in kubernetes**

 - [ ] Deploy  `apps/hello` and `apps/world` applications in  [Minikube](https://github.com/kubernetes/minikube) or [Kind](https://kind.sigs.k8s.io/) cluster using terraform
 - [ ] Use kind or minikube terraform provider

## Final resultat

 - [ ] We must display `Hello` on <http://ornikar.dev/hello>
 - [ ] We must display `World` on <http://ornikar.dev/world>

## Test deliverables expected

 - [ ] A directory `docs/` structured with markdown file for the documentation and instructions
 - [ ] All the [Kubernetes](https://kubernetes.io/) / [Docker](https://www.docker.com/) and [HelmChart](https://helm.sh/) configuration files
 - [ ] All the scripts to automatize and reproduce deployment in [Minikube](https://github.com/kubernetes/minikube) [Kind](https://kind.sigs.k8s.io/) cluster

## Bonus 

This bonus are added to generate a discussion or to present a complete structure

 1. Check skills about a cloud provider (preference for [Google Cloud](https://cloud.google.com/) or [Amazon Web Services](https://aws.amazoncom/)) 
    
 2. Use [Argocd](https://argo-cd.readthedocs.io/en/stable/) to deploy in your cluster 

 3. Check skills about structure (VPC, Firewall, Nodes, Pools, etc.)
 
 4. Check skills about propositions for the next (Observability, Tracing, etc.)


```
Good luck! 
```
