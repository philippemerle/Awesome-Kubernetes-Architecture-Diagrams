# Awesome Kubernetes Architecture Diagrams

## Drawing Tools

* **CloudSkew**: [https://www.cloudskew.com](https://www.cloudskew.com)

* **Creately**: [https://creately.com](https://creately.com)

* **Holori**: [https://holori.com/kubernetes-diagram-tool/](https://holori.com/kubernetes-diagram-tool/)

* **Hyperglance**: [https://www.hyperglance.com/platforms/kubernetes/](https://www.hyperglance.com/platforms/kubernetes/)

* **Layer5**: [https://layer5.io/cloud-native-management/generate-kubernetes-architecture-diagram](https://layer5.io/cloud-native-management/generate-kubernetes-architecture-diagram)

* **Moqups**: [https://moqups.com/templates/mapping-and-diagramming/network-diagrams/kubernetes-diagram/](https://moqups.com/templates/mapping-and-diagramming/network-diagrams/kubernetes-diagram/)

* **Terrastruct**: [https://terrastruct.com](https://terrastruct.com)

## Generation Tools

* **k8sviz**: [https://github.com/mkimuram/k8sviz](https://github.com/mkimuram/k8sviz)
  * Generate Kubernetes architecture diagrams from the actual state in a namespace
  * Git stars: 292
  * Last commit: Jun 6, 2022
  * Implementation: Go and Graphviz
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

* **Kubernetes diagrams**: [https://github.com/trois-six/k8s-diagrams](https://github.com/trois-six/k8s-diagrams)
  * Create diagrams from the Kubernetes API with go-diagrams
  * Git stars: 141
  * Last commit: Feb 15, 2024
  * Implementation: Go
  * Supported Kubernetes resources
    * Namespace
    * Deployment
    * ReplicaSet
    * DaemonSet
    * StatefulSet
    * Pod
    * Service
    * Ingress

* **GruCloud**: [https://github.com/grucloud/grucloud](https://github.com/grucloud/grucloud)
  * Generate code and diagrams from cloud infrastructures: AWS, Azure, GCP, Kubernetes
  * Git stars: 115
  * Last commit: Sep 10, 2024
  * Implementation: JavaScript
  * Most of Kubernetes resources supported

* **K8s Diagram architecture generator**: [https://github.com/kocierik/k8s-to-diagram](https://github.com/kocierik/k8s-to-diagram)
  * Generate a diagram architecture from kubernetes manifests
  * Git stars: 16
  * Last commit: Sep 1, 2024
  * Implementation: Go and D2
  * Most of Kubernetes resources supported

* **react-k8s-viewer**: [https://github.com/SocialGouv/react-k8s-viewer](https://github.com/SocialGouv/react-k8s-viewer)
  * Render diagrams from your kubernetes manifests
  * Git stars: 13
  * Last commit: Nov 12, 2024
  * Implementation: TypeScript
  * Most of Kubernetes resources supported

* **K8s Diagram Previewer**: [https://github.com/jimmymills/k8s-diagram-previewer](https://github.com/jimmymills/k8s-diagram-previewer)
  * Diagram generator for Kubernetes manifests
  * Git stars: 8
  * Last commit: Jul 20, 2021
  * Implementation: Python with Diagrams
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

* **k8s-diagrams**: [https://github.com/imjoseangel/k8s-diagrams](https://github.com/imjoseangel/k8s-diagrams)
  * Creates graphviz diagrams from the Kubernetes API
  * Git stars: 2
  * Last commit: Oct 31, 2021
  * Implementation: Python with Diagrams
  * Supported Kubernetes resources
    * Namespace
    * Deployment
    * Pod
    * ReplicaSet
    * HorizontalPodAutoscaler
    * Ingress
    * Service
    * Endpoint

* **KubeDiagrams**: [https://github.com/philippemerle/KubeDiagrams](https://github.com/philippemerle/KubeDiagrams)
  * Generate Kubernetes architecture diagrams from Kubernetes manifest files. The main originality of KubeDiagrams is its configurability allowing for instance to deal with custom Kubernetes resources.
  * Git stars: 1
  * Last commit: Dec 27, 2024
  * Implementation: Python with Diagrams
  * Most of Kubernetes resources supported

* **kube-diagram**: [https://github.com/kahowell/kube-diagram](https://github.com/kahowell/kube-diagram)
  * Experimental cli tool to generate plantuml diagrams of k8s/openshift resources
  * Git stars: 1
  * Last commit: Jan 14, 2022
  * Implementation: Java
  * Few Kubernetes resources supported

* **kube-diagrams**: [https://github.com/sunny10031982/kube-diagrams](https://github.com/sunny10031982/kube-diagrams)
  * Generate Kubernetes diagrams
  * Git stars: 1
  * Last commit: Apr 3, 2020
  * Implementation: Python with Diagrams
  * Supported Kubernetes resources
    * Ingress
    * Service
    * Pod

* **k8d**: [https://github.com/NickSchleicher/k8d](https://github.com/NickSchleicher/k8d)
  * Diagram Kubernetes Network Policies
  * Git stars: 1
  * Last commit: Jan 21, 2020
  * Implementation: Go
  * Supported Kubernetes resources
    * NetworkPolicy
    * Pod

* **k8s_diagram**: [https://github.com/MrSir/k8s_diagram](https://github.com/MrSir/k8s_diagram)
  * A simple package to generate mermaid.js diagram of your Kubernetes Cluster
  * Git stars: 0
  * Last commit: May 9, 2024
  * Implementation: Python
  * Kubernetes resources supported
    * Pod
    * Job
    * CronJob
    * StatefulSet
    * ReplicaSet
    * Deployment
    * Service
    * Namespace

* **KubeDraw**: [https://github.com/B0nam/kubedraw](https://github.com/B0nam/kubedraw)
  * A Python-based tool designed to simplify the visualization of Kubernetes infrastructure
  * Git stars: 0
  * Last commit: May 20, 2024
  * Implementation: Python with Diagrams
  * Kubernetes resources supported
    * Deployment
    * Pod
    * Ingress
    * Service
    * Namespace

### Comparison Table

<style>
r { color: Red }
o { color: Orange }
g { color: Green }
</style>

| Tool | #Kinds | Activity | #Stars |
| :--------: | :-------: | :-------: | :-------: |
| **[k8sviz](https://github.com/mkimuram/k8sviz)** | **12** | **<r>Inactive</r>** | **<g>292</g>** |
| **[Kubernetes diagrams](https://github.com/trois-six/k8s-diagrams)** | **8** | **<g>Active</g>** | **<g>141</g>** |
| **[GruCloud](https://github.com/grucloud/grucloud)** | *Unknown* | **<g>Active</g>** | **<g>115</g>** |
| **[K8s Diagram architecture generator](https://github.com/kocierik/k8s-to-diagram)** | *Unknown* | **<g>Active</g>** | **16** |
| **[react-k8s-viewer](https://github.com/SocialGouv/react-k8s-viewer)** | *Unknown* | **<g>Active</g>** | **13** |
| **[K8s Diagram Previewer](https://github.com/jimmymills/k8s-diagram-previewer)** | **11** | **<r>Inactive</r>** | **8** |
| **[k8s-diagrams](https://github.com/imjoseangel/k8s-diagrams)** | **8** | **<r>Inactive</r>** | **<r>2</r>** |
| **[KubeDiagrams](https://github.com/philippemerle/KubeDiagrams)** | **<g>25</g>** | **<g>Active</g>** | **<r>1</r>** |
| **[kube-diagram](https://github.com/kahowell/kube-diagram)** | *Unknown* | **<r>Inactive</r>** | **<r>1</r>** |
| **[kube-diagrams](https://github.com/sunny10031982/kube-diagrams)** | **<r>3</r>** | **<r>Inactive</r>** | **<r>1</r>** |
| **[k8d](https://github.com/NickSchleicher/k8d)** | **<r>2</r>** | **<r>Inactive</r>** | **<r>1</r>** |
| **[k8s_diagram](https://github.com/MrSir/k8s_diagram)** | **8** | **<g>Active</g>** | **<r>0</r>** |
| **[KubeDraw](https://github.com/B0nam/kubedraw)** | **5** | **<g>Active</g>** | **<r>0</r>** |

## Diagrams as Code

* **Diagrams**: [https://github.com/mingrammer/diagrams](https://github.com/mingrammer/diagrams)
  * Diagram as Code for prototyping cloud system architectures
  * Git stars: 40k
  * Last commit: Dec 26, 2024
  * Implementation: Python
  * Most of Kubernetes resources supported

* **Diagrams as code**: [https://github.com/dmytrostriletskyi/diagrams-as-code](https://github.com/dmytrostriletskyi/diagrams-as-code)
  * Declarative configurations using YAML for drawing cloud system architectures
  * Git stars: 333
  * Last commit: Sep 12, 2023
  * Implementation: Python with Diagrams
  * Most of Kubernetes resources supported

* **Kubernetes-PlantUML**: [https://github.com/dcasati/kubernetes-PlantUML](https://github.com/dcasati/kubernetes-PlantUML)
  * PlantUML sprites, macros and stereotypes for creating PlantUML diagrams with the Kubernetes components
  * Git stars: 250
  * Last commit: Mar 11, 2021
  * Implementation: PlantUML
  * Most of Kubernetes resources supported

## Various Resources

* **Kubernetes Icons Set**: [https://github.com/kubernetes/community/tree/master/icons](https://github.com/kubernetes/community/tree/master/icons)
  * These icons are a way to standardize Kubernetes architecture diagrams for presentation

* **k8s-diagrams**: [https://github.com/cloudogu/k8s-diagrams](https://github.com/cloudogu/k8s-diagrams)
  * A collection of diagrams explaining Kubernetes
  * Git stars: 327
  * Last commit: Mar 25, 2024

* **Hari Sekhon - Diagrams-as-Code**: [https://github.com/HariSekhon/Diagrams-as-Code](https://github.com/HariSekhon/Diagrams-as-Code)
  * Cloud & DevOps Architecture Diagrams-as-Code in Python and D2 languages
  * Git stars: 176
  * Last commit: Nov 11, 2024
  * Implementation: D2 and Python with Diagrams
  * Most of Kubernetes resources supported

* **Drawing your Kubernetes cluster the right way**: [https://archive.fosdem.org/2023/schedule/event/container_kubernetes_cluster_right_way/attachments/slides/5304/export/events/attachments/container_kubernetes_cluster_right_way/slides/5304/kda_FOSDEM_2023_k8s.pdf](https://archive.fosdem.org/2023/schedule/event/container_kubernetes_cluster_right_way/attachments/slides/5304/export/events/attachments/container_kubernetes_cluster_right_way/slides/5304/kda_FOSDEM_2023_k8s.pdf)