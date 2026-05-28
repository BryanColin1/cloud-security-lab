# IAM Least Privilege Review

## Objective

Review identity and access management settings in a cloud lab environment and document least privilege recommendations.

## Background

Identity and access management is a core part of cloud security. Overly broad permissions can increase the risk of unauthorized access, privilege escalation, and accidental misuse of cloud resources.

## Review Areas

| Area | Security Question |
|---|---|
| User access | Are users assigned only the permissions they need? |
| Role assignment | Are privileged roles limited and justified? |
| MFA | Is multi-factor authentication enabled where appropriate? |
| Least privilege | Are broad permissions avoided? |
| Access review | Are permissions reviewed regularly? |

## Planned Methodology

1. Identify users and roles in the lab environment.
2. Review assigned permissions.
3. Check for excessive privileges.
4. Document risks and recommendations.
5. Create a least privilege checklist.

## Example Risks

| Risk | Impact | Recommendation |
|---|---|---|
| Overly broad administrator access | Increases blast radius if account is compromised | Assign only required roles |
| Missing MFA | Increases risk from stolen passwords | Enable MFA for privileged users |
| Unused accounts | Increases attack surface | Disable or remove unused accounts |
| Lack of access review | Permissions may become outdated | Review access periodically |

## Evidence

Screenshot to be added.

## Conclusion

IAM security is critical in cloud environments because identity is often the primary security boundary. Applying least privilege helps reduce risk and limit the impact of account compromise.
