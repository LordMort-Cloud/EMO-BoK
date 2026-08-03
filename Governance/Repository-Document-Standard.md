# Repository Document Standard
Version: 1.0.0
Status: Authoritative

## 1. Purpose
This document defines the mandatory standards for all documents within the EMO-BoK repository to ensure consistency, traceability, quality and long-term maintainability.

## 2. Repository Principles
- Evidence is immutable.
- Professional assessment creates enduring knowledge.
- Knowledge must be traceable.
- GitHub is the authoritative system of record.
- Released snapshots are immutable.

## 3. Standard Document Header
Every repository document should contain:
- Document ID
- Title
- Version
- Status
- Owner
- Date Created
- Last Updated
- Repository Location
- Related Documents

## 4. Naming Convention
- HIST-xxxx – Historical Assessments
- KO-xxxx – Knowledge Objects
- OLR-xxxx – Operational Lessons
- MEC-xxxx – Master Evidence Catalogue
- PP-xxxx – Position Papers
- GOV-xxxx – Governance
- EMO-REF-xxxx – References

## 5. Traceability
Maintain the chain:
Evidence → Historical Assessment → Knowledge Object → Operational Lesson → Position Paper → Book

## 6. Versioning
Use Semantic Versioning (MAJOR.MINOR.PATCH).

## 7. Quality Assurance
Before commit:
- Metadata complete
- Traceability checked
- References verified
- Markdown valid
- Related links updated

## 8. Git Workflow
Draft → Review → Commit → Snapshot → Push → Release