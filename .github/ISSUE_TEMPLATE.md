---
name: Approval for Deployment
title: "Deployment Approval Required for {{ env.ENVIRONMENT }}"
labels: deployment-requested
assignees: niranjanakoni
---

Deployment Approval requested from {{ payload.sender.login }}.

Comment "Approved" to kick the deployment off.


=== DON'T CHANGE BELOW THIS LINE
```json target_payload
{
    "runNumber":  {{ env.RUNNUMBER }},
    "environment": "{{ env.ENVIRONMENT }}"
}
```