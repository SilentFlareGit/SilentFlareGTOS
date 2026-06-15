# SilentFlareGToS

**SilentFlareGToS** means **SilentFlare General Terms of Service**.

Markdown + GitHub Pages policy library for the SilentFlare personal blog General Terms of Service.

This repository is for a personal blog / personal web presence. It is not a VPS, hosting, payment, SaaS, or commercial infrastructure service agreement unless SilentFlare publishes a separate written product-specific agreement.

## Structure

```text
docs/
  _config.yml
  index.md
  terms/
    overview.md
    compliance.md
    restricted-regions.md
    kyc.md
    acceptable-use.md
    accounts-security.md
    service-availability.md
    payments-refunds.md
    data-privacy.md
    enforcement.md
    disclaimer.md
    contact.md
```

## Deploy with GitHub Pages

Use GitHub Pages with Jekyll:

```text
Settings -> Pages -> Build and deployment
Source: Deploy from a branch
Branch: main
Folder: /docs
```

After deployment, the site entry is the Pages URL for this repository. Each policy page has its own stable route, for example:

```text
/terms/overview/
/terms/restricted-regions/
/terms/kyc/
/terms/acceptable-use/
/terms/data-privacy/
```

## Editing rules

- Use `SilentFlareGToS` as the canonical short name.
- Use `SilentFlare General Terms of Service` as the canonical full name.
- Write policy text in Markdown, not handwritten HTML.
- Keep one policy category per file.
- Keep the documents suitable for a personal blog, not a commercial hosting platform.
- Keep the controlled-access policy in `docs/terms/restricted-regions.md` only.
- Keep the limited KYC1 rule in `docs/terms/kyc.md` only.
- Do not add KYC2, KYC3, proof-of-address, source-of-funds, or commercial onboarding unless the site changes into a commercial service.
- Update `docs/index.md` when adding, removing, or renaming policy files.

## Legal review notice

This repository is an operational policy draft for a personal blog. It is not legal advice. Review it with a qualified legal professional before relying on it for commercial use, identity verification, controlled-access enforcement, GDPR compliance, or German/EU internet-law compliance.
