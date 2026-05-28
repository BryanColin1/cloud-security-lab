# Network Security Review

## Objective

Review cloud network security controls and document recommendations for reducing unnecessary exposure.

## Background

Cloud network security controls help limit inbound and outbound access to cloud resources. Misconfigured rules may expose services directly to the internet, increasing the risk of scanning, brute-force attempts, and exploitation.

## Review Areas

| Area | Security Question |
|---|---|
| Inbound rules | Are unnecessary inbound ports blocked? |
| Remote access | Is SSH/RDP restricted to trusted IP addresses? |
| Public exposure | Are internet-facing resources justified? |
| Segmentation | Are resources separated by function or sensitivity? |
| Logging | Are network flow logs or activity logs available? |

## Example Risks

| Risk | Impact | Recommendation |
|---|---|---|
| SSH or RDP open to the internet | Attackers may attempt brute-force or exploitation | Restrict management access to trusted IPs |
| Unused ports allowed | Larger attack surface | Remove unnecessary inbound rules |
| No network segmentation | Compromise may spread more easily | Separate resources by role or sensitivity |
| Missing network logs | Suspicious traffic may go unnoticed | Enable network logging where possible |

## Secure Configuration Checklist

- Deny inbound access by default.
- Allow only required ports.
- Restrict SSH/RDP to trusted IP ranges.
- Avoid exposing management services directly to the internet.
- Use network segmentation where appropriate.
- Review security rules regularly.
- Enable network monitoring and logging where available.

## Evidence

Screenshot to be added.

## Conclusion

Network security rules should minimize exposure and allow only necessary traffic. Applying restrictive inbound rules and monitoring access helps reduce cloud attack surface.
