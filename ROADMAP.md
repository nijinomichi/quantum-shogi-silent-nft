# Roadmap

## Current Status

**Stage:** experimental reference implementation

The repository contains one standalone browser artifact, a GitHub Pages entry point, and supporting documentation. It should not be treated as a production application, audited NFT system, or validated scientific tool.

## Completed

- ✅ Public repository created
- ✅ Standalone HTML prototype added
- ✅ Balmer-inspired visualization implemented
- ✅ Born-rule-inspired probability interface implemented
- ✅ Shogi-like candidate move generation implemented
- ✅ Metadata draft generation implemented
- ✅ Parent protocol relationship documented
- ✅ IYQ2025 non-affiliation boundary documented
- ✅ License notice added
- ✅ CSS custom-property typo corrected
- ✅ Project hierarchy clarified: Quantum Shogi as project, Silent NFT as module
- ✅ `docs/` structure added
- ✅ GitHub Pages entry file prepared as `index.html`
- ✅ Provenance and NFT metadata boundaries documented

## Known Limitations

- No automated browser tests are present.
- No schema validation is applied to generated metadata.
- No smart contract is deployed or audited.
- No IPFS upload is performed by the application.
- RadicanTrust™ values are experimental internal indicators, not certified measurements.
- Scientific references and poetic metaphors are not yet annotated line by line in the implementation.
- Accessibility and mobile-device behavior require review.
- GitHub Pages is prepared but not yet confirmed as enabled.
- No formal GitHub Release has yet been published.

## Next Actions

### Phase 1: Integrity

- Add metadata schema validation.
- Replace placeholder values with explicit labels.
- Add provenance fields to generated artifacts.
- Annotate scientific and metaphorical terminology in the implementation.

### Phase 2: Reliability

- Add automated tests for probability normalization and metadata output.
- Test current Safari, Chrome, and Firefox behavior.
- Review keyboard access, contrast, labels, and reduced-motion support.
- Record browser limitations.

### Phase 3: Publication

- Enable GitHub Pages from the `main` branch root.
- Confirm the public site URL and browser behavior.
- Add screenshots and a short demonstration recording.
- Publish the first versioned release as `v0.1.0` after validation.
- Document all external media, datasets, and licenses.

### Phase 4: NFT Experiment

- Review metadata against the actual target platform.
- Separate artwork generation from minting instructions.
- Do not describe the repository as an ERC-721 implementation unless a contract is added and reviewed.
- Record CID, contract address, chain, token ID, and transaction only after they exist.

## Completion Criteria

The prototype may be described as a stable public experiment when:

- metadata output is validated
- claims and metaphors are clearly separated
- licensing and provenance are complete
- browser behavior is tested
- accessibility review is recorded
- the public release is versioned
- published NFT identifiers, if any, are independently verifiable

## Canonical Relationship

```text
quantumart-protocol-2026-official
  └── defines principles

quantum-shogi-silent-nft
  └── tests one implementation
```
