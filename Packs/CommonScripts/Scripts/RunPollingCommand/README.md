Runs a one time specified polling command. This is useful for initiating a local playbook context before running a polling scheduled task.

## Permissions
---

This automation runs using the default Limited User role, unless you explicitly change the permissions.
For more information, see the section about permissions here: [https://docs.paloaltonetworks.com/cortex/cortex-xsoar/6-2/cortex-xsoar-admin/playbooks/automations.html
](https://docs.paloaltonetworks.com/cortex/cortex-xsoar/6-2/cortex-xsoar-admin/playbooks/automations.html)

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | python |
| Tags | - |
| Cortex XSOAR Version | 4.0.0+ |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| ids | The list of IDs to poll. |
| pollingCommand | The name of the polling command to run. |
| pollingCommandArgName | The name of the argument of the polling command. |
| additionalPollingCommandArgNames | The comma-separated arguments of the polling command. |
| additionalPollingCommandArgValues | The comma-separated arguments values of the polling command. |

## Outputs
---
There are no outputs for this script.
