# SilentFlareGTOS

Markdown + GitHub Pages policy library for the SilentFlare Global Terms of Service.

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

- Write policy text in Markdown, not handwritten HTML.
- Keep one policy category per file.
- Use numbered clauses for terms that may need review or citation.
- Keep the restricted-region list in `docs/terms/restricted-regions.md` only.
- Keep KYC levels and verification rules in `docs/terms/kyc.md` only.
- Update `docs/index.md` when adding, removing, or renaming policy files.

## Legal review notice

This repository is an operational policy draft. It is not legal advice. Review it with a qualified legal professional before commercial use, especially for German law, European Union law, GDPR, consumer protection, sanctions, export control, and hosting-provider compliance.
