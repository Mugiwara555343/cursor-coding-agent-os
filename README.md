## Lean + Verbose Agent OS MDC Files

This fork adapts **Brian Casel’s Agent OS** instruction set for solo builders who need
low‑token speed **where it matters** and rich, self‑documenting detail **where it helps**.

### What’s different?

| File | Mode | Why |
|------|------|-----|
| `analyze-product-v2.mdc` | **Lean** | Fast diagnostics & thinking loop |
| `execute-tasks-v2.mdc`   | **Lean** | Quick, safe execution; low overhead |
| `plan-product.mdc`       | **Verbose** | Full architectural context & workflow guidance |
| `create-spec.mdc`        | **Verbose** | Detailed specification template & decision tree |

- 📉 Lean files are ≈ 60‑80 % smaller — perfect for o3 / o4‑mini budgets  
- 🛡 Both modes keep strict execution gates, rollback policies, and thinking loops  
- ⚙️ Swap in verbose files for deeper guidance when collaborating with humans or larger models

### Credit

Huge thanks to **Brian Casel** and the [Builder Methods / Agent OS](https://github.com/buildermethods/agent-os) project for the original concept and structure.  
This fork simply tailors that work for a lean, single‑developer workflow — while preserving verbose templates where architectural clarity is valuable.

___________________________________________________________________________________________________________________________________________________________________________________
## Original Agent:

[Agent OS](https://buildermethods.com/agent-os) transforms AI coding agents from confused interns into productive developers. With structured workflows that capture your standards, your stack, and the unique details of your codebase, Agent OS gives your agents the specs they need to ship quality code on the first try—not the fifth.

Use it with:

✅ Claude Code, Cursor, or any other AI coding tool.

✅ New products or established codebases.

✅ Big features, small fixes, or anything in between.

✅ Any language or framework.

---

### Documentation & Installation

Docs, installation, useage, & best practices 👉 [It's all here](https://buildermethods.com/agent-os)

---

Get Brian's free resources on building with AI:
- [Builder Briefing newsletter](https://buildermethods.com)
- [YouTube](https://youtube.com/@briancasel)
