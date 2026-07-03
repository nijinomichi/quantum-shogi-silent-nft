# NFT Metadata

## Scope

The browser artifact generates an **ERC-721-compatible metadata draft**.

It does not:

- deploy a smart contract
- mint a token
- upload media or metadata to IPFS
- verify ownership
- guarantee compatibility with every marketplace

## Required review before minting

Check every generated field before external use:

- `name`
- `description`
- `image`
- `external_url`
- `attributes`
- creator attribution
- license information
- provenance references

## URI rules

A value such as `ipfs://<CID>` is only valid after the corresponding content has actually been uploaded and the CID has been verified.

Do not publish placeholder CIDs, contract addresses, token IDs, or transaction hashes as completed evidence.

## Recommended provenance fields

```json
{
  "creator": "Sou Hashiguchi",
  "project": "Quantum Shogi",
  "module": "Silent NFT",
  "protocol": "QuantumArt Protocol 2026",
  "repository": "https://github.com/nijinomichi/quantum-shogi-silent-nft",
  "source_commit": "<verified commit SHA>",
  "license": "<artwork-specific license>",
  "created_at": "<ISO 8601 timestamp>"
}
```

## Legal boundary

The repository MIT license applies to covered software. Artwork, generated media, text, datasets, trademarks, and third-party materials may require separate terms.
