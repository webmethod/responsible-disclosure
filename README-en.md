# Webmethod Coordinated Vulnerability Disclosure policy

**The effective date for the validity of these conditions is June 14th, 2024.**

At Webmethod we care about the security of our systems, our network, our products and our other services
important. We pay a lot of attention to this during development and maintenance. Of course it can still happen
that a weak spot is discovered. It would be nice if you let us know. We would prefer to hear this as soon as possible
possible, so that we can take measures to protect our customers.

This document describes the procedure we have drawn up for this.

## Report

Please send the report as soon as possible after discovering the vulnerability to **security-external@webmethod.nl**
Preferably encrypt the report with our PGP key: [6CB84814](pgp-security-external.asc)

## Rules

- Do not share information about the security issue with others until the issue is resolved.
- Provide information about how and when the vulnerability or malfunction occurs. Describe clearly how to solve this problem
  can be reproduced and provide information about the method used and the time of investigations.
- Use knowledge about the security problem responsibly. Do not perform actions that go beyond that
  necessary to demonstrate the security problem. Do not exploit the vulnerability and do not keep confidential ones
  data obtained through the vulnerability in the system.
- If desired, leave contact details (email address or telephone number) so that Webmethod can contact you about
  the assessment and progress of resolving the vulnerability. We also take anonymous reports seriously.
- Do not use physical attacks, DDOS attacks or social engineering.

Our CVD policy is not an invitation to actively scan our corporate network extensively for weaknesses. We monitor
our network itself. This means there is a good chance that a scan will be picked up and our team will investigate it.

## What does Webmethod do in the event of a Coordinated Vulnerability Disclosure?

If you report a suspected weakness in an IT system developed or used by Webmethod, then
we treat these in the following way:

- You will receive confirmation of receipt from Webmethod within three working days after submitting the report.
- Within three working days after confirmation of receipt, you will receive a response containing an assessment of the report and
  the expected date of resolution. We also aim to keep you informed in the meantime about the progress of
  solving the problem.
- Webmethod treats your report confidentially and does not share your data with third parties without your permission, except if
  this is required by law or by a court decision.
- Webmethod will determine together with you whether and how the reported problem will be reported. Notification only takes place
  after the problem is resolved. Webmethod will, if desired, include your name in notifications about the reported problem
  listed as discoverer.

## What can you not report?

This Responsible Disclosure scheme is not intended for reporting complaints. The scheme is also not intended for:

- Reporting that the website is unavailable.
- Reporting fake emails (phishing emails).
- Reporting fraud.

For these and other matters, please contact info@webmethod.nl

### Excluded systems

- status.webmethod.nl
- unifi.webmethod.nl
- ns{1-4}.webmethod.nl
- *.domeinen.webmethod.nl
- *.webmethodtelefonie.nl

### Excluded vulnerability types

- (D)DoS attacks
- Clickjacking on pages with no sensitive actions or requiring multiple user interactions.
- Cross-Site Request Forgery (CSRF) on unauthenticated forms or forms with no sensitive actions
- Attacks requiring MITM or physical access to a user's device
- Previously known vulnerable libraries without a working Proof of Concept
- Comma Separated Values (CSV) injection without demonstrating a vulnerability
- Missing best practices in SSL/TLS configuration
- Any activity that could lead to the disruption of our service (DoS) or a violation of the privacy of any user, employee or contractor of Webmethod or any of its affiliates or business partners
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS
- Rate limiting or bruteforce issues on non-authentication endpoints
- Missing best practices in Content Security Policy
- Missing Referrer Policy
- Missing Subresource Integrity directives
- Missing anti-clickjacking mechanisms
- Missing HttpOnly, Secure, SameSite cookie attributes
- Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.)
- Vulnerabilities only affecting users of outdated or unpatched browsers (more than 2 stable versions behind the latest released stable version)
- Software version disclosure / Banner identification issues / Descriptive error messages or headers (e.g. stack traces, application or server errors).
- Public Zero-day vulnerabilities that have had an official disclosure less than 1 month before are on a case by case basis.
- Tabnabbing
- Open redirect - unless an additional security impact can be demonstrated
- Issues that require unlikely user interaction
- Vulnerabilities that are already known (e.g. discovered and reported by other researchers or by an internal team)
- Self-XSS, which includes any payload entered by the victim
- Error messages without sensitive data
- Notifications from which the software we use can be derived
- Problems that require the use of very outdated operating systems, browsers or obsolete plugins
- Problems that are already known to us

This policy has been drawn up on the basis of the [Leidraad Coordinated Vulnerability Disclosure](https://www.ncsc.nl/documenten/publicaties/2019/mei/01/cvd-leidraad) of the NCSC (Dutch).

<hr>
<p align="center"><a href="https://www.webmethod.nl"><img src="https://www.webmethod.nl/assets/images/logo/logo.png"
height="20"></a></p>