# VoltMart ISO 27001 Control Mapping

This repository maps each risk from the VoltMart STRIDE risk register to the most relevant ISO 27001:2022 Annex A control(s), along with a concrete mitigation action for VoltMart.

## What's in This Repo
- **control_mapping.csv** - all 12 risks from `risk_register.csv`, each mapped to an ISO 27001 Annex A control, with a specific mitigation action, assigned owner, and target completion date

## Mapping Approach
For each risk, I identified the Annex A control that most directly addresses its root cause - for example, risks involving payment data interception were mapped to A.8.24 (Use of cryptography), while risks involving unauthorized elevated access were mapped to A.8.2 (Privileged access rights). Every mitigation action was written to be specific and realistic for a small retailer - no expensive enterprise tools, just practical steps like enabling encryption, restricting admin rights, and setting up basic monitoring.

## Target Dates
Target dates are given as a number of days from when this plan was created, representing a reasonable deadline for implementation - not the time it takes to perform the task itself. Higher-urgency risks (e.g., ransomware protection, privileged access) were given shorter deadlines (14 days), while lower-urgency items were given 30 days.

## Source
This mapping builds directly on the risk register maintained in the companion repository: `voltmart-stride-risk-register`.
