# Storage Access Review

## Objective

Review cloud storage access settings and document secure configuration recommendations to reduce the risk of public data exposure.

## Background

Cloud storage misconfigurations are a common security risk. If storage containers, buckets, or blobs are publicly accessible without proper controls, sensitive data may be exposed to unauthorized users.

## Review Areas

| Area | Security Question |
|---|---|
| Public access | Is anonymous or public access disabled? |
| Access control | Are permissions limited to authorized users only? |
| Encryption | Is data encrypted at rest? |
| Logging | Are storage access logs enabled or available? |
| Sensitive data | Is sensitive information avoided in test storage? |
| Lifecycle management | Are unused files removed when no longer needed? |

## Example Risks

| Risk | Impact | Recommendation |
|---|---|---|
| Public storage access enabled | Sensitive data may be exposed publicly | Disable anonymous/public access |
| Excessive permissions | Unauthorized users may access or modify files | Apply least privilege access |
| Missing logging | Suspicious access may go undetected | Enable storage logging and monitoring |
| Sensitive test files uploaded | Accidental data exposure | Use only dummy test data |
| Unused storage resources | Increased attack surface and cost | Remove unused storage resources |

## Secure Configuration Checklist

- Disable anonymous/public access unless explicitly required.
- Use role-based access control for authorized users.
- Avoid storing real sensitive data in lab environments.
- Enable encryption at rest.
- Review access permissions regularly.
- Monitor access logs for unusual activity.
- Remove unused storage containers and test files.

## Evidence

Screenshot to be added.

## Conclusion

Storage security is important because cloud storage is commonly targeted and frequently misconfigured. Restricting access, enabling monitoring, and avoiding sensitive test data can reduce the risk of accidental exposure.
