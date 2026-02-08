# SMCA-REF-1
<img src=https://github.com/cannaseedus-bot/SMCA/blob/main/SMCA_1.png>
This repository is the **canonical reference implementation** of:

- Collapse Geometry Registry
- CM-1 Control Alphabet
- Binary Split legality
- SCXQ7 execution gating
- Conformance verification
- Public compliance signaling

## What this repo does

1. Builds a CM-1 verifier to WASM
2. Verifies collapse geometry via CI
3. Publishes immutable registry artifacts
4. Anchors legality via hashes
5. Generates deterministic compliance badges

## What this repo does NOT do

- Execute arithmetic
- Compute π
- Interpret semantics
- Allow extensions

If CI passes, the implementation is lawful.
If CI fails, the implementation is illegal.

This repository defines **execution law**, not software behavior.

## Generated artifacts

This repository does not store binary artifacts. Build the CM-1 verifier with `src/cm1/build.sh`
to generate `wasm/cm1_verify.wasm` locally, then run `node conformance/run.js` to verify vectors.
See `docs/BINARY_ARTIFACTS.md` for exact regeneration instructions and example CM-1 streams.
