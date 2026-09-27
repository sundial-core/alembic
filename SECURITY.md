# Security notes

## Verify before running

- SHA-256 checksums are published with every release. Verify before executing anything.
- Downloads come only from this site or the GitHub Releases page: https://github.com/alembic-core/alembic/releases

## Network model

Alembic is a young, low-hashrate RandomX chain. Practical consequences:

- It is 51%-attackable by anyone renting enough RandomX capacity.
- Treat it as experimental software for study, not secure money.
- Never commit more electricity than you can spare.

## Operational hygiene

- Keep the seed offline.
- One address per miner keeps accounting clean.
- Full-node mining (solo) removes third parties entirely.
