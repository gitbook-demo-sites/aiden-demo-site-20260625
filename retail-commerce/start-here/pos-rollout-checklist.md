---
description: "A representative rollout checklist for Aiden POS and retail operations."
icon: list-check
---

# POS rollout checklist

{% stepper %}
{% step %}
### Confirm store setup

Verify general store settings, specific store settings, tax behavior, receipt output, and local operational defaults.
{% endstep %}

{% step %}
### Configure users and identity

Assign POS users, portal admins, and Microsoft Entra login expectations before training store teams.
{% endstep %}

{% step %}
### Validate hardware

Check barcode scanner behavior, signature pad support, printer flow, and payment terminal readiness.
{% endstep %}

{% step %}
### Rehearse transaction paths

Run customer selection, item selection, pause/resume, finishing, gift card, cash procedure, and attachment scenarios.
{% endstep %}

{% step %}
### Connect finance handoff

Confirm reconciliation expectations with Bank Connectivity and SAP data ownership.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Treat this as a demo checklist. A production rollout should use Aiden's exact implementation plan and customer-specific SAP configuration.
{% endhint %}
