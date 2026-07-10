# 👋 Kunal Khare – Infrastructure & Distributed Systems Engineer

> _Understanding how things actually work under the hood: from OpenStack's I/O paths to Temporal's event-sourced workflows._

---

<div align="center">

### 🚀 **Deploy Your First Exploration**

```bash
# Initialize your journey
$ curl -s https://kunal-khare-sre.netlify.app | grep "infrastructure"

# Navigate to deep-dive resources
$ cd /portfolio/infrastructure
$ ls -la

# Core Interests
$ cat interests.txt
├── Cloud Infrastructure (OpenStack, Kubernetes/GKE)
├── Control-Plane Orchestration (Temporal, Migrations)
├── Developer Experience (CI/CD, Ephemeral Environments)
└── Infra Storytelling (Diagrams + Deep Dives)
```

</div>

---

## 📡 **Infrastructure Stack**

<table>
<tr>
<td width="50%">

### **Cloud Platforms**
- OpenStack (Nova, Cinder, Glance, Neutron, Octavia, Designate)
- Kubernetes / GKE, Helm, HPA
- Temporal (durable workflows)
- PostgreSQL, Redis

### **Networking & Storage**
- Linux networking (iptables/OVN)
- DNS (PowerDNS/BIND)
- NGINX/HAProxy load balancing
- Storage drivers & I/O optimization

</td>
<td width="50%">

### **Frontend & Tooling**
- React 18, Vite, React Router
- Tailwind CSS, Framer Motion
- Three.js, React Three Fiber
- TypeScript, ESLint, PostCSS

### **DevOps & CI/CD**
- GitHub Actions
- Docker & container pipelines
- Ephemeral PR environments
- Observability dashboards

</td>
</tr>
</table>

---

## 📚 **Selected Deep Dives**

A collection of highly technical, implementation-focused posts:

| Post | Focus Area | Depth |
|------|-----------|-------|
| **[Inside OpenStack Cinder + Glance: The Real Boot-from-Volume Pipeline](https://kunal-khare-sre.netlify.app/blog/openstack-cinder-glance-boot-from-volume-pipeline)** | Storage, Nova, Libvirt | Every step traced across drivers |
| **[Why We Chose Temporal Over Argo & Airflow](https://kunal-khare-sre.netlify.app/blog/temporal-vs-argo-airflow-control-plane-orchestration)** | Orchestration, Workflows | Production-driven comparison |
| **[App Engine to GKE: Kubernetes Architecture Deep Dive](https://kunal-khare-sre.netlify.app/blog/app-engine-to-gke-kubernetes-architecture)** | Resource economics, autoscaling | HPA, CUDs, node pools |
| **[Inside OpenStack Networking: Neutron + Octavia + Designate](https://kunal-khare-sre.netlify.app/blog/openstack-networking-neutron-octavia-designate)** | ML2/OVN, LBaaS, DNS | Full integration pipeline |

---

## 🛠️ **CLI Actions – Deploy & Explore**

```bash
# ═══════════════════════════════════════════════════════════════
# FORWARD DEPLOY ENGINEER – Interactive Command Suite
# ═══════════════════════════════════════════════════════════════

$ forward-deploy init --profile kunal

🔧 Initializing forward-deploy context...
├─ [✓] Infrastructure knowledge base loaded
├─ [✓] Temporal workflows engine ready
├─ [✓] Kubernetes cluster context set
└─ [✓] 3D visualization pipeline active

# ───────────────────────────────────────────────────────────────
# 1. EXPLORE INFRASTRUCTURE PATTERNS
# ───────────────────────────────────────────────────────────────

$ forward-deploy explore --stack openstack
🔍 Fetching OpenStack pipeline internals...

Architecture Overview:
  ┌─────────────────────────────────────────────────┐
  │  Nova Compute  ──→  Cinder Storage  ──→  Glance │
  │       │                   │                  │   │
  │       └─→ Neutron Networking ──→ Octavia LBaaS  │
  │                           │                     │
  │                      Designate DNS              │
  └─────────────────────────────────────────────────┘

$ forward-deploy deep-dive --component cinder-io
📊 Analyzing Cinder I/O path...
  • Block device provisioning
  • Volume attachment lifecycle
  • Storage driver optimization
  • Performance metrics & bottlenecks

$ forward-deploy trace --request "openstack server create --boot-from-volume"
🎯 Request tracing: Nova → Cinder → Glance → Libvirt
  ✓ Step 1: Nova receives API call
  ✓ Step 2: Volume lookup in Cinder
  ✓ Step 3: Glance image download
  ✓ Step 4: Domain XML generation
  ✓ Step 5: Libvirt domain launch
  └─ Estimated latency: 45-120s (depends on image size)

# ───────────────────────────────────────────────────────────────
# 2. KUBERNETES OPERATIONS
# ───────────────────────────────────────────────────────────────

$ forward-deploy k8s-audit --cluster gke-prod
🔐 Cluster audit:
  ├─ Node pools: 3 (standard, compute, ephemeral)
  ├─ Requests/Limits: Properly configured
  ├─ HPA active: 12 deployments with dynamic scaling
  ├─ PR environments: Ephemeral, auto-cleanup
  └─ Cost optimization: 18% reduction via CUDs

$ forward-deploy resource-matrix --show economics
📈 Resource Economics Matrix:
  ┌─────────────────────────────────────────────┐
  │ Node Type  │ CPU  │ Memory │ Cost  │ Density│
  ├─────────────────────────────────────────────┤
  │ Standard   │  4   │  16GB  │ $$$   │  4/pod│
  │ Compute    │  16  │  64GB  │ $$$$ │  2/pod│
  │ Ephemeral  │  2   │  8GB   │ $    │ 12/pod│
  └─────────────────────────────────────────────┘

$ forward-deploy hpa-tune --deployment api-server --target-cpu 70
⚙️  Horizontal Pod Autoscaler tuned:
  • Min replicas: 3
  • Max replicas: 20
  • Target CPU: 70%
  • Scale-up delay: 15s
  • Scale-down delay: 5m

# ───────────────────────────────────────────────────────────────
# 3. TEMPORAL WORKFLOW DEBUGGING
# ───────────────────────────────────────────────────────────────

$ forward-deploy temporal-debug --workflow infrastructure-migration
🔄 Workflow execution history:
  Workflow ID: infra-migrate-2024-q2
  Status: RUNNING (3 activities completed, 1 in progress)
  
  Timeline:
  ├─ [2024-01-15 14:22:10] PreFlightCheck ✓ (2.3s)
  ├─ [2024-01-15 14:22:12] ValidateResources ✓ (15.2s)
  ├─ [2024-01-15 14:22:27] DataSnapshot ⏳ (running, 3.1s elapsed)
  └─ [Pending] MigrationExecute (waiting for snapshot)

$ forward-deploy temporal-replay --execution-id 12345 --debug-level verbose
🔍 Event sourcing replay:
  Replaying 847 events from event log...
  • Determinism check: PASS
  • State transitions: Valid
  • Retry policies: Honored
  └─ Replay duration: 2.4s (100% match with live execution)

$ forward-deploy temporal-signal --workflow infra-migrate-2024-q2 \
                                 --signal cancel-with-cleanup
✓ Signal sent: cancel-with-cleanup
  Workflow will:
  ├─ Complete current activity
  ├─ Trigger cleanup routines
  ├─ Log final metrics
  └─ Mark migration as rolled back

# ───────────────────────────────────────────────────────────────
# 4. OBSERVABILITY & DEBUGGING
# ───────────────────────────────────────────────────────────────

$ forward-deploy logs --service neutron --tail 500 --filter "error|warn"
🔍 Neutron logs (last 500, errors & warnings):
  [2024-01-15 14:22:45] WARNING: OVN bridge recalculation (2.1s)
  [2024-01-15 14:23:12] ERROR: ML2 plugin sync failure (retrying...)
  [2024-01-15 14:23:15] INFO: Recovered from sync, continuing

$ forward-deploy metrics --query "openstack_cinder_volume_latency_p99"
📊 Cinder Volume Latency (p99):
  ├─ SSD volumes:     8.2ms
  ├─ HDD volumes:     42.1ms
  ├─ NVMe volumes:    3.1ms
  └─ Trend: Stable (variance < 5%)

$ forward-deploy trace-request --req-id abc123 --show-waterfall
⏱️  Request waterfall (req_id=abc123):
  API Ingress       ▓░░░░░░░░░░░░░░░░░░░  [  45ms] ✓
  Authorization     ░▓░░░░░░░░░░░░░░░░░░  [   8ms] ✓
  Database Query    ░░▓▓▓▓░░░░░░░░░░░░░░  [ 120ms] ✓
  Storage RPC       ░░░░░░▓▓▓▓▓▓░░░░░░░░  [ 230ms] ✓
  Serialization     ░░░░░░░░░░░░░▓░░░░░░  [  32ms] ✓
  ─────────────────────────────────────────────────
  Total latency:                            [ 435ms]

# ───────────────────────────────────────────────────────────────
# 5. DEPLOYMENT & ROLLBACK
# ───────────────────────────────────────────────────────────────

$ forward-deploy plan-rollout --service nova-conductor --version v2.45.1
📋 Rollout plan:
  Deployment: nova-conductor
  Current: v2.45.0 (stable for 14 days)
  Target:  v2.45.1 (5 hotfixes, 12 KB binary)
  
  Rollout Strategy: Canary
  ├─ Phase 1: 1 replica (5 min observation)
  ├─ Phase 2: 25% of fleet (15 min)
  ├─ Phase 3: 75% of fleet (30 min)
  └─ Phase 4: 100% (monitor 1 hour)

$ forward-deploy execute-rollout --service nova-conductor
🚀 Starting rollout...
  ├─ [████████░░] Canary (1/3)        40% ✓
  ├─ [████░░░░░░] Phase 2 (2/8)       25% ✓
  └─ [░░░░░░░░░░] Phase 3 pending    0%

$ forward-deploy rollback --service nova-conductor --reason "increased_latency"
⚠️  ROLLBACK INITIATED
  Reason: Increased latency detected (p99: 450ms → 850ms)
  Strategy: Immediate (fast fallback to v2.45.0)
  
  Rollback progress:
  ├─ Stop new deployments      ✓
  ├─ Drain in-flight requests  ✓ (waiting on 3 long operations)
  ├─ Revert image deployment   ▓░ 30% complete
  └─ Verify traffic return     ░░ pending

# ───────────────────────────────────────────────────────────────
# 6. POST-INCIDENT ANALYSIS
# ───────────────────────────────────────────────────────────────

$ forward-deploy incident-postmortem --id INC-2024-001 --auto-generate
📋 Auto-generated Postmortem:
  
  Title: Cinder Storage Latency Spike (2024-01-15 14:00–14:45)
  Duration: 45 minutes
  Impact: 2,300 volume I/O requests affected (0.3% error rate)
  
  Root Cause:
  • OVN data plane recalculation triggered by network config update
  • Cascading effect on storage driver's RPC latency
  
  Timeline:
  14:00 - Config push to 5% of Neutron nodes
  14:12 - OVN bridge recalculation begins (expected 2min, took 8min)
  14:20 - Cinder I/O latency increases (p99: 8ms → 150ms)
  14:25 - Alert fires; operator investigation starts
  14:30 - Root cause identified
  14:35 - Config rolled back
  14:45 - Latency returns to baseline
  
  Action Items:
  ├─ [ ] Increase OVN recalculation timeout
  ├─ [ ] Add latency canary before network pushes
  ├─ [ ] Improve alerting precision (reduce false positives)
  └─ [ ] Document Neutron/Cinder coupling

$ forward-deploy generate-report --format pdf --include graphs metrics timeline
📄 Postmortem PDF generated: incident-2024-001-report.pdf

# ═══════════════════════════════════════════════════════════════
```

---

## 🎯 **How I Work**

- **End-to-end ownership** – Design → Infrastructure → Code → Observability → Post-mortem
- **Production-driven design** – Start from failure modes and operational constraints
- **Readable systems** – Logs, metrics, traces, dashboards that actually answer questions
- **High-quality docs** – Diagrams + narratives that new engineers can rely on at 3am

---

## 🔗 **Connect**

<div align="center">

| **Portfolio** | **LinkedIn** | **Email** |
|:---:|:---:|:---:|
| [kunal-khare-sre.netlify.app](https://kunal-khare-sre.netlify.app) | [LinkedIn Profile](https://www.linkedin.com/in/kunaldevxxx/) | kunalkhare2004@gmail.com |

**Open to discussions on:**
- OpenStack/Kubernetes migrations
- Infrastructure control planes
- Durable workflow engines
- Production observability

</div>

---

<div align="center">

### 📊 **3D Infrastructure Visualization**

```
      ┌──────────────────────────────────────────┐
      │      Infrastructure & Distributed       │
      │        Systems Engineering              │
      └──────────────────────────────────────────┘
                         │
           ┌─────────────┼─────────────┐
           │             │             │
      ┌────▼────┐  ┌────▼────┐  ┌────▼────┐
      │ OpenStack│  │ Temporal│  │Kubernetes
      │ Storage/ │  │ Workflow│  │  GKE    │
      │Networking│  │ Engine  │  │  HPA    │
      └─────────┘  └────┬────┘  └────┬────┘
                        │            │
                 ┌──────┴────────────┘
                 │
         ┌───────▼────────┐
         │  Observability  │
         │  & Debugging    │
         └─────────────────┘
```

**Let's build reliable, observable infrastructure together.**

</div>
