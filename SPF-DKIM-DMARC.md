# SPF, DKIM and DMARC

Email authentication and anti-spoofing implementation.

## SPF

### Purpose

SPF validates which mail servers are authorized to send email on behalf of a domain.

### Common Tasks

- SPF record creation
- SPF record validation
- Third-party mail service configuration

## DKIM

### Purpose

DKIM digitally signs outgoing email messages.

### Common Tasks

- DKIM key generation
- DNS record publication
- Signature validation

## DMARC

### Purpose

DMARC provides reporting and enforcement policies for email authentication.

### Policies

- p=none
- p=quarantine
- p=reject

## Security Benefits

- Prevent email spoofing
- Reduce phishing attacks
- Improve email deliverability
- Improve domain reputation

## Tools

- MXToolbox
- Microsoft 365 Defender
- Google Admin Toolbox
