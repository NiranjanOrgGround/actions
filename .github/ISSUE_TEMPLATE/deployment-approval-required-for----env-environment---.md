---
name: Deployment Approval 
about: Deployment Approval
title: 'Deployment Approval Required'
labels: deployment-requested
assignees: niranjanakoni

---
<!--
Deployment Approval requested from {{ payload.sender.login }}.
Comment "Approved" to kick the deployment off.


=== DON'T CHANGE BELOW THIS LINE
```json target_payload
{
    "runNumber":  {{ env.RUNNUMBER }},
    "environment": "{{ env.ENVIRONMENT }}"
}
```
-->
