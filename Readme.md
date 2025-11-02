A comprehensive repository showcasing Kubernetes fundamentals and advanced deployments. Includes configurations for Pods, Deployments, Services, Ingress, ConfigMaps, Secrets, and persistent storage. Demonstrates container orchestration, scaling, and rolling updates for Node.js-based microservices

🔥🔥🔥 Terms and Definitions 🔥🔥🔥
`What is K8s ?`
`open-surce orchestration tool`

🚀 Main Components 🚀

- **Pod** — Pinakamaliit na deployable unit sa Kubernetes; naglalaman ng isa o higit pang mga container na may shared network at storage.

- **Deployment** — Kung paano nagma-manage ng desired state at rolling updates para sa pods.

- **Service** — Abstraction na nagbibigay ng stable network endpoint para sa set ng pods.

- **Ingress** — Rules para mag-route ng external HTTP/HTTPS traffic papunta sa services.

- **ConfigMap** — Para maglagay ng non-sensitive configuration data na maaring i-inject sa pods.

- **Secret** — Para sa sensitive data tulad ng passwords at API keys; naka-encode at maaaring ma-mount bilang volume o environment variables.

- **PersistentVolume (PV)** — Cluster-level storage resource.

- **PersistentVolumeClaim (PVC)** — Request para sa storage na ginagamit ng pod.

- **Kubelet** — Agent na tumatakbo sa bawat node; inuutusan ang node para mag-run ng containers ayon sa Pod spec.

- **API Server** — Gatekeeper ng cluster; lahat ng kubectl at internal components ay nag-iinteract dito.

- **Scheduler** — Nag-assign ng Pods sa mga nodes base sa resource request at constraints.

---

## 🚀 Key Components

- **Control Plane**: API Server, Controller Manager, Scheduler, etcd (state store)
- **Worker Nodes**: kubelet, kube-proxy, container runtime (e.g., containerd)
- **Networking**: Pod networking (CNI), Services, Ingress
- **Storage**: PV, PVC, StorageClass

---
