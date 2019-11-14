---
sccp: 7
title: Lower exchange fee to 50 basis points for two weeks
author: Arthur Cheong (@Arthur0x)
discussions-to: https://discord.gg/kPPKsPb
status: Proposed
created: 2019-11-15
---

## Simple Summary
<!--"If you can't explain it simply, you don't understand it well enough." Provide a simplified and layman-accessible explanation of the SCCP.-->
The existing exchange fee of 50 basis points is higher than the standard 30 basis points and oracle frontrunning is less of a concern now with SIP-21 implemented. We propose to lower the fee to 30 basis points to enable more organic trading flow within the system. We believe that the lower fee should bring some oragnic volume and make it more more feasible for traders to trade again.

## Abstract
<!--A short (~200 word) description of the variable change proposed.-->
Exchange fees are charged each time a Synth is converted, this fee is currently set to 50bps, which is making it really difficult for average trader to trade in this environment. By lowering the exchange fee, this, average trader will find it easier to trade in this low volatility environment.

## Motivation
<!--The motivation is critical for SCCPs that want to update variables within Synthetix. It should clearly explain why the existing variable is not incentive aligned. SCCP submissions without sufficient motivation may be rejected outright.-->
50 basis point make it really difficult for most users to trade on Synthetix Exchange. Given that SIP-21 is already implemented to mitigate oracle front-running, we should revert back to 30 basis point trading fee.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
