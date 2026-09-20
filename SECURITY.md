# Security Policy

Eplayment Corporation operates payment systems under a license from the Bangko
Sentral ng Pilipinas. We take reports about our software and services seriously
and we would rather hear about a problem early than read about it later.

## Scope

This policy covers the repositories in this organization and the services they
run, including the Weav, Epaygames, and PIXEL products and their public
endpoints.

Out of scope:

- Reports produced solely by an automated scanner, with no demonstrated impact
- Missing security headers or TLS configuration with no exploitable consequence
- Social engineering, phishing, or physical attacks against our staff or offices
- Denial of service, load testing, or anything that degrades service for real
  users
- Vulnerabilities in third-party services we consume, which should go to that
  vendor
- Findings that require a compromised device or a privileged account to reproduce

## Reporting a vulnerability

**Do not open a public issue.** Public disclosure before a fix is available puts
real customers at risk.

Report privately through GitHub's private vulnerability reporting, using the
**Report a vulnerability** button on the Security tab of the affected repository.
If that is unavailable, or the issue concerns a service rather than a repository,
email security@eplayment.co.

Please include:

- What the issue is and where you found it
- Steps to reproduce, with a proof of concept if you have one
- What an attacker could do with it
- Anything we need to clean up afterward, such as test accounts or records you
  created

Write in English or Filipino. Either is fine.

## What happens next

We acknowledge receipt and tell you who is handling it. We will keep you updated
as we investigate, and we will let you know when a fix ships.

If a report turns out to be a duplicate or out of scope, we will say so plainly
rather than leaving you waiting.

## Testing boundaries

If you are looking for issues rather than stumbling on one:

- Use your own accounts and your own test data
- Never access, modify, or retain another person's data, and stop as soon as you
  realize you can
- No automated scanning against production, and no load or stress testing
- Never move real money. Test with the smallest amount that demonstrates the
  issue, and tell us about any transaction you create

Card data, personal data, and transaction records belong to our customers. If you
encounter any, stop, do not download it, and tell us what you saw.

## Good faith

We will not pursue legal action against anyone who follows this policy, reports
promptly, and gives us reasonable time to fix the issue before disclosing it. If
you are unsure whether something is in scope, ask first.

We do not currently run a paid bug bounty program. We do acknowledge reporters
who ask to be credited, once a fix has shipped.

## For our staff

Report a lost device, a suspected compromise, or any possible data exposure
immediately through the internal incident channel, not here. Prompt disclosure is
treated as a mitigating factor.