# Source Imports

Planned imports for the first `bonfyre-core` extraction batch.

| Current Source | Target Path In `bonfyre-core` | Notes |
|---|---|---|
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/liblambda-tensors` | `lib/liblambda-tensors/` | Prefer preserving existing nested repo history if later imported with subtree/filter-repo. |
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/ArtifactManifest` | `schemas/artifact-manifest/` | Shared schema/validation contract. |
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/TreeSitterCanon` | `tools/tree-sitter-canon/` | Canonicalization helper. |
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/JqCanon` | `tools/jq-canon/` | Canonicalization helper. |
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/ZstdFamilyCompressor` | `tools/zstd-family-compressor/` | Compression substrate helper. |
| `/Users/nickgonzales/Documents/Bonfyre/10-Code/_shared/bonfyre_toolkit.py` | `scripts/bonfyre_toolkit.py` | Shared utility script. |

## Import Strategy

Recommended order:

1. import `liblambda-tensors`
2. import `ArtifactManifest`
3. import canon helpers
4. import compressor helper
5. import shared toolkit

This order gives the repo a library-first shape instead of starting with wrapper scripts.

## Imported So Far

- `lib/liblambda-tensors/`
- `schemas/artifact-manifest/`
