# Cybersecurity Policy

Protecting our systems, our clients' data and our intellectual property is
everyone's job: founder, contractor and intern alike.

## Authentication and access

- **Strong, unique passwords** everywhere, held in a password manager,
  never reused across services.
- **Two-factor authentication is mandatory** on every company account:
  email, GitHub, trackers, cloud consoles, financial systems.
- **Least privilege.** Access is granted by role and necessity, and removed
  when the need ends.
- **Passwords are never shared.** Not with colleagues, not with founders,
  not with support. No legitimate Cuesoft process asks for your password:
  treat any such request as an incident and report it.

## Credentials and secrets

- Secrets (API keys, tokens, service credentials) live in the approved
  secret manager, never in code, never in repositories, never in chat.
- **Nothing sensitive travels through WhatsApp.** Client groups are for
  coordination; credentials and access requests go through the engagement's
  formal email channel.
- Rotations and access changes on production systems go through the
  engagement lead: unauthorised changes are a violation.

## Data storage

- Confidential files and client data live only in approved company systems.
  Personal cloud accounts and personal USB storage are prohibited for
  company data.
- Sensitive data is encrypted in storage and in transit.

## Devices and networks

- Keep your work device's OS patched, disk encrypted, screen locked, and
  protected with up-to-date security tooling (see [BYOD](../byod/)).
- Use secure networks; on public Wi-Fi, use a VPN.
- A lost or stolen device that touched company or client data is reported
  **immediately** so access can be revoked.

## Threats and incidents

- Be suspicious of unexpected links, attachments and urgent requests:
  phishing is the front door of most breaches.
- Report suspected phishing, malware, breaches or unusual account activity
  immediately to [hello@cuesoft.io](mailto:hello@cuesoft.io). Fast reports
  contain damage; delayed ones compound it. Personal-data incidents also
  follow the [data-protection policy](../data-protection/) clock.

## Who this applies to and what it covers

It applies to everyone with access to Cuesoft or client systems, data or
accounts: the founders, contractors and interns, and anyone else given
access for as long as they have it. It covers accounts, credentials,
devices, networks, data, code, third-party and AI tools, and how
incidents are reported.

## Acceptable use of company accounts, systems and data

- Use company accounts and systems only for the work they were given for.
  They are not for personal projects, other clients' work or anything
  unlawful.
- Your access is personal to you. Do not let anyone else use it, and do not
  use anyone else's.
- Do not try to reach systems, data or accounts you have not been given, do
  not test or probe company or client systems without written approval, and
  do not bypass or disable a security control.
- Do not install or connect software, extensions or services that touch
  company or client data unless they are approved.
- Do not put personal data, credentials, client data or confidential
  information into public repositories, public pastebins, AI tools, or any
  third-party tool that has not been approved in writing.
- Do not commit secrets, `.env` files, keys or personal data to any
  repository, public or private. If one is committed, treat it as exposed:
  report it at once and rotate it.
- Use only legitimately licensed software for company work.

## Monitoring of company systems

This policy does not authorise Cuesoft to look into your personal device,
your personal accounts or your personal messages. Company accounts and the
data in them belong to Cuesoft, so use them on the footing that the company
can review what is held in them.
<!-- TODO(owner): confirm what is monitored or logged on company systems, who can see it, and how long it is kept; the handbook does not say Cuesoft monitors, so correct or remove this section to match -->

## Lost or stolen devices and credentials

Report a lost or stolen device, a lost or exposed password, token or key,
and any account you think someone else has used, **immediately** to
[hello@cuesoft.io](mailto:hello@cuesoft.io). Do not wait to be sure. We will
suspend or revoke access while we check. Reporting fast is never held
against you; hiding it is.

## Incident response

1. You report. Do not delete evidence, and do not try to fix it quietly.
2. We contain it: revoke or suspend access, rotate credentials, and pause
   affected work.
3. We establish what was exposed. If personal data is involved, the
   [data-protection policy](../data-protection/) clock runs, and the
   privacy policy's [breach notification](https://privacy.cuesoft.io/handling/breach/)
   commits us to notify the authorities and affected people where the law
   requires.
4. We record the incident and what changes.

The privacy policy's [security page](https://privacy.cuesoft.io/handling/security/)
describes our safeguards.

## Returning access

At the end of an engagement, access is revoked the same day: see
[onboarding and offboarding](../../people/onboarding-offboarding/). Return
or remove company data and credentials as the [BYOD policy](../byod/) says.
Where a risk is found, access can be suspended earlier.

## Responsibility

You are responsible for the security of your own devices and accounts. We do
not make you personally liable beyond what your signed agreement and the law
provide. Careless handling is a violation, and a deliberate breach, such as
sharing credentials or leaking data, is severe misconduct: see
[violations](../../people/violation/).

## Reporting a concern, records, law and changes

Report policy concerns to [hello@cuesoft.io](mailto:hello@cuesoft.io) or the
COO, and if it concerns them to the CEO or another founder, as
[the policies page](../) explains. No one is penalised for a good-faith
report, and a knowingly false one is a violation. Records of incidents and
reports are kept as the [rules for every policy](../#records) say.
Local law applies on top of this policy, the signed agreement prevails where
they differ, and the policy changes the way the handbook does: see
[changing a policy](../#changing-a-policy).
