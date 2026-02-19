
---

# Security Analysis

## Role-Based Access Control

Linux enforces access using:

- User owner
- Group owner
- Permission bits (rwx)

This mirrors IAM-based authorization models in cloud platforms.

## Principle of Least Privilege

After removing group write permission:

- Users retained read access
- Write access was restricted

This demonstrates controlled privilege reduction without breaking availability.

## Real-World Relevance

The same security model applies to:

- AWS IAM policies
- S3 bucket permissions
- Kubernetes RBAC
- Linux production servers
