# AstroDocs

Unofficial, dated, offline editions of the official [Astro documentation](https://docs.astro.build/) in English.

The documentation is provided in multiple formats:

- Markdown
- Plain text
- Standalone HTML
- PDF
  - All-in-one edition
  - Tutorial
  - Guide
  - Reference
  - Ecosystem

## Latest edition

**Documentation snapshot:** 2026-07-18  
**Language:** English  
**Source repository:** [withastro/docs](https://github.com/withastro/docs)  
**Source commit:** [`0eaddbeca24fd7a45470f0701b3071f86a238b56`](https://github.com/withastro/docs/commit/0eaddbeca24fd7a45470f0701b3071f86a238b56)

### Downloads

| Format | File |
|---|---|
| Markdown — all in one | [Astro-Docs-English-2026-07-18-All-in-One.md](20270718/TEXT/Astro-Docs-English-2026-07-18-All-in-One.md) |
| Plain text — all in one | [Astro-Docs-English-2026-07-18-All-in-One.txt](20270718/TEXT/Astro-Docs-English-2026-07-18-All-in-One.txt) |
| HTML — all in one | [Astro-Docs-English-2026-07-18-All-in-One.html](20270718/HTML/Astro-Docs-English-2026-07-18-All-in-One.html) |
| PDF — all in one | [Astro-Docs-English-2026-07-18-All-in-One.pdf](20270718/PDF/Astro-Docs-English-2026-07-18-All-in-One.pdf) |
| PDF — Tutorial | [Astro-Docs-English-2026-07-18-01-Tutorial.pdf](20270718/PDF/Astro-Docs-English-2026-07-18-01-Tutorial.pdf) |
| PDF — Guide | [Astro-Docs-English-2026-07-18-02-Guide.pdf](20270718/PDF/Astro-Docs-English-2026-07-18-02-Guide.pdf) |
| PDF — Reference | [Astro-Docs-English-2026-07-18-03-Reference.pdf](20270718/PDF/Astro-Docs-English-2026-07-18-03-Reference.pdf) |
| PDF — Ecosystem | [Astro-Docs-English-2026-07-18-04-Ecosystem.pdf](20270718/PDF/Astro-Docs-English-2026-07-18-04-Ecosystem.pdf) |

## Coverage

Each edition includes all four primary documentation areas:

1. **Tutorial**
2. **Guide**
3. **Reference**
4. **Ecosystem**

The all-in-one editions combine these sections into a single document. The PDF release also provides each section as an individual volume.

## Repository structure

```text
AstroDocs/
├── README.md
├── LICENSE
└── 20270718/
    ├── HTML/
    │   └── Astro-Docs-English-2026-07-18-All-in-One.html
    ├── TEXT/
    │   ├── Astro-Docs-English-2026-07-18-All-in-One.md
    │   ├── Astro-Docs-English-2026-07-18-All-in-One.txt
    │   └── Astro-Docs-English-2026-07-18-All-in-One.manifest.json
    ├── PDF/
    │   ├── Astro-Docs-English-2026-07-18-All-in-One.pdf
    │   ├── Astro-Docs-English-2026-07-18-01-Tutorial.pdf
    │   ├── Astro-Docs-English-2026-07-18-02-Guide.pdf
    │   ├── Astro-Docs-English-2026-07-18-03-Reference.pdf
    │   └── Astro-Docs-English-2026-07-18-04-Ecosystem.pdf
    └── metadata/
        ├── build-manifest.json
        ├── source-files.json
        ├── changes-since-previous.md
        └── checksums.sha256
```

## Versioning

Each release is stored in a date-coded directory. Every edition records:

- Build date
- Astro documentation source commit
- Included English source files
- File checksums
- Changes since the previous edition

This makes it possible to compare documentation snapshots and rebuild the books when the upstream Astro documentation changes.

## Purpose

This repository provides convenient offline and archival editions of the Astro documentation for:

- Offline reading
- Full-text searching
- Printing
- E-readers and document-management systems
- Comparing dated documentation releases
- Preserving a reproducible documentation snapshot

## Attribution and license

The documentation content originates from the official [`withastro/docs`](https://github.com/withastro/docs) repository and its open-source contributors.

The upstream documentation repository is distributed under the MIT License. The applicable copyright notice and license must remain included with redistributed editions. See the repository's [`LICENSE`](LICENSE) file.

Generated formatting, compilation scripts, covers, and release metadata do not change the ownership or licensing of the original Astro documentation content.

## Disclaimer

This is an unofficial community publication.

It is not affiliated with, sponsored by, approved by, or endorsed by Astro Technology Company or the official Astro documentation team.

Astro, its documentation, trademarks, and related materials belong to their respective owners.
