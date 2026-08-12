# Microsoft Entra ID Identity Security Lab

A collection of hands-on identity security exercises performed in an authorized Microsoft Entra ID lab environment. This project demonstrates identity administration, role-based access control, authentication monitoring, Conditional Access, and suspicious sign-in investigation.

## Project Objectives

* Practice secure identity and access administration.
* Examine how Entra ID implements role-based access control and least privilege.
* Analyze authentication events using sign-in logs.
* Configure Conditional Access safely in report-only mode.
* Correlate identity telemetry during a simulated security investigation.
* Document findings using an incident-response mindset.

## Case Studies

| Case Study                                                                                      | Topics                                                        | Status |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ------ |
| [Identity and Access Administration](case-studies/01-identity-access-administration.md)         | User provisioning, security groups, RBAC, least privilege     | Draft  |
| [Authentication Policy and Monitoring](case-studies/02-authentication-policy-and-monitoring.md) | Authentication logs, MFA, Conditional Access                  | Draft  |
| [Suspicious Sign-In Investigation](case-studies/03-suspicious-sign-in-investigation.md)         | Behavioral baselining, brute-force detection, incident triage | Draft  |

## Technologies and Security Concepts

* Microsoft Entra ID
* Microsoft Entra sign-in logs
* Conditional Access
* Multifactor authentication
* Identity and Access Management
* Role-Based Access Control
* Least privilege
* Behavioral analysis
* Security-event correlation
* Incident triage

## Repository Structure

* `case-studies/` — Detailed documentation of the lab activities and investigations
* `evidence/` — Sanitized screenshots and supporting evidence to be added after review

## Lab Scope

All activities were conducted in an authorized test environment using dedicated test identities. Simulated suspicious activity was intentionally generated for educational and defensive-security purposes.

The project does not contain passwords, authentication tokens, complete IP addresses, tenant identifiers, proprietary documentation, or personally identifiable information.

## Current Status

This repository is under active development. Written case studies are being reviewed for technical accuracy, and sanitized evidence will be added incrementally.
