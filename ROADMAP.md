# Roadmap — VaultOS Systems

**Objective:** Build VaultOS v0.1 (offline relay node with snapshots and transports).

## Milestone 1 (Weeks 1–4)
- Draft snapshot specification (serialization + signature).
- CLI skeleton for snapshot signer/verify.
- Initial threat model document.

## Milestone 2 (Weeks 5–8)
- Implement store-and-forward pipeline with resume tokens.
- Add integrity checks and recovery tests.
- Basic CLI release for signing/verifying snapshots.

## Milestone 3 (Weeks 9–12)
- Demo transports:
  - QR-code sync
  - USB-based relay
  - LoRa proof-of-concept transfer
- Extend docs with usage instructions and recovery scenarios.

## Milestone 4 (Weeks 13–16)
- Finalize reproducible build process.
- Publish hardening checklist + threat model v1.
- Release VaultOS v0.1 with demo video + documentation.
