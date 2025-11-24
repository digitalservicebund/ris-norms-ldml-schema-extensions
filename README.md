# ris-norms-ldml-schema-extensions

This repo contains RIS-specific LegalDocML.de schema files (XSDs) that are being used by [ris-norms-migration](https://github.com/digitalservicebund/ris-norms-migration) and [ris-norms](https://github.com/digitalservicebund/ris-norms).

## Workflow

- **Source of Truth:** the `main` branch
- **Commits:** direct pushes to `main` are allowed
- **Notifications:** every commit to `main` posts to Slack `#1_neuris_norms-data`
- **WIP:** use separate branches for non-final changes
- **Integration:** teams decide how to include these files (e.g. with git submodules)
