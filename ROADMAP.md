# Roadmap

## Current Status

**Stage:** experimental prototype

The repository currently contains one standalone browser artifact and supporting documentation. It should be treated as a reference implementation, not as a production application, audited NFT system, or validated scientific tool.

## Completed

- Public repository created
- Standalone HTML prototype added
- Balmer-inspired visualization implemented
- Born-rule-inspired probability interface implemented
- Shogi-like candidate move generation implemented
- Metadata draft generation implemented
- Parent protocol relationship documented
- IYQ2025 non-affiliation boundary documented
- License notice added

## Known Limitations

- No automated browser tests are present.
- No schema validation is applied to generated metadata.
- No smart contract is deployed or audited.
- No IPFS upload is performed by the application.
- RadicanTrust™ values are experimental internal indicators, not certified measurements.
- Scientific references and poetic metaphors are not yet annotated line by line.
- Accessibility and mobile-device behavior require review.

## Next Actions

### Phase 1: Integrity

- ✅ CSS custom-property typo corrected.
- Add metadata schema validation.
- Replace placeholder values with explicit labels.
- Add provenance fields for generated artifacts.
- Add a scientific/metaphorical terminology note.

### Phase 2: Reliability

- Add basic automated tests for probability normalization and metadata output.
- Test current Safari, Chrome, and Firefox behavior.
- Review keyboard access, contrast, labels, and reduced-motion support.
- Record known browser limitations.

### Phase 3: Publication

- Decide whether GitHub Pages should host the prototype.
- Add screenshots and a short demonstration recording.
- Add versioned releases.
- Document any external media, datasets, and licenses.

### Phase 4: NFT Experiment

- Review metadata against the actual target platform.
- Separate artwork generation from minting instructions.
- Do not describe the repository as an ERC-721 implementation unless a contract is added and reviewed.
- Record CID, contract address, chain, token ID, and transaction only after they exist.

## Completion Criteria

The prototype may be described as a stable public experiment when:

- known syntax errors are fixed
- metadata output is validated
- claims and metaphors are clearly separated
- licensing and provenance are complete
- browser behavior is tested
- published NFT identifiers, if any, are independently verifiable

## Canonical Relationship

```text
quantumart-protocol-2026-official
  └── defines principles

quantum-shogi-silent-nft
  └── tests one implementation
```
