<p align="center"><img src="https://github.com/user-attachments/assets/7785a8d6-6e28-4892-8958-3daf85414f05" width="80" alt="Bonfÿre knight" /></p>

# Bonfÿre Core

**Shared native libraries and artifact contracts.**

C11 library authors, local-data developers, and integrations that require the smallest reusable substrate.

## Aurekai / Bonfÿre: role and maturity

**Why this exists:** AI can generate software faster than teams can coordinate it. [Aurekai](https://aurekai.work) invests engineering and reusable software into connected public and commercial experiences; [Bonfÿre](https://github.com/Nickgonzales76017/bonfyre) supplies the native capabilities, source context, authorized work and verification that make projects compound.

| | This repository |
|---|---|
| **Business outcome** | Reusable low-level components instead of project-by-project libraries |
| **Technical scope** | C11 core libraries and native artifact contracts |
| **Maturity boundary** | April 2026 source extraction; compare against canonical lib/ before use |
| **Verification** | Inspect the source, build instructions, fixtures and limitations below; this repository is not proof of a live Aurekai release. |

[Business, project and technical model](https://github.com/Nickgonzales76017/bonfyre/blob/main/docs/aurekai-bonfyre-model.md) · [Current canonical implementation](https://github.com/Nickgonzales76017/bonfyre)

## Source and scope

This repository preserves an **April 2026 source extraction**. It contains `lib/`, `cmd/`, `schemas/`, `tools/` and migration notes. That material remains useful for inspection and for understanding a component boundary, but it is not the latest canonical source or an independently supported package release.

The [current Bonfÿre development lineage](https://github.com/Nickgonzales76017/bonfyre) owns the integrated version: [`lib/`](https://github.com/Nickgonzales76017/bonfyre/tree/main/lib/). Later source changes are reviewed and published separately from private runtime state.

The older extraction kept temporary vendored dependencies and original migration notes. They are not an additional source of truth; check the [current repository](https://github.com/Nickgonzales76017/bonfyre) for the version, license, operating contract and tests relevant to your use.

## See the work in context

- [Aurekai work samples](https://aurekai-work-samples.pages.dev/) — customer-facing tools and handoffs
- [Bonfÿre developer and product guides](https://docs.aurekai.work/) — integrated operations and technical contexts
- [Client integration examples](https://github.com/Nickgonzales76017/bonfyre/blob/main/docs/client-operations-portfolio.md) — real kinds of receiving-system work

For an **independently scoped native-C example** with its own build and verification fixtures, see [Bonfÿre Statement Import](https://github.com/Nickgonzales76017/bonfyre-statement-import).

The license accompanying this extraction governs its own files; the canonical repo and independent components may have different terms.
