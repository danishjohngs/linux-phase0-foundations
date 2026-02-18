# Linux Phase-0 Foundations

This repository documents my hands-on Linux foundation work completed as part of my Cloud Security → DevSecOps roadmap.

The focus of this phase was to build strong fundamentals in:

- Linux system architecture
- Command-line proficiency
- User and permission management
- Process and service control
- Log investigation
- Security enforcement using role-based access

This phase was completed using:

- TryHackMe – Linux Fundamentals 1, 2, 3
- Practical implementation and security validation labs

---

## Core Skills Demonstrated

### 1. Filesystem & Architecture
- Understanding of Linux directory structure
- System vs user space separation
- Root directory importance

### 2. Command Line Proficiency
- File and directory manipulation
- Text processing
- Documentation access via `man`, `--help`

### 3. User & Permission Security
- Multi-user environment setup
- Group-based access control
- Ownership management using `chown`
- Permission control using `chmod`
- Real-world enforcement validation

### 4. Process & Service Management
- Monitoring processes
- Signal handling
- Service control via `systemctl`
- Scheduled automation using `cron`

### 5. Log Investigation
- Analysis of `/var/log`
- Understanding authentication logs
- Identifying security-relevant events

---

## Practical Security Lab

The key project in this phase:

### User Permission Security Lab

Objective:
Simulate a development team with controlled shared access using Linux RBAC (Role-Based Access Control).

Key Outcomes:
- Implemented secure shared directory owned by root
- Enforced group-level access
- Validated permission denial scenarios
- Applied least-privilege principles

See full implementation under:
`/projects/user-permission-security-lab/`

---

## Why This Matters for Cloud Security

Linux permission logic directly maps to:

- AWS IAM authorization
- S3 access policies
- Kubernetes RBAC
- Cloud security enforcement mechanisms

This repository demonstrates practical Linux security understanding, not theoretical knowledge.

---

## Status

Phase 0 – Linux Foundations: Completed  
Next Phase: Networking Foundations
