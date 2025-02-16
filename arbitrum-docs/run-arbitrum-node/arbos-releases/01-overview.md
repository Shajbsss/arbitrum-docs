---
title: 'ArbOS software releases: Overview'
sidebar_label: 'Overview'
sidebar_position: 1
author: dlee
---

:::info

This document provides an overview of Nitro node software releases that upgrade ArbOS. Visit the [Nitro Github repository](https://github.com/OffchainLabs/nitro/releases) for a detailed index of Nitro releases.

:::

Arbitrum chains are powered by Arbitrum nodes running the Nitro software stack. The Nitro software stack includes [ArbOS](https://forum.arbitrum.foundation/t/arbitrum-arbos-upgrades/19695), the Layer 2 EVM hypervisor that facilitates the execution environment of an Arbitrum chain.

Although Nitro is updated regularly, only a subset of Nitro releases carry ArbOS upgrades. These releases are significant because ArbOS upgrades are Arbitrum's equivalent to a hard fork - they can alter a node's ability to produce valid Arbitrum blocks. This is why validator nodes supporting a public Arbitrum chain (One, Nova) **must update Nitro** whenever a new ArbOS version is released.

Note that every Nitro release is backwards compatible. In other words, the latest version of Nitro will support all previous ArbOS releases. This means that your validator's Nitro version must be greater than or equal to the version that includes the latest ArbOS upgrade.

import PublicPreviewBannerPartial from '../../node-running/partials/_upgrade-cadence-recommendations-partial.mdx';

<PublicPreviewBannerPartial />

ArbOS upgrades are carried out by the chain's owner; in the case of Arbitrum One and Nova, the owner is the Arbitrum DAO and so an upgrade will require a governance proposal and vote to pass to complete the upgrade. [This is an example of a Nitro release that contains an ArbOS version bump, specifically to ArbOS 11](https://github.com/OffchainLabs/nitro/releases/tag/v2.2.0).

Visit [Inside Arbitrum Nitro](/inside-arbitrum-nitro/inside-arbitrum-nitro.mdx) to learn more about Nitro's architecture; more information about ArbOS software releases is available on [the Arbitrum DAO forum](https://forum.arbitrum.foundation/t/arbitrum-arbos-upgrades/19695).

## List of available ArbOS releases

- [ArbOS 20 "Atlas"](/run-arbitrum-node/arbos-releases/arbos20.md)
- [ArbOS 11](/run-arbitrum-node/arbos-releases/arbos11.md)

## Naming and numbering scheme

Beginning with ArbOS 20, ArbOS releases use the name of planetary moons in our solar system, ascending in alphabetical order (i.e. the next ArbOS upgrade after ArbOS 20 "Atlas" will be a planetary moon that begins with the letter "B").

The number used to denote each upgrade will increment by 10, starting from ArbOS 20 (i.e. the next ArbOS upgrade after ArbOS 20 will be ArbOS 30). This was done because there are teams who have customized their Orbit chain's [behavior](/launch-orbit-chain/how-tos/customize-stf.mdx) or [precompiles](/launch-orbit-chain/how-tos/customize-precompile.mdx) and who may wish to use ArbOS's naming schema between official ArbOS version bumps (e.g. ArbOS 12 could be the name of a customized version of ArbOS for a project's L3 Orbit chain).

## Network status

To view the status and timeline of network upgrades on Arbitrum One and Nova, [please visit this page](https://docs.arbitrum.foundation/network-upgrades).

## Stay up to date

To stay up to date with proposals, timelines, and statuses of network upgrades to Arbitrum One and Nova:

- Subscribe to the [Arbitrum Node Upgrade Announcement channel on Telegram](https://t.me/arbitrumnodeupgrade)
- Join both the `#dev-announcements` and `#node-runners` Discord channels in the [Arbitrum Discord server](https://discord.gg/arbitrum)
- Follow the official Arbitrum ([`@Arbitrum`](https://twitter.com/arbitrum)) and Arbitrum Developers ([`@ArbitrumDevs`](https://twitter.com/ArbitrumDevs)) X accounts, formerly Twitter.
