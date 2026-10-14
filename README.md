# ZULIP

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-chat_platforms-lightgrey)

> Anticloud-hardened packaging of the upstream project `ZULIP` in category **CHAT PLATFORMS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CHAT PLATFORMS · **Upstream:** https://github.com/zulip/zulip · **Upstream pin:** `de2dbb995b7072a169320f522b2571587ac271a7` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Zulip overview

[Zulip](https://zulip.com) is an open-source organized team chat app with unique
[topic-based threading][why-zulip] that combines the best of email and chat to
make remote work productive and delightful. Fortune 500 companies, [leading open
source projects][rust-case-study], and thousands of other organizations use
Zulip every day. Zulip is the only [modern team chat app][features] that is
designed for both live and asynchronous conversations.

Zulip is built by a distributed community of developers from all around the
world, with 99+ people who have each contributed 100+ commits. With
over 1,500 contributors merging over 500 commits a month, Zulip is the
largest and fastest growing open source team chat project.

Come find us on the [development community chat](https://zulip.com/development-community/)!

[![GitHub Actions build status](https://github.com/zulip/zulip/actions/workflows/zulip-ci.yml/badge.svg)](https://github.com/zulip/zulip/actions/workflows/zulip-ci.yml?query=branch%3Amain)
[![coverage status](https://img.shields.io/codecov/c/github/zulip/zulip/main.svg)](https://codecov.io/gh/zulip/zulip)
[![Mypy coverage](https://img.shields.io/badge/mypy-100%25-green.svg)][mypy-coverage]
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![GitHub release](https://img.shields.io/github/release/zulip/zulip.svg)](https://github.com/zulip/zulip/releases/latest)
[![docs](https://readthedocs.org/projects/zulip/badge/?version=latest)](https://zulip.readthedocs.io/en/latest/)
[![Zulip chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://chat.zulip.org)
[![Bluesky](https://img.shields.io/badge/bluesky-@zulip.bsky.social-blue.svg?style=flat)](https://bsky.app/profile/zulip.bsky.social)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/zulip)](https://github.com/sponsors/zulip)

[mypy-coverage]: https://blog.zulip.org/2016/10/13/static-types-in-python-oh-mypy/
[why-zulip]: https://zulip.com/why-zulip/
[rust-case-study]: https://zulip.com/case-studies/rust/
[features]: https://zulip.com/features/

## Getting started

- **Contributing code**. Check out our [guide for new
  contributors](https://zulip.readthedocs.io/en/latest/contributing/contributing.html)
  to get started. We have invested in making Zulip’s code highly
  readable, thoughtfully tested, and easy to modify. Beyond that, we
  have written an extraordinary 185K words of documentation for Zulip
  contributors.

- **Contributing non-code**. [Report an
  issue](https://zulip.readthedocs.io/en/latest/contributing/reporting-bugs.html),
  [translate](https://zulip.readthedocs.io/en/latest/translating/translating.html)
  Zulip into your language, or [give us
  feedback](https://zulip.readthedocs.io/en/latest/contributing/suggesting-features.html).
  We'd love to hear from you, whether you've been using Zulip for years, or are just
  trying it out for the first time.

- **Checking Zulip out**. The best way to see Zulip in action is to [drop
  by](https://chat.zulip.org/?show_try_zulip_modal) the Zulip development
  community (no account required). We also recommend reading about Zulip's
  [unique approach](https://zulip.com/why-zulip/) to organizing conversations.

- **Running a Zulip server**. Self-host Zulip directly on Ubuntu or Debian
  Linux, in [Docker](https://github.com/zulip/docker-zulip), or with prebuilt
  images for [Digital Ocean](https://marketplace.digitalocean.com/apps/zulip) and
  [Render](https://render.com/docs/deploy-zulip).
  Learn more about [self-hosting Zulip](https://zulip.com/self-hosting/).

- **Using Zulip without setting up a server**. Learn about [Zulip
  Cloud](https://zulip.com/zulip-cloud/) hosting options. Zulip sponsors free [Zulip
  Cloud Standard](https://zulip.com/plans/) for hundreds of worthy
  organizations, including [fellow open-source
  projects](https://zulip.com/for/open-source/).

- **Participating in [outreach
  programs](https://zulip.readthedocs.io/en/latest/contributing/contributing.html#outreach-programs)**
  like [Google Summer of Code](https://developers.google.com/open-source/gsoc/).

- **Supporting Zulip**. Learn about all the ways you can [support
  Zulip](https://zulip.com/help/support-zulip-project), including contributing
  financially, and helping others discover it.

You may also be interested in reading our [blog](https://blog.zulip.org/), and
following us on [LinkedIn](https://www.linkedin.com/company/zulip-project/),
[Mastodon](https://fosstodon.org/@zulip), and [X](https://x.com/zulip).

Zulip is distributed under the
[Apache 2.0](https://github.com/zulip/zulip/blob/main/LICENSE) license.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `analytics/`, `api_docs/`, `confirmation/`, `corporate/`, `locale/`, `patches/`, `pgroonga/`, `puppet/`, `scripts/`, `starlight_help/`, `static/`, `templates/`
- Snapshot size: **6628 files**, **327251 lines of code** (measured; see Benchmarks)
- Primary languages: `.json` (1745), `.py` (1070), `.png` (485), `.hbs` (472), `.ts` (470), `.mdx` (464)
- Upstream commit pinned for this packaging: `de2dbb995b7072a169320f522b2571587ac271a7`

---

## Installation

[![coverage status](https://img.shields.io/codecov/c/github/zulip/zulip/main.svg)](https://codecov.io/gh/zulip/zulip)
[![Mypy coverage](https://img.shields.io/badge/mypy-100%25-green.svg)][mypy-coverage]
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![GitHub release](https://img.shields.io/github/release/zulip/zulip.svg)](https://github.com/zulip/zulip/releases/latest)
[![docs](https://readthedocs.org/projects/zulip/badge/?version=latest)](https://zulip.readthedocs.io/en/latest/)
[![Zulip chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://chat.zulip.org)
[![Bluesky](https://img.shields.io/badge/bluesky-@zulip.bsky.social-blue.svg?style=flat)](https://bsky.app/profile/zulip.bsky.social)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/zulip)](https://github.com/sponsors/zulip)

[mypy-coverage]: https://blog.zulip.org/2016/10/13/static-types-in-python-oh-mypy/
[why-zulip]: https://zulip.com/why-zulip/
[rust-case-study]: https://zulip.com/case-studies/rust/
[features]: https://zulip.com/features/

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

- **Contributing code**. Check out our [guide for new
  contributors](https://zulip.readthedocs.io/en/latest/contributing/contributing.html)
  to get started. We have invested in making Zulip’s code highly
  readable, thoughtfully tested, and easy to modify. Beyond that, we
  have written an extraordinary 185K words of documentation for Zulip
  contributors.

- **Contributing non-code**. [Report an
  issue](https://zulip.readthedocs.io/en/latest/contributing/reporting-bugs.html),
  [translate](https://zulip.readthedocs.io/en/latest/translating/translating.html)
  Zulip into your language, or [give us
  feedback](https://zulip.readthedocs.io/en/latest/contributing/suggesting-features.html).
  We'd love to hear from you, whether you've been using Zulip for years, or are just
  trying it out for the first time.

- **Checking Zulip out**. The best way to see Zulip in action is to [drop
  by](https://chat.zulip.org/?show_try_zulip_modal) the Zulip development
  community (no account required). We also recommend reading about Zulip's
  [unique approach](https://zulip.com/why-zulip/) to organizing conversations.

- **Running a Zulip server**. Self-host Zulip directly on Ubuntu or Debian
  Linux, in [Docker](https://github.com/zulip/docker-zulip), or with prebuilt
  images for [Digital Ocean](https://marketplace.digitalocean.com/apps/zulip) and
  [Render](https://render.com/docs/deploy-zulip).
  Learn more about [self-hosting Zulip](https://zulip.com/self-hosting/).

- **Using Zulip without setting up a server**. Learn about [Zulip
  Cloud](https://zulip.com/zulip-cloud/) hosting options. Zulip sponsors free [Zulip
  Cloud Standard](https://zulip.com/plans/) for hundreds of worthy
  organizations, including [fellow open-source
  projects](https://zulip.com/for/open-source/).

- **Participating in [outreach
  programs](https://zulip.readthedocs.io/en/latest/contributing/contributing.html#outreach-programs)**
  like [Google Summer of Code](https://developers.google.com/open-source/gsoc/).

- **Supporting Zulip**. Learn about all the ways you can [support
  Zulip](https://zulip.com/help/support-zulip-project), including contributing
  financially, and helping others discover it.

You may also be interested in reading our [blog](https://blog.zulip.org/), and
following us on [LinkedIn](https://www.linkedin.com/company/zulip-project/),
[Mastodon](https://fosstodon.org/@zulip), and [X](https://x.com/zulip).

Zulip is distributed under the
[Apache 2.0](https://github.com/zulip/zulip/blob/main/LICENSE) license.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

contributors.

- **Contributing non-code**. [Report an
  issue](https://zulip.readthedocs.io/en/latest/contributing/reporting-bugs.html),
  [translate](https://zulip.readthedocs.io/en/latest/translating/translating.html)
  Zulip into your language, or [give us
  feedback](https://zulip.readthedocs.io/en/latest/contributing/suggesting-features.html).
  We'd love to hear from you, whether you've been using Zulip for years, or are just
  trying it out for the first time.

- **Checking Zulip out**. The best way to see Zulip in action is to [drop
  by](https://chat.zulip.org/?show_try_zulip_modal) the Zulip development
  community (no account required). We also recommend reading about Zulip's
  [unique approach](https://zulip.com/why-zulip/) to organizing conversations.

- **Running a Zulip server**. Self-host Zulip directly on Ubuntu or Debian
  Linux, in [Docker](https://github.com/zulip/docker-zulip), or with prebuilt
  images for [Digital Ocean](https://marketplace.digitalocean.com/apps/zulip) and
  [Render](https://render.com/docs/deploy-zulip).
  Learn more about [self-hosting Zulip](https://zulip.com/self-hosting/).

- **Using Zulip without setting up a server**. Learn about [Zulip
  Cloud](https://zulip.com/zulip-cloud/) hosting options. Zulip sponsors free [Zulip
  Cloud Standard](https://zulip.com/plans/) for hundreds of worthy
  organizations, including [fellow open-source
  projects](https://zulip.com/for/open-source/).

- **Participating in [outreach
  programs](https://zulip.readthedocs.io/en/latest/contributing/contributing.html#outreach-programs)**
  like [Google Summer of Code](https://developers.google.com/open-source/gsoc/).

- **Supporting Zulip**. Learn about all the ways you can [support
  Zulip](https://zulip.com/help/support-zulip-project), including contributing
  financially, and helping others discover it.

You may also be interested in reading our [blog](https://blog.zulip.org/), and
following us on [LinkedIn](https://www.linkedin.com/company/zulip-project/),
[Mastodon](https://fosstodon.org/@zulip), and [X](https://x.com/zulip).

Zulip is distributed under the
[Apache 2.0](https://github.com/zulip/zulip/blob/main/LICENSE) license.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | 6628 |
| Lines of code | 327251 |
| Dependency references | 196 |
| Dependencies by ecosystem | npm: 196 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @babel/core | ^8.0.1 | package.json |
| npm | @babel/preset-env | ^8.0.2 | package.json |
| npm | @babel/preset-typescript | ^8.0.1 | package.json |
| npm | @date-fns/tz | ^1.4.1 | package.json |
| npm | @fontsource-variable/open-sans | ^5.0.9 | package.json |
| npm | @formatjs/intl | ^6.1.2 | package.json |
| npm | @gfx/zopfli | ^1.0.15 | package.json |
| npm | @koa/bodyparser | ^6.0.0 | package.json |
| npm | @prometheus-io/client | ^0.16.1 | package.json |
| npm | @sentry/browser | ^11.1.0 | package.json |
| npm | @sentry/core | ^11.1.0 | package.json |
| npm | @sinonjs/fake-timers | ^15.1.1 | package.json |
| npm | @types/postcss-import | ^14.0.3 | package.json |
| npm | @uppy/core | ^6.1.0 | package.json |
| npm | @uppy/dashboard | ^6.0.0 | package.json |
| ... | (181 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

Cloud Standard](https://zulip.com/plans/) for hundreds of worthy
  organizations, including [fellow open-source
  projects](https://zulip.com/for/open-source/).

- **Participating in [outreach
  programs](https://zulip.readthedocs.io/en/latest/contributing/contributing.html#outreach-programs)**
  like [Google Summer of Code](https://developers.google.com/open-source/gsoc/).

- **Supporting Zulip**. Learn about all the ways you can [support
  Zulip](https://zulip.com/help/support-zulip-project), including contributing
  financially, and helping others discover it.

You may also be interested in reading our [blog](https://blog.zulip.org/), and
following us on [LinkedIn](https://www.linkedin.com/company/zulip-project/),
[Mastodon](https://fosstodon.org/@zulip), and [X](https://x.com/zulip).

Zulip is distributed under the
[Apache 2.0](https://github.com/zulip/zulip/blob/main/LICENSE) license.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing guide

Welcome! This is a step-by-step guide on how to get started contributing code to
the [Zulip](https://zulip.com/) organized team chat [open-source
project](https://github.com/zulip). Thousands of people use Zulip every day, and
your work on Zulip will have a meaningful impact on their experience. We hope
you'll join us!

To learn about ways to contribute without writing code, please see our
suggestions for how you can [support the Zulip
project](https://zulip.com/help/support-zulip-project).

## How to use Zulip's documentation for contributors

::: note

**Reading and following our written guidelines** to the very best of your ability is
the only way to become a successful Zulip contributor.

:::

Zulip has a documentation-based approach to onboarding new contributors. As you
are getting started, this page will be your go-to for figuring out what to do
next. You will also explore other guides, learning about how to put together
your first pull request, diving into [Zulip's
subsystems](https://zulip.readthedocs.io/en/latest/subsystems/index.html), and
much more.

We hope you'll find this process to be a great learning experience. If you
_aren't_ excited to learn from our series of contributor guides, then Zulip is
not the right project for you.

Please read the following sections of this guide at the times described (or
earlier). And of course, use the [Zulip apps](https://zulip.com/apps/) during
the whole process!

**Prior to picking up your first issue**:

- [How to be a successful contributor](#how-to-be-a-successful-contributor)
- [AI use policy and guidelines](#ai-use-policy-and-guidelines)
- [Join the Zulip development community](#join-the-zulip-development-community)
- [Getting started](#getting-started)
- [Finding an issue to work on](#finding-an-issue-to-work-on)

**When starting to work on your first issue**:

- [Getting help](#getting-help) as you work on your first pull request
- Learning [best practices](#best-practices)

**When getting ready to submit your first pull request**:

- [Submitting a pull request](#submitting-a-pull-request)

**After submitting your first pull request**:

- [Going beyond the first issue](#beyond-the-first-issue)

Any time you feel lost, come back to this guide. The information you need is
likely somewhere on this page (perhaps in the list of [common
questions](#common-questions)), or in one of the many references it points to.

If you've done all you can with the documentation and are still fee

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `ZULIP` (category: CHAT PLATFORMS)
- **Upstream URL:** https://github.com/zulip/zulip
- **Pinned commit (SHA):** `de2dbb995b7072a169320f522b2571587ac271a7`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`33f3a9717c1b567de49c51ebb3a4eb57bd1ec09906395258d8275b575c1db92e`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

