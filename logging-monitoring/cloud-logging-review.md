# Cloud Logging and Monitoring Review

## Objective

Review cloud logging and monitoring capabilities and document how activity logs can support security investigations.

## Background

Cloud logs help security teams understand what actions occurred, who performed them, and when they happened. Without logging, suspicious activity may be difficult to investigate.

## Review Areas

| Area | Security Question |
|---|---|
| Activity logs | Are administrative actions recorded? |
| Sign-in logs | Are user authentication events available? |
| Resource changes | Are create, update, and delete actions visible? |
| Alerts | Are alerts configured for risky activity? |
| Retention | Are logs retained long enough for investigation? |

## Example Events to Monitor

| Event Type | Security Relevance |
|---|---|
| Failed sign-in attempts | May indicate password guessing or unauthorized access attempts |
| Privileged role assignment | May indicate privilege escalation risk |
| Storage public access changes | May indicate accidental or malicious data exposure |
| Network rule changes | May expose services to the internet |
| Resource deletion | May indicate accidental deletion or destructive activity |

## Secure Monitoring Checklist

- Review activity logs regularly.
- Monitor privileged role changes.
- Monitor failed authentication attempts.
- Monitor storage access changes.
- Monitor network security rule changes.
- Configure alerts for high-risk administrative actions.
- Retain logs for investigation and compliance needs.

## Evidence

Screenshot to be added.

## Conclusion

Cloud logging and monitoring are essential for detecting suspicious activity and supporting investigations. Activity logs, sign-in logs, and alerting help analysts understand changes across the cloud environment.
