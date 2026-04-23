# Switching, VLAN, and Security Lab

This repository documents a Cisco Packet Tracer lab focused on network segmentation, switching logic, and switch-level security controls.

The project combines practical network implementation with structured technical documentation, covering VLAN creation, trunk configuration, EtherChannel, port security, access control, and functional validation.

## Project Context

This lab was developed as part of a practical networking module focused on:

- local network design
- logical segmentation
- departmental separation
- switch configuration
- communication control
- validation of expected traffic behavior

## Project Focus

This lab covers the following areas:

- VLAN-based segmentation
- access and trunk port configuration
- EtherChannel configuration
- switch hardening
- port security
- shutdown of unused interfaces
- IP addressing for validation purposes
- connectivity testing in Packet Tracer
- isolation between distinct network segments
- documentation of implementation and results

## Objectives

The main objective of this lab was to implement and validate a segmented switched network capable of:

- separating departments through VLANs
- allowing communication only where intended
- protecting access ports against unauthorized devices
- maintaining consistent switch configuration
- demonstrating correct network behavior through simulation and testing

## Technical Scope

### Switching and Segmentation
- VLAN creation
- access port assignment
- trunk configuration
- VLAN transport between switches
- segmentation by department

### Aggregation and Backbone
- EtherChannel
- backbone consistency
- VLAN propagation across switches

### Security Controls
- port security
- sticky MAC addressing
- shutdown of unused ports
- console protection
- basic switch hardening

### Validation
- simulation-based testing
- successful communication inside the same VLAN
- failed communication between distinct VLANs
- addressing and logical verification

## What This Repository Shows

This repository is intended to demonstrate:

- practical switch configuration skills
- understanding of VLAN segmentation logic
- knowledge of trunking and EtherChannel behavior
- awareness of switch-level security measures
- ability to validate network behavior in a structured way
- capacity to document a lab with technical clarity

## Repository Structure

```text
switching-vlan-security-lab/
├── README.md
├── docs/
│   ├── case-study/
│   ├── sanitized-version/
│   └── supporting-notes/
├── images/
│   ├── topology/
│   ├── vlans/
│   ├── etherchannel/
│   ├── security/
│   └── validation/
└── notes/
    ├── overview.md
    ├── configuration-logic.md
    └── technical-scope.md

Documentation Note

Some original academic materials may contain contextual or presentation details that will be reviewed before publication. For that reason, this repository is being prepared in stages, starting with a clean public-facing structure and technical summary.

Status

In progress — public documentation and repository structure are being prepared.
