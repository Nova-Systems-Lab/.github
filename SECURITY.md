# Security Policy

Nova Systems Lab takes the security of its projects and users seriously.

We appreciate responsible reports from security researchers, developers, testers, and community members.

## Supported Versions

Security support is generally provided for:

- The latest stable release
- The latest actively maintained development version
- Other versions explicitly identified as supported by the relevant project

Older releases, archived repositories, prototypes, and experimental builds may not receive security updates.

Each project may publish its own supported-version table when releases become available.

## Reporting a Vulnerability

Do not report suspected security vulnerabilities through:

- Public GitHub Issues
- Public GitHub Discussions
- Public Discord channels
- Social media
- Public Pull Requests

Use GitHub's private vulnerability-reporting feature for the affected repository when it is available.

To report privately:

1. Open the affected repository.
2. Go to the **Security** tab.
3. Select **Advisories**.
4. Choose **Report a vulnerability**.
5. Provide the requested details.

If private vulnerability reporting is not available, email:

novasystemslab@gmail.com

Use a clear subject such as:

Security Report: [Project Name]

Do not send exploit details into a public Discord message.

## What to Include

Please provide as much of the following as possible:

- The affected project
- Affected version, commit, or branch
- A clear description of the vulnerability
- Steps to reproduce it
- Required conditions or permissions
- Potential impact
- Proof-of-concept details, where safe
- Suggested fixes or mitigations, if known
- Whether the issue has been publicly disclosed elsewhere

Remove unrelated personal information and secrets from logs or screenshots.

## Responsible Disclosure

Please:

- Give maintainers reasonable time to investigate and respond
- Avoid public disclosure before a fix or mitigation is available
- Avoid accessing, modifying, or deleting data that does not belong to you
- Avoid disrupting services or users
- Use the minimum testing necessary to demonstrate the issue
- Do not use a vulnerability for personal gain, extortion, or harm

## Response Process

After receiving a report, maintainers will try to:

1. Acknowledge the report
2. Review and reproduce the issue
3. Assess severity and impact
4. Develop a fix or mitigation
5. Coordinate disclosure where appropriate
6. Publish an advisory or release when ready

Nova Systems Lab is an independent open-source organization, so response times may vary. Critical reports will be prioritized when possible.

## Public Disclosure

Please coordinate public disclosure with the maintainers.

Where appropriate, the reporter may be credited in:

- A GitHub Security Advisory
- Release notes
- Project documentation
- Acknowledgements

Credit will only be given with the reporter's consent.

## Out of Scope

The following are generally not considered security vulnerabilities unless they create a meaningful security impact:

- Missing features
- General bugs without security consequences
- Issues affecting unsupported versions
- Social-engineering attacks against individual community members
- Denial-of-service testing that causes disruption
- Reports based only on automated scanner output without validation
- Problems caused by intentionally disabling security controls
- Vulnerabilities in unrelated third-party services
- Physical access attacks
- Self-XSS without impact on another user
- Missing security headers without a demonstrated risk

## Safe Harbour

Nova Systems Lab will not pursue action against researchers who:

- Act in good faith
- Follow this policy
- Avoid harming users or systems
- Avoid unnecessary access to data
- Report findings privately
- Allow reasonable time for remediation

This safe-harbour statement does not authorize violations of applicable law or third-party terms.

## Security Updates

Security fixes may be delivered through:

- New releases
- Patched development builds
- GitHub Security Advisories
- Updated documentation
- Temporary mitigations

Users should keep projects and dependencies updated and only download releases from official Nova Systems Lab repositories and channels.