# OLS Cline Demo
This repository demonstrates **Cline (AI Assistant)** integrated with:
✅ OpenShift LightSpeed (OLS) MCP Server
✅ GitHub MCP Server
✅ All operations performed locally from VS Code IDE

---

## 🚀 What this demo shows

This is a complete end-to-end workflow demonstration:

1. **AI Assisted Kubernetes/OpenShift operations** directly from your IDE
2. Moving workloads between OpenShift projects
3. Troubleshooting pending pods and storage issues
4. Automated git operations & pull request creation
5. Full context-aware assistance without switching tools

---

## 🛠️ Demonstrated Workflow

| Step | Action | Tool Used |
|---|---|---|
| 1 | Query OpenShift best practices for pod migration | **OpenShift LightSpeed MCP** |
| 2 | Verify existing cluster state | Local `oc` CLI |
| 3 | Export & clean pod manifests | Cline + `yq` |
| 4 | Recreate pod in target namespace | Local cluster operations |
| 5 | Diagnose pending pod scheduling issues | OpenShift LightSpeed MCP |
| 6 | Fix PVC storage class configuration | Cline edits |
| 7 | Cleanup old projects | `oc` delete operations |
| 8 | Stage, commit & push changes | Git CLI |
| 9 | Attempt automated PR creation | **GitHub MCP Server** |


---

## 🔧 Technologies Integrated

| Component | Purpose |
|---|---|
| **Cline** | AI Agent that orchestrates all operations, understands context, executes commands, edits files |
| **OpenShift LightSpeed MCP** | OpenShift & Kubernetes domain knowledge, best practices, troubleshooting guidance |
| **GitHub MCP** | Git operations, repository management, PR automation |
| **Local VS Code** | All operations run natively from your IDE, no browser context switching |

---

## 📁 Repository Contents

```
├── busybox-deployment.yaml          # Original deployment manifest
├── busybox-deployment-fixed.yaml    # Fixed version with correct storage & security
└── README.md                         # This documentation
```

---

## 💡 Key Takeaways

- **Zero context switching**: All operations performed inside VS Code
- **Domain expertise on demand**: OpenShift best practices available instantly
- **Safe iterative execution**: Cline verifies each step before proceeding
- **Full auditability**: Every action is visible and can be reviewed
- **Native tooling integration**: Works with your existing `oc`, `git`, IDE workflow

This demo shows how modern AI assistants can integrate natively with your development and operations workflow without requiring external services or web interfaces.