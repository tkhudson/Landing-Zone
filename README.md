# Secure Azure Landing Zone Blueprint

This repository serves as a public placeholder and documentation reference for the secure Azure landing zone blueprint that I designed and built for Hudson IT Consulting.

The actual Terraform code, modules, variables, configuration files, and sensitive security controls are intentionally not published here. They are maintained in a private, access-controlled repository due to the sensitive nature of the security posture configurations, naming conventions, policy definitions, RBAC patterns, network isolation rules, and compliance-aligned guardrails they contain.

### Purpose
- Demonstrate my approach to building secure, cost-optimized Azure landing zones following Microsoft CAF and ALZ best practices.
- Provide transparency for clients, recruiters, and collaborators interested in my cloud infrastructure and security engineering work.
- Serve as a reference point for discussions around Azure security posture management (CSPM), remote Terraform state bootstrapping, least-privilege networking, and governance foundations.

### Key Design Principles (Public Summary)
- Remote Terraform state in encrypted Azure Blob Storage with versioning and soft-delete
- Isolated VNet with management/workload subnets and default-deny NSGs
- No public IPs or endpoints by default
- Basic Azure Policy enforcement for diagnostics/logging
- Zero-trust foundation with least-privilege access and encryption at rest
- Designed for quick spin-up/spin-down (estimated cost <$1–$5 for short testing)

For inquiries about collaboration, consulting engagements, or private repo access (under NDA), please reach out directly.

Tyler Hudson -
Hudson I.T. Consulting  
February 2026  
