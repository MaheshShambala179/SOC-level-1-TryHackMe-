# Cyber Kill Chain

## Overview

The Cyber Kill Chain is a model for describing common stages of an intrusion. SOC analysts can use it to organize observations, connect related alerts, and consider where defensive controls or response actions may interrupt an incident. Real incidents do not always follow these stages in order, and activity may skip or repeat stages.

## The seven stages

1. **Reconnaissance** — An actor gathers information about a potential target. Defenders can reduce unnecessary exposure and monitor for suspicious discovery activity.
2. **Weaponization** — An actor prepares a capability intended to exploit a weakness or deliver malicious content. Defensive teams focus on threat intelligence, secure configuration, and prevention controls.
3. **Delivery** — The capability is presented to a target, for example through a message, a web resource, or removable media. Email, web, and endpoint controls can help detect or block suspicious delivery.
4. **Exploitation** — A weakness or user interaction is used to trigger unintended behavior. Patching, application hardening, and endpoint monitoring help reduce risk and identify suspicious changes.
5. **Installation** — The actor attempts to establish a presence on a system. Endpoint protection and monitoring for unexpected software or persistence changes are relevant defenses.
6. **Command and Control (C2)** — A compromised system may communicate with external infrastructure. Network monitoring, DNS analysis, and egress controls can help identify unusual communications.
7. **Actions on Objectives** — The actor attempts to achieve their goal, such as accessing, disrupting, or stealing information. Access controls, data monitoring, and incident response help contain impact.

## How a SOC can use the model

- Map alerts and evidence to possible stages, while treating the mapping as a guide rather than proof.
- Build a timeline from endpoint, identity, email, and network telemetry.
- Look for opportunities to contain activity and prevent progression to later stages.
- Record evidence and uncertainty clearly; one event may have several possible explanations.

## Key takeaway

The model encourages defenders to think beyond an isolated alert and assess the broader sequence of activity. It complements, rather than replaces, detailed incident-response procedures and other threat frameworks.

## My Notes

Add room-specific notes, examples, and lessons learned here.

## Completed

- [ ] Room completed
