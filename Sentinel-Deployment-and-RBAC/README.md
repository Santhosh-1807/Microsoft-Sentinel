Microsoft Sentinel — Deployment & RBAC

Objective

To understand how Microsoft Sentinel is deployed and how
Role-Based Access Control (RBAC) is used to manage access
and permissions.

Topics Covered

- Microsoft Sentinel deployment
- Log Analytics Workspace
- Sentinel workspace configuration
- Azure role-based access control (RBAC)
- User permissions
- Access management
- Security responsibilities

Deployment Concept

The basic deployment process is:

Azure
↓
Log Analytics Workspace
↓
Microsoft Sentinel
↓
Security Monitoring Environment

Log Analytics Workspace

Microsoft Sentinel is associated with a Log Analytics workspace.
The workspace is used to store and query security-related data.

RBAC

Role-Based Access Control (RBAC) is used to control what users
can do within Azure resources.

RBAC helps implement the principle of least privilege by giving
users only the permissions required for their responsibilities.

SOC Use Case

In a SOC environment, different users may require different
levels of access.

For example:

- SOC Analyst — investigate security events and incidents
- Security Administrator — manage security configurations
- Reader — view resources without making changes

Access should be granted according to job responsibilities.

Deployment Workflow

1. Access Azure
2. Select or create the required Log Analytics Workspace
3. Configure Microsoft Sentinel
4. Verify the Sentinel environment
5. Configure required permissions
6. Verify user access

Security Principle

RBAC helps reduce unnecessary privileges and limits the impact
of unauthorized or accidental changes.

Skills Demonstrated

- Microsoft Sentinel deployment
- Azure security fundamentals
- Log Analytics Workspace
- RBAC
- Access control
- Least-privilege security

Evidence

Practical screenshots from the deployment and RBAC configuration
are stored in the "screenshots" directory.


