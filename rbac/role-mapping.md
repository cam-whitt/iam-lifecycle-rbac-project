# Role-Based Access Control (RBAC) Mapping

## Objective
Demonstrate how job roles map to permissions using RBAC to enforce least privilege.

## Example Roles

| Role | Access Granted | Risk Level |
|----|----|----|
| IT Support | User account management, password resets | Medium |
| SOC Analyst | Log access, alert review tools | Medium |
| IAM Analyst | Identity systems, access reviews | High |
| Administrator | System-wide privileged access | Critical |

## RBAC Principles
- Users are assigned roles, not individual permissions
- Permissions are grouped based on job function
- Privileged roles require additional approval and monitoring

## Risks Addressed
- Excessive individual permissions
- Lack of visibility into access
- Inconsistent access assignments

## Why This Matters
RBAC simplifies access management, improves auditability, and reduces the likelihood of unauthorized privilege escalation.
