# Security Policy for AXBet

**App:** AXBet v15.0 Official  
**Package:** `com.axbet.app`  
**Publisher:** Allagosh Systems®

### Supported Versions

We actively support security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 15.0    | :white_check_mark: Official - Active Support |
| < 15.0  | :x: No longer supported |

Only the official build from this GitHub repository (`com.axbet.app`) is supported. Builds from other sources are not official and are not covered.

### Reporting a Vulnerability

If you discover a security vulnerability in the official AXBet app, please help us protect our users.

**DO NOT create a public GitHub issue for security problems.**

Instead, report privately:

**Email:** officialallagoshsystems@proton.me  
**Subject:** [SECURITY] AXBet v15.0 - Vulnerability Report

Please include:
1. Description of the vulnerability
2. Steps to reproduce
3. App version (v15.0) and device info
4. Your GitHub username (if you want credit)

### What to Expect

- We will acknowledge your email within 48 hours
- We will investigate and provide an update within 7 days
- If confirmed, we will release a patch and credit you in `/SECURITY.md` (unless you request anonymity)
- We follow responsible disclosure - please give us 90 days to fix before public disclosure

### Security Practices in v15.0

- Official data architecture - no in-app webviews scraping external sites
- HTTPS only - all network calls use TLS
- Atomic file writes to prevent data corruption
- No storage of passwords or financial data in app
- Firebase security rules enforced server-side
- No root detection bypass, no obfuscated mirrors

### Out of Scope

- Reports about unofficial clones of `com.axbet.app` on other stores
- Social engineering or physical access to device
- Vulnerabilities in third-party services (Firebase, Android OS itself)

Thank you for helping keep AXBet official and secure.

© 2026 Allagosh Systems®
