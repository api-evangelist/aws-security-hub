# AWS Security Hub (aws-security-hub)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS Security Hub is a cloud security posture management (CSPM) service that aggregates, organizes, and prioritizes security findings from AWS services like Amazon GuardDuty, Inspector, and Macie, as well as supported third-party products. It continuously assesses your AWS environment against security standards such as AWS Foundational Security Best Practices, CIS, PCI DSS, and NIST. The Security Hub API and AWS SDKs provide access to findings, controls, insights, and automation rules using AWS Signature Version 4 authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aws-security-hub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aws-security-hub/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Security
- Cloud Security Posture Management
- Compliance
- Findings
- Threat Detection
- Cloud
- AWS

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### AWS Security Hub CSPM API

REST API for managing security standards, controls, findings, insights, automation rules, and member account configuration in AWS Security Hub. Requests are authenticated with AWS Signature Version 4 (SigV4) using AWS access keys or temporary IAM credentials.

- **Human URL:** [https://docs.aws.amazon.com/securityhub/1.0/APIReference/Welcome.html](https://docs.aws.amazon.com/securityhub/1.0/APIReference/Welcome.html)
- **Base URL:** `https://securityhub.us-east-1.amazonaws.com`

#### Tags

- Security
- CSPM
- Findings
- Compliance
- AWS

#### Properties

- [Documentation](https://docs.aws.amazon.com/securityhub/1.0/APIReference/Welcome.html)
- [User  Guide](https://docs.aws.amazon.com/securityhub/latest/userguide/what-is-securityhub.html)
- [Endpoints](https://docs.aws.amazon.com/general/latest/gr/sechub.html)
- [Postman Collection](collections/aws-security-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-security-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://aws.amazon.com/security-hub/)
- [Documentation](https://docs.aws.amazon.com/securityhub/)
- [Pricing](https://aws.amazon.com/security-hub/pricing/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
