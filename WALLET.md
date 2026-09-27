# Alembic Wallet — setup and usage

## Download and verify

1. Get the build from the [downloads page](https://alembic-core.github.io/alembic/downloads/).
2. Verify the checksum in PowerShell:

    Get-FileHash Alembic-0.1-win-x64.zip -Algorithm SHA256

3. Compare the output with the SHA-256 published on the download page. It must match exactly.

## First start

1. Unpack the archive and run the wallet.
2. The wallet starts syncing. Sync state and peer count show in the status bar.
3. Create a wallet, write the seed down, keep it offline.

## Addresses

Alembic addresses start with **L**. Generate a new address for each miner to keep payouts separable.

## Ports

- P2P: 18989
- RPC: 18990
- Config file: alembic.conf

## Backup

The seed phrase restores everything. Store it offline; a file backup alone is not a backup.
