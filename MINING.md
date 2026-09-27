# Mining Alembic (ALM)

Alembic uses RandomX, a CPU-oriented proof-of-work algorithm. Ordinary processors can take part; purpose-built hardware gains no meaningful edge because the work is re-aimed after every block.

## Requirements

- A CPU with AES-NI support and at least 2 GB of memory per mining thread group
- The Alembic node running and synced (or a pool account)
- An Alembic address (L-prefix) to receive rewards

## Step 1 — Run a node

1. Download the wallet build from the [downloads page](https://alembic-core.github.io/alembic/downloads/).
2. Unpack and run it. Wait for full sync.
3. Create a wallet and copy an L-prefix address.

## Step 2 — Mine solo

Point xmrig at your node's RPC port:

    xmrig -o 127.0.0.1:18990 -u YOUR_L_ADDRESS -a rx/0 -k

## Step 3 — Mine on a pool

Any RandomX pool that lists Alembic can be used:

    xmrig -o POOL_URL:PORT -u YOUR_L_ADDRESS -a rx/0 -k --donate-level=1

## Notes

- Solo mining pays the full 41 ALM coinbase to your address when you find a block.
- Block time is 160 seconds; difficulty retargets every block.
- No dev fee exists anywhere in the code path.
