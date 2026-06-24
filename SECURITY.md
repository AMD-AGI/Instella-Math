# Security Policy

## Reporting a Vulnerability

We take the security of Instella-Math seriously. If you believe you have found a
security vulnerability, please report it to us privately. **Do not report security
vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, please use GitHub's Private Vulnerability Reporting:

1. Go to the **Security** tab of this repository.
2. Click **Report a vulnerability** (or visit
   [`/security/advisories/new`](../../security/advisories/new)).
3. Provide a clear description of the issue, including steps to reproduce, the
   affected component or version, and any potential impact you have identified.

## What to Expect

- We will acknowledge receipt of your report as soon as we are able.
- We will investigate and keep you informed of our progress.
- Once the issue is resolved, we will coordinate disclosure with you.

## Supported Versions

Security updates are applied to the latest release on the `main` branch. Older
revisions are not guaranteed to receive fixes.

## Scope

This policy covers the code maintained in this repository. Vulnerabilities in
third-party dependencies should be reported to the respective upstream projects,
though we welcome a heads-up so we can update affected dependencies.

## Secrets & Sensitive Data

Never include credentials, API keys, tokens, or other sensitive data in issues,
pull requests, or commits. If you discover that a secret has been committed,
report it privately using the process above so it can be rotated.
