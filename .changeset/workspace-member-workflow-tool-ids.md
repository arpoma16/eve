---
"eve": patch
---

Workflow tools in an eve workspace member (`agents/<name>/` without its own `package.json`) now compile with the same workflow id the deployment registers, so calling them no longer fails with "is not registered as a workflow in this deployment".
