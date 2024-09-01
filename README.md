> ## :GitOps and Kubernetes - Cloud Native Engineer - Essentials:
> ### **{ Linux, Docker, Kubernetes, YAML, JSON, Git, ArgoCd }**

**Learn from experienced and certified professionals.**
**Hands-On, Real world scenario based, Practical training**
**Contact us :**

    Email:  ninitltd@ninit.tech, ninitltd@gmail.com
    Contact: +44 07904500068

### Aim:
> This course is designed for those individuals and/or groups who are interested in learning modern ways to build and deploy containersied workloads. Following the best industrial work practices, **GitOps** offers a step forward in *_Infrastructure Automation_* and most importantly for *_software application build and delivery_*. **_Kuberbenetes adoption is on rise AND it is now a de-facto standard for business to build and deliver cloud-native applications_**. You will learn Docker, Kubernetes and the GitOps tookit in this course through instructor-led sessions.  **_Our training is >80% hands on (Practical) as we truly believe that learning by doing is the best way to learn and master new skills._**

> As cloud native application developments are growing rapidly, the industrial demand for skilled individuals is also growing.  Participants will gain insight about container orchestration with confidence to work with modern container orchestration systems like **Kubernetes**. This course is hugely focused on latest GitOps practices and will deep dive into modern tools such as Argo-CD to prepare real world application deployment patterns. This course is for anyone who is interested in improving their employment chances for starting a new career as well as securing a highly paid job with a long term stable career.

The delegate will acquire essential knowledge which will help them to become a good :

* Cloud Native support Engineer.
* Kubernetes support Engineer.
* Kubernetes Administrator.                    
* Build and Release specialist.
* Entry to mid level SRE/DevOps/GitOps Engineer.

### Prerequisites :
### At least one of the following.

* **Desire** to learn and master new skills.
* Problem solving **Attitude**.
* Good **Team Player**.
* **Interested** in exploring new career opportunities.
* **Open minded**.

 **_Note: Every delegate will need their own laptop or desktop computer with descent internet connectivity._**

#### Setting up your device (Member's of our team will help you to setup your Workstation OR Laptop)

>## Fundamentals on data serialisation and basic application concepts.

  - YAML
    * Structure of `yaml` document.
    * Prepare sample `yaml` document.
    * Query different elements with `yq` utility.
  - JSON
    * Structure of `json` document.
    * Prepare sample `json` document.
    * Query different elements with `jq` utility.
  - What is API?
    * Take example of public API e.g `github` or `gitlab`
    * Familieries with `curl` and `wget` utility.

>## Docker
* Virtual machines vs Containers.
* What is an IP Address and how applications and devices communicate.
* Why Docker Containerization ?
* What is a container ?
* Get familier with dockerCli.
* Learn basic Docker operations.
* Learn about 
    * docker `run` , `exec` , `rm` and other important commands.
* Understanding docker image concept.
  - Learn about Docker-Hub (A free docker image repository)
  - Understanding image tags.
  - Pull a basic ​busybox​ and ​alpine​ image from dockerhub. 
      * ​docker `pull`
  - List all images available local on your system. 
      * docker `images`
  - Inspect a docker image to gain insight of the image. 
      * ​docker image `inspect`
  - Familierise with basic **LINUX utilities** through a container.
* Practice **LINUX common commands** on a **ubuntu** container.
* Understand different **Dockerfile** commands.
* Build container from default images.
* Create docker image from running container.
* Write _DockerFile_ to build container image from scratch.
* Build a custom web server image using _nginx webserver_.
    * docker _build_
* Docker Compose to run multiple containers.

>## Linux and BASH scripting :
  * Get more insight about **Linux filesystem** in a container.
  * What is BASH scripting?
  * Why BASH scripts are very useful ?
  * Prepare sample BASH scripts. 
  * What is cronJob ? Create and test sample cronJob.

>## SCM or VCS ( Theory + Practical ):
>#### Source control management / Version Control System
* What is SCM/VCS and why it is important ?
* Download / Install `Git` or `Gitbash` (for windows) .
* Configure local git preferences.
* Getting familiar with command line options/help.
* Create a FREE GitHub account.
* Private vs Public repository.
* Create a new project repository on GitHub.
* Cloning repository.
* Commit new changes and raise new pull request.
* Peer review pending pull requests and approvals.
* Push new changes to Github.
* Advance concepts of branches and tags.
* Learn about `GitHub Actions` and `workflows` configurations.
* Prepare your first pipeline to `build` and `publish` custom `container image`.

>## Kubernetes `K8S`
  * What is `Kubernetes` ?
  * Why `kubernetes` adoption is on rise ?
  * `Docker` vs `Kubernetes` - comparision.
  * High level Architectural diagram of Kubernetes and core components.
  * What is `kubernetes` API ?
  * Setup `kubernetes`.
  * Install `kubectl` - A command line management utility.
  * Query `k8s` api with kubectl and get familier with basics.
  * Kubernetes resources :
    >### Namespaces
      * Whats ia a `NAMESPACE`? Understand importance of `NS`
      * When to use different namespaces ?
      * Switch between namespaces permenantly vs temperory options.
      * Create a new namespace (Imperative way)
      * Understand `Imperative` vs `Declarative` approach to create resources.
      * Create a new namespace (Declarative way)
    >### Pods
      * What is a `POD` ?
      * Understand difference between `POD` vs `Container`
        * Create a `POD` with one of the `nginx image` we prepared earlier(Imperative).
        * Create a `POD` (Declaratice).
      * Understanding pod lifecycle.
      * Pod logs.
      * Pod Internals:
    >### Labels and Selectors
      * Importance of Labels and selectors ?
      * Syntax and character set.
      * List, Watch and filter kubernetes resources.
    >### Service
      * What is a service ?
      * Service types in `k8s` :
        - ClusterIP (Default)
        - NodePort
        - LoadBalancer
        - Externalname
      * Setup a default service for the `POD` created in previous step.
      * Query services with `kubectl` to verify details.
      * Query the service endpoint from `web browser` or `cURL` to confirm its working as expected.
      * Setup a `NodePort` serivce for the same pod and check again.
    >### ConfigMap
      * What is a configMap ?
      * Create config map from literals.
      * Create config map from files.
      * Configure pod to setup configuration / parameters from configMap.
      * Configure pod to setup environment variables from configMap.
      * Configure pod to setup configuration from volume.
    >### Secrets
      * What is a secret ?
      * Overview of secrets. understand base64 encoding / decoding.
      * Create a secret.
      * Retrieve a secret.
      * Configure a pod to retrieve credentials/parameters from a secret.
    >### Deployments
      * What is a deployment ?
      * Deployment manifest (template).
      * Prepare a custom deployment using imperative command and different options.
      * Create a deployment.
      * Update a deployment.
      * Practice Deploy commands:
        - `rollout`, `scale`, `autoscale`
      * Check history and status of deployment.
      * Recreate deployment. (rolling update vs recreate)
      * Pausing and Resuming deployment.
    >### Replicasets
      * What is a replicaset ?
      * When to use Replicaset ?
      * Scaling a replicaset.
    >### Volumes
      * Type of volumes.
      * Persistent Volumes.
      * Persistent Volume Claim.
      * Storage classes.
    >### Ingress
      * What is ingress.
      * Create a new ingress resource.
      * Ingress rules.
      * Default backend rules.
      * Ingress class and scopes.
      * Prepare a deployment and setup ingress resource.

>## Helm Package manager.
  * What is a package maanager ?
  * Why `helm` for `kubernetes`s package management ?
  * Setup helm locally on your system.
  * helm repositories :
    - add, remove, list repositories.
  * Prepare a helm chart to deploy `nginx` web server.
    - helm create `chart_name` [flags]
  * Gain better insight about helm :
    - Charts
    - Releases
    - Revisions
    - Template
    - Values.yaml
  * Deploy your first helm release.
  * Query deployed helm release and validate.
    - get
    - list
    - status
  * Make ammendment to helm release and upgrade existing helm release.

>## GitOps with Argo CD:
* Introduction to `GitOps` ?
* What is `ArgoCD` ?
* Example without ArgoCD and with ArgoCD
* Defining single source of truth.
* Setting up Argocd with helm chart on our test k8s cluster.
* Integrate with GitHub Repo.
* ArgoCD Application vs Applicationset.
* Manage multiple kubernetes clusters with ArgoCD.
* Prepare a DEMO setup for container image build.
* Prepare a DEMO for application deployment. 

## Project Work ##
> * Define the required scope of project.
> * Go through backlog grooming and spring planning.
> * Prepare sprints and assign work to team.
> * Explain concept of pairing with colleague.

---
### ** Based on participants' requirements, advanced topics will be covered.
### Quizzes, home work and more hands on lab work will be available during the course to get particepants ready for interviews.

### ** Required information and basic knowledge will be provided depends on delegate’s requirement.

----
#### About Instructor :
##### Nilesh Barot :

___________Nilesh is an open-source enthusiast with over 2+ decades of experience. He is pationate about learning and adopting new ways of designing and building solutions. In recent years he has successfully delivered projects by adopting and following Continuous Integration and Delivery processes.________

Professional Qualifications: https://www.credly.com/users/nilesh-barot/badges

Linked in profile : https://uk.linkedin.com/in/nileshbarot 
#kubernetes #k8s #cncf #golang #GNU/Linux #Linux

### Duration of the course : 3 - 4 Months + Project duration.
### Schedule :
	* Every Saturday OR Sunday : 09:30 am - 11:00 am
	* Additional support sessions will be conducted as and when needed.
	* Contact us :

	    Email:  ninitltd@ninit.tech, ninitltd@gmail.com

	    Contact: +44 07904500068
