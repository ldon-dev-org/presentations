---?image=assets/img/jx-artwork/jx-robocat.png&position=-28% 15%&size=55% 100%

@snap[text-right]
## Introducion 
## a @css[jx-header]( Jenkins X)
### una guia para todos
@snapend

---
@title[Te llevamos en un Tour de Jenkins X Boat Tour]

@snap[center]
## Vamos a Explorar Jenkins X!!
@snapend

@snap[center]
![height=500px,title=Jenkins is NOT Jenkins X](assets/img/jx-artwork/jx-boat-tours.png)
@snapend

---
@title[Que es Jenkins X?]
@transition[fade]

@snap[west]
# Que es Jenkins X?
@snapend

@snap[east fragment]
![height=500px,title=Jenkins is NOT Jenkins X](assets/img/jx-artwork/jenkins.png)
@snapend

@snap[east fragment]
@fa[ban fa-10x text-red]
@snapend

---
@snap[east fragment]
@quote[Jenkins X  no es mejor o peor que Jenkins y no es una nueva version o es mejor que Jenkins. Es un producto completamente different](Viktor Farcic - Principal Software Delivery Strategist @CloudBees)
@snapend

---
@title[Que es Jenkins X? - proque no es Jenkins]
@transition[fade]
---?image=assets/img/jx-artwork/jx-robocat.png&position=-28% 15%&size=55% 100%

@snap[east span-60]
@ol[list-spaced-bullets list-boxed-bullets text-gold text-08]
1. Completamente code nuevo          @fa[code-branch fa-3x text-yellow]
2. Nada se a reusado de Jenkins     @fab[creative-commons-zero fa-2x text-yellow]
3. Es nativo a Kubernetes                 @fa[dharmachakra fa-3x text-yellow]
4. Architectura Differente           @fa[vihara fa-3x text-yellow]
@olend
@snapend


---
@title[Que es Jenkins X? - proque no es Jenkins]
@transition[fade]
@snap[east fragment]
![half,height=500px,title=Jenkins is NOT Jenkins X](assets/img/jx-artwork/jenkins-v-jenkinsx.png)
@snapend


@snap[west text-smallcaps font-lato-thin span-55]
@css[]

El concepto de pipas y su extensibilidad es lo que tienen en comun.

@css[text-bold text-gold text-15](Eso es todo!)
@snapend


---
@title[Jenkins X - Kubernetes Native CI/CD]
---?image=assets/img/jx-artwork/jx-captain.png&position=-15% 15%&size=55% 100%

@snap[east span-69]
 @css[jx-header text-uppercase text-20 text-shadow](Jenkins) @css[jx-header text-uppercase text-bold text-20 text-shadow](X)  
## es una plataforma @css[text-bold](opinada)

@css[font-lato-light](Nativo a Kubernetes @fa[dharmachakra text-yellow])

##  CI/CD platform
@css[text-10 thin-text](Compuesta de muchos otros projectos de open-source)
@snapend

---
@title[What is Jenkins X? - Multi Cloud]
---?image=assets/img/jx-artwork/jx-tour-poster.png&position=2% 45%&size=25%

@snap[center-north text-right]
##  Usala en EKS y GKE
@snapend

@snap[west-center fragment]
![height=280px,title=AWS,position=5px](https://www.sinefa.com/wp-content/uploads/2019/03/AWS-Logo-White.png)
@snapend

@snap[center-right fragment]
![width=200,title=GCP](https://seeklogo.com/images/G/google-cloud-logo-6B950E8ADB-seeklogo.com.png)
@snapend


---

@title[What is Jenkins X? - Tekton es el motor para Pipas]
---?image=assets/img/jx-artwork/jx-tekton-engine.png&position=-28% 15%&size=55% 100%

@snap[east]
## Tekton es el @fa[heartbeat fa-3x pulsingheart] 
## del system de 
## ejecución de Pipas
@snapend


@title[What is Jenkins X? - Pipelines]
---?image=assets/img/jx-artwork/jx-tekton-engine.png&position=-28% 15%&size=55% 100%

@snap[east span-78]
@ol[list-spaced-bullets list-boxed-bullets text-gold text-08]
1. Pipas son declarativas (YAML)             @fa[code fa-3x text-yellow]
2. Etapas corren en su propio pod        @fa[box fa-3x text-yellow]
3. Nativo a Kubernetes                             @fa[dharmachakra fa-3x text-yellow]
@olend
@snapend

@title[What is Jenkins X? - Diagram]
---?image=assets/img/jx-artwork/jx-tekton-engine.png&position=-28% 15%&size=55% 100%

@snap[east span-80]
#### Jenkins X Te Abstrae de la complejidad Tekton 
![IMAGE](assets/img/jx-pipeline-to-tekton.png)
@snapend

@title[Jenkins X - Preview Environments]
---?image=assets/img/jx-artwork/jx-xoltar.png&position=left 45%&size=40%

@snap[east span-70]
##  Vista Previa te da un vislumbre al futuro!

#### Tus colegas ven tu trabajo antes de desplegarlo. Tu te aseguras que to code funciona

@css[text-06 thin-text text-italic]([ Namespaced Ingress, Pod running your latest app version ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/ns.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/ing.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - Preview Environments]
---?image=assets/img/jx-artwork/jx-robocat.png&position=left 45%&size=40%

@snap[east span-70]
##  ChatOps

#### Jenkins X Bot automatically comments on your Commits, Issues and Pull Requests

@css[text-06 thin-text text-italic]([ Use your Git Provider built-in UI ] )

@snap[west-south text-blue]
@fa[git-square fa-3x] @fa[github-square fa-3x]
@snapend

@snapend


@title[Jenkins X - QuickStarts]
---?image=assets/img/jx-artwork/jx-robocat.png&position=left 45%&size=40%

@snap[east span-70]
##  QuickStarts

#### Kick the tires without writing a single line of code.

@css[text-06 thin-text text-italic]([ Namespaced Ingress, Pod running sampled app ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/ns.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/ing.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - DevPods]
---?image=assets/img/jx-artwork/jx-devpods.png&position=left 45%&size=40%

@snap[east span-70]
##  DevPods

#### develop in the cloud via a kubernetes devpod.

@css[text-06 thin-text text-italic]([   Ingress, Pod with your project files synched, modify live ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/ns.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/ing.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - Build Packs]
---?image=assets/img/jx-artwork/jx-robocat.png&position=left 45%&size=40%

@snap[east span-70]
##  Build Packs

#### pipeline templates based on the language your app runs.

@css[text-06 thin-text text-italic]([ Namespaced Ingress, Pod running your latest app version ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/ns.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/ing.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - Serverless Deployments]
---?image=assets/img/jx-artwork/jx-serverless.png&position=left 45%&size=40%

@snap[east span-70]
##  Serverless Deployments

#### Knative spin up/down based on traffic demand.

@css[text-06 thin-text text-italic]([ Namespaced Ingress, Pods running your latest app version ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/ns.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/ing.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - Canary Deployments]
---?image=assets/img/jx-artwork/jx-robocat.png&position=left 45%&size=40%

@snap[east span-70]
##  Canary Deployments with Istio & Flagger

#### Install Istio and Flagger at cluster level, then configure via YAML

@css[text-06 thin-text text-italic]([ View metrics via Grafana/Prometheus ] )

@snap[west-south]
![height=100px](assets/img/k8s-icons/resources/labeled/crd.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/svc.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/deploy.svg)
![height=100px](assets/img/k8s-icons/resources/labeled/pod.svg)
@snapend

@snapend

@title[Jenkins X - GitOps]
---?image=assets/img/jx-artwork/jx-gitops.png&position=left 45%&size=40%

@snap[east span-70]
##  GitOps

#### git as single source of truth for everything.
@css[text-06 text-gold]( jx uses gitops to manage its own config)

@css[text-06 thin-text text-italic]([ git repositories hold all configuration ] )

@snap[west-south text-blue]
@fa[git-square fa-3x] @fa[github-square fa-3x]
@snapend

@snapend

---

@title[Questions]
@snap[north span-100]
## @css[text-yellow](Got Questions   @fa[question])
@snapend
# Q&A
@emoji[tada]