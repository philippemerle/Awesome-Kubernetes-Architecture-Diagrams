# Awesome Kubernetes Architecture Diagrams

## Kubernetes Icons Set (KIS)

* [Kubernetes Icons Set](https://github.com/kubernetes/community/tree/master/icons) provides icons to standardize Kubernetes architecture diagrams for presentation. Having uniform architecture diagrams improve understandibility.

## Drawing Tools

* **CloudSkew**: [https://www.cloudskew.com](https://www.cloudskew.com)

* **Creately**: [https://creately.com](https://creately.com)

* **Draw.io**: [https://www.drawio.com](https://www.drawio.com)

* **Holori**: [https://holori.com/kubernetes-diagram-tool/](https://holori.com/kubernetes-diagram-tool/)

* **Hyperglance**: [https://www.hyperglance.com/platforms/kubernetes/](https://www.hyperglance.com/platforms/kubernetes/)

* **Layer5**: [https://layer5.io/cloud-native-management/generate-kubernetes-architecture-diagram](https://layer5.io/cloud-native-management/generate-kubernetes-architecture-diagram)

* **Lucidchart**: [https://www.lucidchart.com](https://www.lucidchart.com)

* **Moqups**: [https://moqups.com/templates/mapping-and-diagramming/network-diagrams/kubernetes-diagram/](https://moqups.com/templates/mapping-and-diagramming/network-diagrams/kubernetes-diagram/)

* **Terrastruct**: [https://terrastruct.com](https://terrastruct.com)

* a lot of others!

## Diagrams as Code

* **Diagrams**: [https://github.com/mingrammer/diagrams](https://github.com/mingrammer/diagrams)
  * Diagram as Code for prototyping cloud system architectures
  * ![GitHub Repo stars](https://img.shields.io/github/stars/mingrammer/diagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/mingrammer/diagrams?style=flat)
  * Implementation: Python
  * Most of Kubernetes resources supported

* **Diagrams as code**: [https://github.com/dmytrostriletskyi/diagrams-as-code](https://github.com/dmytrostriletskyi/diagrams-as-code)
  * Declarative configurations using YAML for drawing cloud system architectures
  * ![GitHub Repo stars](https://img.shields.io/github/stars/dmytrostriletskyi/diagrams-as-code)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/dmytrostriletskyi/diagrams-as-code?style=flat)
  * Implementation: Python with Diagrams
  * Most of Kubernetes resources supported

* **Kubernetes-PlantUML**: [https://github.com/dcasati/kubernetes-PlantUML](https://github.com/dcasati/kubernetes-PlantUML)
  * PlantUML sprites, macros and stereotypes for creating PlantUML diagrams with the Kubernetes components
  * ![GitHub Repo stars](https://img.shields.io/github/stars/dcasati/kubernetes-PlantUML)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/dcasati/kubernetes-PlantUML?style=flat)
  * Implementation: PlantUML
  * Most of Kubernetes resources supported

* a few others!

## Generation Tools

* **k8sviz**: [https://github.com/mkimuram/k8sviz](https://github.com/mkimuram/k8sviz)
  * Generate Kubernetes architecture diagrams from the actual state in a namespace
  * ![GitHub Repo stars](https://img.shields.io/github/stars/mkimuram/k8sviz)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/mkimuram/k8sviz?style=flat)
  * Implementation: Go and Graphviz
  * Input: K8s API
  * Supported Kubernetes resources
    * Namespace
    * Service
    * PersistentVolumeClaim
    * Pod
    * StatefulSet
    * DaemonSet
    * ReplicaSet
    * Deployment
    * Job
    * CronJob
    * Ingress
    * HorizontalPodAutoscaler
  * KIS supported
  * Output formats: [all Graphviz output formats](https://graphviz.org/docs/outputs/)

* **Kubernetes diagrams**: [https://github.com/trois-six/k8s-diagrams](https://github.com/trois-six/k8s-diagrams)
  * Create diagrams from the Kubernetes API with go-diagrams
  * ![GitHub Repo stars](https://img.shields.io/github/stars/trois-six/k8s-diagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/trois-six/k8s-diagrams?style=flat)
  * Implementation: Go
  * Input: K8s API
  * Supported Kubernetes resources
    * Namespace
    * Deployment
    * ReplicaSet
    * DaemonSet
    * StatefulSet
    * Pod
    * Service
    * Ingress
  * KIS supported
  * Output formats: DOT only

* **GruCloud**: [https://github.com/grucloud/grucloud](https://github.com/grucloud/grucloud)
  * Generate code and diagrams from cloud infrastructures: AWS, Azure, GCP, Kubernetes
  * ![GitHub Repo stars](https://img.shields.io/github/stars/grucloud/grucloud)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/grucloud/grucloud?style=flat)
  * Implementation: JavaScript
  * Input: JavaScript IaC
  * Supported Kubernetes resources
    * ConfigMap
    * ClusterRole
    * ClusterRoleBinding
    * Deployment
    * Ingress
    * Namespace
    * PersistentVolume
    * PersistentVolumeClaim
    * Secret
    * Role
    * RoleBinding
    * Service
    * Service Account
    * StatefulSet
  * KIS unsupported
  * Output formats: PlantUML

* **KubeDiagrams**: [https://github.com/philippemerle/KubeDiagrams](https://github.com/philippemerle/KubeDiagrams)
  * Generate Kubernetes architecture diagrams from Kubernetes manifest files, kustomization files, Helm charts, and actual cluster state. The main originality of KubeDiagrams is its configurability allowing for instance to deal with custom Kubernetes resources.
  * ![GitHub Repo stars](https://img.shields.io/github/stars/philippemerle/KubeDiagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/philippemerle/KubeDiagrams?style=flat)
  * Implementation: Python with Diagrams
  * 45 Kubernetes resource kinds supported
  * KIS supported
  * Output formats: PNG, JPG, SVG, PDF, and DOT

* **K8s Diagram architecture generator**: [https://github.com/kocierik/k8s-to-diagram](https://github.com/kocierik/k8s-to-diagram)
  * Generate a diagram architecture from kubernetes manifests
  * ![GitHub Repo stars](https://img.shields.io/github/stars/kocierik/k8s-to-diagram)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/kocierik/k8s-to-diagram?style=flat)
  * Implementation: Go and D2
  * Input formats: K8s manifest annotations
  * Supported Kubernetes resources
    * Deployment
    * Service
    * Pod
    * ConfigMap
    * Secret
    * Ingress
    * StatefulSet
    * PersistentVolume
    * PersistentVolumeClaim
  * KIS unsupported
  * Output formats: SVG and PNG

* **react-k8s-viewer**: [https://github.com/SocialGouv/react-k8s-viewer](https://github.com/SocialGouv/react-k8s-viewer)
  * Render diagrams from your kubernetes manifests
  * ![GitHub Repo stars](https://img.shields.io/github/stars/SocialGouv/react-k8s-viewer)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/SocialGouv/react-k8s-viewer?style=flat)
  * Implementation: TypeScript
  * Input formats: K8s manifests
  * 7 Kubernetes resource kinds supported
  * KIS unsupported
  * Output formats: React Flow

* **K8s Diagram Previewer**: [https://github.com/jimmymills/k8s-diagram-previewer](https://github.com/jimmymills/k8s-diagram-previewer)
  * Diagram generator for Kubernetes manifests
  * ![GitHub Repo stars](https://img.shields.io/github/stars/jimmymills/k8s-diagram-previewer)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/jimmymills/k8s-diagram-previewer?style=flat)
  * Implementation: Python with Diagrams
  * Input formats: K8s manifests and Helm charts
  * Supported Kubernetes resources
    * Deployment
    * Service
    * Ingress
    * Pod
    * CronJob
    * Job
    * DaemonSet
    * StatefulSet
    * ConfigMap
    * Secret
    * PersistentVolumeClaim
  * KIS supported
  * Output formats: PNG, JPG, SVG, PDF, and DOT

* **k8s-diagrams**: [https://github.com/imjoseangel/k8s-diagrams](https://github.com/imjoseangel/k8s-diagrams)
  * Creates graphviz diagrams from the Kubernetes API
  * ![GitHub Repo stars](https://img.shields.io/github/stars/imjoseangel/k8s-diagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/imjoseangel/k8s-diagrams?style=flat)
  * Implementation: Python with Diagrams
  * Input formats: K8s API
  * Supported Kubernetes resources
    * Namespace
    * Deployment
    * Pod
    * ReplicaSet
    * HorizontalPodAutoscaler
    * Ingress
    * Service
    * Endpoint
  * KIS supported
  * Output formats: PNG, JPG, SVG, PDF, and DOT

* **kube-diagram**: [https://github.com/kahowell/kube-diagram](https://github.com/kahowell/kube-diagram)
  * Experimental cli tool to generate plantuml diagrams of k8s/openshift resources
  * ![GitHub Repo stars](https://img.shields.io/github/stars/kahowell/kube-diagram)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/kahowell/kube-diagram?style=flat)
  * Implementation: Java
  * Input formats: K8s manifests
  * Few Kubernetes resources supported
  * Unknown if KIS supported
  * Output formats: Unknown

* **kube-diagrams**: [https://github.com/sunny10031982/kube-diagrams](https://github.com/sunny10031982/kube-diagrams)
  * Generate Kubernetes diagrams
  * ![GitHub Repo stars](https://img.shields.io/github/stars/sunny10031982/kube-diagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/sunny10031982/kube-diagrams?style=flat)
  * Implementation: Python with Diagrams
  * Input formats: K8s API
  * Supported Kubernetes resources
    * Ingress
    * Service
    * Pod
  * KIS supported
  * Output formats: PNG

* **k8d**: [https://github.com/NickSchleicher/k8d](https://github.com/NickSchleicher/k8d)
  * Diagram Kubernetes Network Policies
  * ![GitHub Repo stars](https://img.shields.io/github/stars/NickSchleicher/k8d)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/NickSchleicher/k8d?style=flat)
  * Implementation: Go
  * Input formats: K8s API
  * Supported Kubernetes resources
    * NetworkPolicy
    * Pod
  * Unknown if KIS supported
  * Output formats: XML for draw.io

* **k8s_diagram**: [https://github.com/MrSir/k8s_diagram](https://github.com/MrSir/k8s_diagram)
  * A simple package to generate mermaid.js diagram of your Kubernetes Cluster
  * ![GitHub Repo stars](https://img.shields.io/github/stars/MrSir/k8s_diagram)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/MrSir/k8s_diagram?style=flat)
  * Implementation: Python
  * Input formats: K8s API
  * Kubernetes resources supported
    * Pod
    * Job
    * CronJob
    * StatefulSet
    * ReplicaSet
    * Deployment
    * Service
    * Namespace
  * KIS supported
  * Output formats: PNG

* **KubeDraw**: [https://github.com/B0nam/kubedraw](https://github.com/B0nam/kubedraw)
  * A Python-based tool designed to simplify the visualization of Kubernetes infrastructure
  * ![GitHub Repo stars](https://img.shields.io/github/stars/B0nam/kubedraw)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/B0nam/kubedraw?style=flat)
  * Implementation: Python with Diagrams
  * Input formats: K8s API
  * Kubernetes resources supported
    * Deployment
    * Pod
    * Ingress
    * Service
    * Namespace
  * KIS supported
  * Output formats: PNG

### Comparison Table

| Tool | K8s Kinds | Activity | GitHub Stars |
| :--------: | :-------: | :-------: | :-------: |
| **[k8sviz](https://github.com/mkimuram/k8sviz)** | **12** | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/mkimuram/k8sviz?style=flat&color=%2300FF00) |
| **[Kubernetes diagrams](https://github.com/trois-six/k8s-diagrams)** | **8** | $\color{green}{\textbf{Active}}$ |  ![GitHub Repo stars](https://img.shields.io/github/stars/trois-six/k8s-diagrams?style=flat&color=%2300FF00) |
| **[GruCloud](https://github.com/grucloud/grucloud)** | **14** | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/grucloud/grucloud?style=flat&color=%2300FF00) |
| **[KubeDiagrams](https://github.com/philippemerle/KubeDiagrams)** | $\color{green}{\textbf{45}}$ | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/philippemerle/KubeDiagrams?style=flat&color=%2300FF00) |
| **[K8s Diagram architecture generator](https://github.com/kocierik/k8s-to-diagram)** | **9** | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/kocierik/k8s-to-diagram?style=flat) |
| **[react-k8s-viewer](https://github.com/SocialGouv/react-k8s-viewer)** | **7** | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/SocialGouv/react-k8s-viewer?style=flat) |
| **[K8s Diagram Previewer](https://github.com/jimmymills/k8s-diagram-previewer)** | **11** | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/jimmymills/k8s-diagram-previewer?style=flat) |
| **[k8s-diagrams](https://github.com/imjoseangel/k8s-diagrams)** | **8** | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/imjoseangel/k8s-diagrams?style=flat&color=%23FF0000) |
| **[kube-diagram](https://github.com/kahowell/kube-diagram)** | **5** | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/kahowell/kube-diagram?style=flat&color=%23FF0000) |
| **[kube-diagrams](https://github.com/sunny10031982/kube-diagrams)** | $\color{red}{\textbf{3}}$ | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/sunny10031982/kube-diagrams?style=flat&color=%23FF0000) |
| **[k8d](https://github.com/NickSchleicher/k8d)** | $\color{red}{\textbf{2}}$ | $\color{red}{\textbf{Inactive}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/NickSchleicher/k8d?style=flat&color=%23FF0000) |
| **[k8s_diagram](https://github.com/MrSir/k8s_diagram)** | **8** | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/MrSir/k8s_diagram?style=flat&color=%23FF0000) |
| **[KubeDraw](https://github.com/B0nam/kubedraw)** | **5** | $\color{green}{\textbf{Active}}$ | ![GitHub Repo stars](https://img.shields.io/github/stars/B0nam/kubedraw?style=flat&color=%23FF0000) |


## Various Other Resources

* **k8s-diagrams**: [https://github.com/cloudogu/k8s-diagrams](https://github.com/cloudogu/k8s-diagrams)
  * A collection of diagrams explaining Kubernetes
  * ![GitHub Repo stars](https://img.shields.io/github/stars/cloudogu/k8s-diagrams)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/cloudogu/k8s-diagrams?style=flat)

* **Hari Sekhon - Diagrams-as-Code**: [https://github.com/HariSekhon/Diagrams-as-Code](https://github.com/HariSekhon/Diagrams-as-Code)
  * Cloud & DevOps Architecture Diagrams-as-Code in Python and D2 languages
  * ![GitHub Repo stars](https://img.shields.io/github/stars/HariSekhon/Diagrams-as-Code)
  * ![GitHub last commit](https://img.shields.io/github/last-commit/HariSekhon/Diagrams-as-Code?style=flat)
  * Implementation: D2 and Python with Diagrams
  * Most of Kubernetes resources supported

* **Drawing your Kubernetes cluster the right way**: [https://archive.fosdem.org/2023/schedule/event/container_kubernetes_cluster_right_way/attachments/slides/5304/export/events/attachments/container_kubernetes_cluster_right_way/slides/5304/kda_FOSDEM_2023_k8s.pdf](https://archive.fosdem.org/2023/schedule/event/container_kubernetes_cluster_right_way/attachments/slides/5304/export/events/attachments/container_kubernetes_cluster_right_way/slides/5304/kda_FOSDEM_2023_k8s.pdf)

* Talk [Visualizing Kubernetes with Generated Diagrams](https://www.youtube.com/watch?v=GEeodHEOmvA) at Southern California Linux Expo
