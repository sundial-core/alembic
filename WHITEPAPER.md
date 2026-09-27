# Alembic (ALM) — Whitepaper

## Abstract

Alembic is a proof-of-work network running RandomX on ordinary processors. Its design goal is a currency whose every governing constant was fixed in public source code before block zero existed — a sealed apparatus, not a negotiated one.

## 1. The still as a design principle

An alembic (alambic) works because its geometry is fixed before the fire is lit. The shape of the cucurbit, the swan neck and the condenser determine what arrives in the receiver; nothing is added or adjusted mid-run. Alembic copies that order of operations:

1. Constants first: total supply, block cadence, stage-1 reward, halving rhythm and difficulty rule are committed to public source code.
2. Chain second: block zero is mined only after the code is published.
3. Nothing after: no dev fee, no treasury, no unlock calendar, no governance parameters left to move.

## 2. Consensus

- Algorithm: RandomX, CPU-oriented and memory-heavy.
- Block time: 160 seconds. Exactly 540 blocks per day.
- Difficulty: retargets every block.
- The reward is paid in full to the miner who assembles the block.

## 3. Emission

Stage-1 reward: 41 ALM per block. Halving every 690,000 blocks (~3.5 years). Maximum supply:

    2 × 41 × 690,000 = 56,580,000 ALM

Daily issuance at stage 1: 540 × 41 = 22,140 ALM. Zero coins existed before genesis; every coin comes out of a block reward.

## 4. Why CPU-minable

RandomX re-aims its computation at every block, so purpose-built hardware holds no lasting edge over a desktop CPU. Capacity is ordinary processors doing ordinary work, at home.

## 5. Honest limits

Alembic is a young, low-hashrate network. It is not secure money and is 51%-attackable by anyone renting enough RandomX capacity. This document describes what the published source code does; it is not investment advice.
