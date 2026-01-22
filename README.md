# DevOps Homelab

A Linux-first DevOps homelab documenting real infrastructure decisions, trade-offs, and failure modes.

This repository represents my primary professional homelab. Its goal is not to showcase tools, but to practice and document **architecture, reliability, and operational reasoning** under realistic constraints.

The homelab evolves over time and is used to simulate production-like scenarios across local and cloud environments, focusing on how systems behave, break, and recover.

## Purpose

This homelab is used to:
- Design and operate a production-inspired platform
- Practice Kubernetes operations beyond the happy path
- Explore infrastructure and platform trade-offs
- Validate architectural assumptions through hands-on experiments
- Document decisions and their consequences over time

The emphasis is on **clarity of reasoning**, not feature completeness.

## Scope

The homelab covers, but is not limited to:

- Linux systems and networking
- Kubernetes platforms and workloads
- Infrastructure as Code
- Automation and CI/CD
- Observability, reliability, and resilience
- Hybrid local and cloud-based experiments

## Documentation

Detailed documentation is maintained in the GitHub Wiki. (In progress)

Key entry points:
- **Overview**: goals, constraints, and evolution  
- **Architecture**: high-level system design and diagrams  
- **Decisions (ADRs)**: architectural and technical decisions with context  
- **Operations**: how the platform is operated and maintained  
- **Lessons Learned**: what broke, why, and what changed as a result  

## Repository Structure

This repository is intentionally structured around responsibilities rather than tools:

- infrastructure/  
  Foundational provisioning and base resources
- platform/  
  Platform-level configuration and workloads
- automation/  
  Scripts, pipelines, and automation glue
- docs/  
  Documentation assets and diagrams referenced by the Wiki

Implementation details may evolve but the architectural intent remains stable.

## Principles

- Documentation over demos
- Decisions over tools
- Constraints over convenience
- Learning through controlled failure
- Clarity over complexity

## Status

This homelab is actively evolving.  
Not all components are present at all times, and some areas intentionally remain incomplete while being explored.
