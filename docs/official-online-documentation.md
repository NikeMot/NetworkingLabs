# Official Online Documentation

## Purpose

This document adds an online documentation layer to the 24-lab NetworkingLabs curriculum.

Books provide durable concepts and deep foundations. Official online documentation provides current command syntax, platform behaviour, product features, and operational best practice.

Every generated lab should include both where relevant:

```text
Book chapter = foundation and mental model
Official online documentation = current implementation detail
Lab evidence = proof that the learner can apply both
```

## Rule

When a lab uses a tool, platform, vendor feature, command, API, or cloud service, check official online documentation where possible.

Prefer:

1. Official project documentation
2. Vendor documentation
3. Maintainer documentation
4. Operating system manual pages
5. Standards/RFCs where relevant

Avoid relying on old blog posts, forum snippets, or copied commands without verifying against current official docs.

## Documentation freshness requirement

Each lab write-up should record:

- online documentation consulted
- date checked
- feature, command, or behaviour verified
- any version-specific note
- whether the lab output matched the documentation

## Core online documentation sources

| Area | Official source | Used for |
| --- | --- | --- |
| curl | https://curl.se/docs/manpage.html | HTTP checks, API checks, headers, redirects, TLS, timing, troubleshooting |
| Wireshark | https://www.wireshark.org/docs/wsug_html_chunked/ | packet capture analysis, filtering, protocol inspection |
| Linux `ip` command | https://man7.org/linux/man-pages/man8/ip.8.html | interfaces, routes, addresses, network state |
| OpenSSL `s_client` | https://docs.openssl.org/master/man1/openssl-s_client/ | TLS diagnostics, certificate checks, handshake troubleshooting |
| Microsoft `Test-NetConnection` | https://learn.microsoft.com/en-us/powershell/module/nettcpip/test-netconnection | Windows connectivity and port testing |
| Azure Well-Architected Framework | https://learn.microsoft.com/en-us/azure/well-architected/ | reliability, cost optimisation, security, operational excellence |
| Prometheus | https://prometheus.io/docs/introduction/overview/ | metrics, alerting, SRE observability concepts |
| Grafana | https://grafana.com/docs/ | dashboards, visualisation, alerting, observability workflows |
| NetBox | https://docs.netbox.dev/ | CMDB/source-of-truth modelling, inventory, IPAM, dependencies |
| Palo Alto Networks documentation | https://docs.paloaltonetworks.com/ | zone-based firewall policy, security rules, NAT, logging concepts |
| Cisco documentation | https://www.cisco.com/c/en/us/support/index.html | routing, switching, wireless, firewall, troubleshooting references |
| Juniper documentation | https://www.juniper.net/documentation/ | routing, switching, firewall policy, Junos concepts |
| Google SRE books | https://sre.google/books/ | SRE principles, SLIs, SLOs, error budgets, incident response, toil |

## Where online docs are mandatory

Use official online docs in these areas:

- command syntax that may change between versions
- cloud services and managed platform behaviour
- firewall vendor concepts
- observability tooling
- automation APIs
- TLS/certificate behaviour
- security controls
- SRE terminology and practices
- Windows PowerShell networking commands
- Linux networking commands

## Lab template requirement

Every generated lab should include an `Online documentation checked` subsection.

Minimum format:

| Documentation | Why checked | Date checked | Version or scope note |
| --- | --- | --- | --- |
| Official source name | Command/tool/platform behaviour | YYYY-MM-DD | Version, OS, product, or lab scope |

## Break/fix relevance

Online documentation is especially important in break/fix work.

Use it to verify:

- expected command behaviour
- option syntax
- known limitations
- current platform defaults
- official troubleshooting guidance
- security warnings
- version-specific behaviour

## AI rule

AI can help locate or summarise official documentation, but the lab should still cite or name the official source used.

AI output is not a substitute for checking official documentation.