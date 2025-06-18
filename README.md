# ris-norms-ldml-schema-extensions

This repo contains RIS-specific LegalDocML.de schema files (XSDs) that are being used by [ris-norms-migration](https://github.com/digitalservicebund/ris-norms-migration) and [ris-norms](https://github.com/digitalservicebund/ris-norms).

## Proposal

As this repo is not in use yet and we first want to build a common understanding of how to work with this shared repo, here is a proposal:

- each team can decide for themselves how they include the schema files e.g. using git submodules
- the code on `main` is the single source of truth
- each team can directly push to `main`
- if necessary teams can work on separate branches if they have changes that are still work in progress
