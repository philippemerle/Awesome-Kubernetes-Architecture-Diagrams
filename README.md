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
  * Git stars: 40.3k
  * Last commit: Feb 11, 2025
  * Implementation: Python
  * Most of Kubernetes resources supported

* **Diagrams as code**: [https://github.com/dmytrostriletskyi/diagrams-as-code](https://github.com/dmytrostriletskyi/diagrams-as-code)
  * Declarative configurations using YAML for drawing cloud system architectures
  * Git stars: 338
  * Last commit: Sep 12, 2023
  * Implementation: Python with Diagrams
  * Most of Kubernetes resources supported

* **Kubernetes-PlantUML**: [https://github.com/dcasati/kubernetes-PlantUML](https://github.com/dcasati/kubernetes-PlantUML)
  * PlantUML sprites, macros and stereotypes for creating PlantUML diagrams with the Kubernetes components
  * Git stars: 254
  * Last commit: Mar 11, 2021
  * Implementation: PlantUML
  * Most of Kubernetes resources supported

* a few others!

## Generation Tools

* **k8sviz**: [https://github.com/mkimuram/k8sviz](https://github.com/mkimuram/k8sviz)
  * Generate Kubernetes architecture diagrams from the actual state in a namespace
  * GitHub stars: 298
  * Last commit: Jun 6, 2022
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
  * GitHub stars: 141
  * Last commit: Feb 15, 2024
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
  * GitHub stars: 115
  * Last commit: Sep 10, 2024
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
  * GitHub stars: 100
  * Last commit:  Feb 13, 2025
  * Implementation: Python with Diagrams
  * 42 Kubernetes resource kinds supported
  * KIS supported
  * Output formats: PNG, JPG, SVG, PDF, and DOT

* **K8s Diagram architecture generator**: [https://github.com/kocierik/k8s-to-diagram](https://github.com/kocierik/k8s-to-diagram)
  * Generate a diagram architecture from kubernetes manifests
  * GitHub stars: 18
  * Last commit: Sep 1, 2024
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
  * GitHub stars: 13
  * Last commit: Nov 12, 2024
  * Implementation: TypeScript
  * Input formats: K8s manifests
  * 7 Kubernetes resource kinds supported
  * KIS unsupported
  * Output formats: React Flow

* **K8s Diagram Previewer**: [https://github.com/jimmymills/k8s-diagram-previewer](https://github.com/jimmymills/k8s-diagram-previewer)
  * Diagram generator for Kubernetes manifests
  * GitHub stars: 8
  * Last commit: Jul 20, 2021
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
  * GitHub stars: 2
  * Last commit: Oct 31, 2021
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
  * GitHub stars: 1
  * Last commit: Jan 14, 2022
  * Implementation: Java
  * Input formats: K8s manifests
  * Few Kubernetes resources supported
  * Unknown if KIS supported
  * Output formats: Unknown

* **kube-diagrams**: [https://github.com/sunny10031982/kube-diagrams](https://github.com/sunny10031982/kube-diagrams)
  * Generate Kubernetes diagrams
  * GitHub stars: 1
  * Last commit: Apr 3, 2020
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
  * GitHub stars: 1
  * Last commit: Jan 21, 2020
  * Implementation: Go
  * Input formats: K8s API
  * Supported Kubernetes resources
    * NetworkPolicy
    * Pod
  * Unknown if KIS supported
  * Output formats: XML for draw.io

* **k8s_diagram**: [https://github.com/MrSir/k8s_diagram](https://github.com/MrSir/k8s_diagram)
  * A simple package to generate mermaid.js diagram of your Kubernetes Cluster
  * GitHub stars: 0
  * Last commit: May 9, 2024
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
  * GitHub stars: 0
  * Last commit: May 20, 2024
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
| **[k8sviz](https://github.com/mkimuram/k8sviz)** | **12** | $\color{red}{\textbf{Inactive}}$ | $\color{green}{\textbf{298}}$ |
| **[Kubernetes diagrams](https://github.com/trois-six/k8s-diagrams)** | **8** | $\color{green}{\textbf{Active}}$ | $\color{green}{\textbf{141}}$ |
| **[GruCloud](https://github.com/grucloud/grucloud)** | **14** | $\color{green}{\textbf{Active}}$ | $\color{green}{\textbf{115}}$ |
| **[KubeDiagrams](https://github.com/philippemerle/KubeDiagrams)** | $\color{green}{\textbf{42}}$ | $\color{green}{\textbf{Active}}$ | $\color{green}{\textbf{100}}$ |
| **[K8s Diagram architecture generator](https://github.com/kocierik/k8s-to-diagram)** | **9** | $\color{green}{\textbf{Active}}$ | **18** |
| **[react-k8s-viewer](https://github.com/SocialGouv/react-k8s-viewer)** | **7** | $\color{green}{\textbf{Active}}$ | **13** |
| **[K8s Diagram Previewer](https://github.com/jimmymills/k8s-diagram-previewer)** | **11** | $\color{red}{\textbf{Inactive}}$ | **8** |
| **[k8s-diagrams](https://github.com/imjoseangel/k8s-diagrams)** | **8** | $\color{red}{\textbf{Inactive}}$ | $\color{red}{\textbf{2}}$ |
| **[kube-diagram](https://github.com/kahowell/kube-diagram)** | **5** | $\color{red}{\textbf{Inactive}}$ | $\color{red}{\textbf{1}}$ |
| **[kube-diagrams](https://github.com/sunny10031982/kube-diagrams)** | $\color{red}{\textbf{3}}$ | $\color{red}{\textbf{Inactive}}$ | $\color{red}{\textbf{1}}$ |
| **[k8d](https://github.com/NickSchleicher/k8d)** | $\color{red}{\textbf{2}}$ | $\color{red}{\textbf{Inactive}}$ | $\color{red}{\textbf{1}}$ |
| **[k8s_diagram](https://github.com/MrSir/k8s_diagram)** | **8** | $\color{green}{\textbf{Active}}$ | $\color{red}{\textbf{0}}$ |
| **[KubeDraw](https://github.com/B0nam/kubedraw)** | **5** | $\color{green}{\textbf{Active}}$ | $\color{red}{\textbf{0}}$ |


## Various Other Resources

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

* Talk [https://www.youtube.com/watch?v=GEeodHEOmvA](Visualizing Kubernetes with Generated Diagrams) at Southern California Linux Expo
