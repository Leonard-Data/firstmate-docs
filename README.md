# Firstmate Docs

Documentation source for Firstmate knowledge in MSP Portal.

This repository explains how Firstmate works, how to set it up, and how to work with it well.
It is written for two readers at once:

- architecture engineers who need system boundaries, contracts, and failure modes
- junior developers who need plain setup steps, examples, and safe operating habits

## How this repository fits into MSP Portal

This repository owns its `docs/` content and `.docs-source.yml` metadata.
MSP Portal reads the metadata, syncs the Markdown, and publishes the section with shared navigation and search.

## Start here

- [Documentation overview](docs/README.md)
- [Firstmate core and soul](docs/concepts/firstmate-core.md)
- [System map](docs/architecture/system-map.md)
- [Setup guide](docs/guides/setup.md)
- [Working well with Firstmate](docs/guides/working-with-firstmate.md)

## Local content checks

```bash
find docs -name '*.md' -print
```

Keep pages small, linked, and portable.
Use relative links so the same content works in GitHub and MSP Portal.
