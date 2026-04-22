# Wildfire Incident Response Case Study  
### Real-World Incident Response → IT / Cybersecurity Mindset

---

## Overview

This case study documents a real-world wildfire incident near a school campus and demonstrates structured incident response under time pressure.

Although this is a physical event, the response methodology directly aligns with:
- IT Systems Administration
- Cybersecurity Incident Response (SOC)
- Network Monitoring and Escalation Protocols

The focus is on:
- Detection and monitoring
- Predefined trigger thresholds
- Controlled escalation
- Resource coordination
- Post-incident analysis

---

## Incident Context

- Environment: School campus adjacent to dry vegetation field and hillside
- Threat: Active wildfire with visible progression toward perimeter
- Constraints:
  - Limited visibility at night
  - Uncertain fire spread direction
  - No immediate external directive

---

## Key Visual Evidence

### 1. Fire Approaching Perimeter Boundary (Critical Threshold)

![Wildfire approaching perimeter boundary at night](images/wildfire-perimeter-boundary-night.jpg)

**Figure 1:** Active wildfire nearing the defined perimeter boundary.

This represents the **primary trigger condition**, equivalent to:
- A monitored system crossing a critical threshold
- Example (IT): CPU at 100%, unauthorized access detected, lateral movement observed

---

### 2. Fireline Progression (Threat Movement Analysis)

![Wildfire slope fire during daytime](images/wildfire-slope-fire-day.jpg)

**Figure 2:** Fire movement across terrain.

Equivalent to:
- Tracking attacker movement across a network
- Observing spread patterns and predicting next targets

---

### 3. Smoke Encroachment (Early Warning Signal)

![Wildfire smoke moving toward buildings](images/wildfire-smoke-encroachment.jpg)

**Figure 3:** Smoke affecting visibility before direct impact.

Equivalent to:
- Early indicators (logs, alerts, anomalies)
- Signals that precede full system compromise

---

### 4. Initial Ignition (Detection Phase)

![Wildfire initial ignition at night](images/wildfire-initial-ignition-night.jpg)

**Figure 4:** Initial detection of threat.

Equivalent to:
- First alert in SIEM
- Suspicious login or anomaly detection

---

### 5. Fireline Intensity (Escalation Phase)

![Wildfire fireline progression](images/wildfire-fireline-progression.jpg)

**Figure 5:** Increased intensity and spread.

Equivalent to:
- Confirmed incident escalation
- Multiple alerts correlating into a real threat

---

### 6. Boundary Reference (Network Perimeter Analogy)

![School boundary and dry field reference](images/site-boundary-reference-day.jpg)

**Figure 6:** Defined boundary between safe zone and risk zone.

Equivalent to:
- Network segmentation boundary
- Firewall perimeter
- Trust boundary in infrastructure

---

## Incident Response Lifecycle Mapping

### 1. Detection

- Visual confirmation of fire activity
- Monitoring changes in intensity and direction

**IT Equivalent:**
- Log monitoring
- Alert systems (SIEM, IDS/IPS)

---

### 2. Analysis

- Evaluated terrain, fuel sources, and proximity
- Identified high-risk zone (dry vegetation field)

**IT Equivalent:**
- Root cause analysis
- Identifying attack vectors or vulnerable systems

---

### 3. Trigger Definition (Critical Step)

A predefined condition was established:

> **Trigger:** Fire crosses beyond dry field boundary toward school property

This eliminated:
- Hesitation
- Emotional decision-making
- Dependence on delayed external commands

**IT Equivalent:**
- Alert thresholds
- Automated escalation rules
- Runbooks for incident severity levels

---

### 4. Response Preparation

Actions staged BEFORE escalation:

- Transportation (evacuation vehicle) on standby
- Muster point pre-selected (low-risk zone)
- Staff roles understood
- Secondary location identified

**IT Equivalent:**
- Incident response playbooks
- Backup systems ready
- Failover planning
- Role-based access and responsibilities

---

### 5. Containment Strategy

- Students moved to controlled, safe muster area (cement field)
- Avoided high-risk zones (fuel, buildings)

**IT Equivalent:**
- Network isolation
- Segmentation
- Containing compromised systems

---

### 6. Communication and Coordination

- Clear chain of command
- No reliance on unclear or delayed external directives

**IT Equivalent:**
- Incident command structure
- Internal escalation paths
- Avoiding dependency on slow external responses

---

## Outcome

- No emergency evacuation required
- Full readiness maintained
- No confusion or reactive decision-making

---

## Lessons Learned (Post-Incident Analysis)

### What worked

- Predefined trigger conditions → eliminated delay
- Early staging of resources → reduced response time
- Clear visibility of boundary → improved decision accuracy

---

### Improvements (Next Iteration)

- Define secondary triggers (e.g., smoke density / air quality thresholds)
- Implement redundant communication systems
- Pre-assign smaller response units (group leaders)

---

## Cybersecurity & IT Relevance

This incident demonstrates core competencies required in:

### IT Systems Administration
- Monitoring systems under changing conditions
- Planning for failure before it happens
- Structuring response procedures

### Cybersecurity / SOC
- Detection → Analysis → Response lifecycle
- Threshold-based escalation
- Incident containment strategies
- Decision-making under uncertainty

### Networking
- Understanding boundaries and segmentation
- Identifying risk zones and pathways of spread

---

## Skills Demonstrated

- Incident Response Planning
- Risk Assessment and Threat Modeling
- Systems Thinking Under Pressure
- Structured Decision-Making
- Operational Leadership
- Clear Technical Documentation
