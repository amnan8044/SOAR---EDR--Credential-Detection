# Tines SOAR Workflow – Automated Endpoint Isolation

## Overview
This Tines workflow automates incident response for credential harvesting detections received from LimaCharlie.

When a detection fires, the workflow isolates the affected endpoint and notifies analysts in Slack.

---

## Workflow Steps
1. Receive detection alert from LimaCharlie via webhook
2. Extract sensor and host identifiers
3. Trigger endpoint isolation action in LimaCharlie
4. Send real-time alert to Slack
5. Validate containment by confirming loss of network connectivity

---

## Outcome
- Malicious activity is contained automatically
- Endpoint is isolated within seconds of detection
- SOC analysts are notified immediately via Slack
