# Healthcare Appointment Management System

System analysis and design report for a healthcare appointment booking system for Irish GP practices and clinics. 4-person group project, CSC1016 Business Systems Analysis, DCU.

📄 [Read the full report (PDF)](report.pdf)

## Overview
In this module, each group wrote a short system proposal, then another group did the full analysis and design for it. Our team took a 5-process proposal from another group and turned it into nine detailed, implementation-ready BPMN models plus a UML class diagram. All the design work in this report is ours. The designs handle real-world problems like scheduling conflicts, incomplete patient records, delayed confirmations and GDPR compliance.

## My contribution (25%)
- **Process 2.5 - Provider Availability Check & Scheduling:** queries provider calendars in real time and books the slot if one is available, using an event-based gateway and message flows between the scheduling system and the provider calendar
- **Process 2.6 - Alternative Scheduling & Patient Negotiation:** when no slot is free, offers the patient up to 3 alternatives, waits 48 hours for a reply, then escalates to reception staff for manual negotiation, with waitlist and cancellation paths
- System design and multi-pool collaboration diagrams

**Methods:** BPMN 2.0 (event-based gateways, timer and message events, sub-processes, multi-pool collaboration), UML class diagrams, process analysis
