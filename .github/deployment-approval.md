---
title: Deployment Approval Required for {{ env.ENVIRONMENT }}
labels: deployment-request
---

Deployment approval request from {{ payload.sender.login }}.

Comment "Approved" to kick the deployment off.

=== DON'T CHANGE BELOW LINE
``` json target_payload
{
  "runNumber": "{{ env.RUNNUMBER }}",
  "environment": "{{ env.ENVIRONMENT }}"
}
```
