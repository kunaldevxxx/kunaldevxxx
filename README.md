# Kunal Khare

**Infrastructure & Distributed Systems Engineer**  
OpenStack • Kubernetes/GKE • Temporal • Networking • React + Three.js

---

## 01 // About

I like understanding *how things actually work* under the hood — from OpenStack Cinder’s I/O path and Neutron’s data plane, to Temporal’s event-sourced workflow engine and Kubernetes node economics.

I mostly work across:

- **Cloud infrastructure** – OpenStack, Kubernetes/GKE, load balancing, DNS, storage
- **Control-plane orchestration** – long-running workflows, migrations, durable execution
- **Developer experience** – CI/CD, ephemeral environments, good debugging stories
- **Frontend for infra** – React, Framer Motion, Three.js for expressive, data‑heavy UIs

If it involves packets, queues, or event logs, I’m interested.

---

## 02 // What I’m Working On

- **Infra storytelling through deep‑dive blogs**  
  Turning hard‑won operational knowledge into long, diagram‑heavy posts.
- **Cloud-native control planes**  
  Temporal, Kubernetes, and OpenStack working together in real production failure modes.
- **High‑signal personal tooling**  
  Small scripts and dashboards that make debugging clusters and workflows less painful.

---

## 03 // Selected Writing

Long‑form posts from my portfolio (highly technical, implementation‑focused):

- **Inside OpenStack Cinder + Glance: The Real Boot‑from‑Volume Pipeline**  
  From `openstack server create --boot-from-volume` to libvirt domain XML, tracing every step across Nova, Cinder, Glance, and storage drivers.  
  `https://kunal-khare-sre.netlify.app/blog/openstack-cinder-glance-boot-from-volume-pipeline`

- **Why We Chose Temporal Over Argo Workflows and Airflow for Control‑Plane Orchestration**  
  A practical comparison based on long‑running infra workflows, not marketing checklists.  
  `https://kunal-khare-sre.netlify.app/blog/temporal-vs-argo-airflow-control-plane-orchestration`

- **Why We Moved from App Engine to GKE: A Kubernetes Architecture Deep Dive**  
  Requests/limits, node pools, CUDs, HPAs, Helm, and ephemeral PR environments.  
  `https://kunal-khare-sre.netlify.app/blog/app-engine-to-gke-kubernetes-architecture`

- **Inside OpenStack Networking: How Neutron, Octavia, and Designate Actually Work Together**  
  ML2/OVN pipeline, amphora load balancers, and DNS-as-a-Service integration.  
  `https://kunal-khare-sre.netlify.app/blog/openstack-networking-neutron-octavia-designate`

---

## 04 // Stack

**Core infrastructure**

- OpenStack (Nova, Cinder, Glance, Neutron, Octavia, Designate)
- Kubernetes / GKE, Helm, Horizontal Pod Autoscaler
- Temporal (durable workflows), Postgres, Redis
- Linux networking, iptables/OVN, DNS (PowerDNS/BIND), NGINX/HAProxy

**Application & frontend**

- React 18, Vite, React Router
- Tailwind CSS, Framer Motion
- Three.js, React Three Fiber, @react-three/drei
- React Markdown, remark-gfm

**Tooling & CI/CD**

- GitHub Actions, ephemeral PR environments
- Docker, container image pipelines
- ESLint, TypeScript typings for React, PostCSS

---

## 05 // Projects & Experiments

- **Personal Portfolio** – Built with React + Vite + Tailwind + Framer Motion + Three.js  
  A single‑page experience with 3D visuals, animated sections, and a blog powered by markdown‑like content.

- **Infra Deep Dives** – This repo / blog content  
  Opinionated, long‑form docs for:
  - OpenStack internals (storage, networking, LBaaS, DNS)
  - Kubernetes resource economics and autoscaling
  - Temporal workflows for infra control planes

> I tend to prefer “one really good, long explanation” over lots of shallow posts.

---

## 06 // How I Like to Work

- **End‑to‑end ownership** – from design doc → infra → code → observability → post‑mortem.
- **Production‑driven design** – start from failure modes and operational constraints.
- **Readable systems** – logs, metrics, traces, and dashboards that actually answer questions.
- **High‑quality docs** – diagrams + narratives that new engineers can rely on at 3am.

---

## 07 // Contact

- **Portfolio:** `https://kunal-khare-sre.netlify.app/`  
- **LinkedIn:** `https://www.linkedin.com/in/kunaldevxxx/`  
- **Email:** `kunalkhare2004@gmail.com`

If you’re working on infrastructure control planes, OpenStack/Kubernetes migrations, or durable workflow engines and want to trade notes, I’m always up for a technical chat.
