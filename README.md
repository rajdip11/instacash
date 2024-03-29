InstaCash Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/InstaCash-Project/InstaCash.svg?branch=master)](https://travis-ci.org/InstaCash-Project/InstaCash) [![GitHub version](https://badge.fury.io/gh/InstaCash-Project%2FInstaCash.svg)](https://badge.fury.io/gh/InstaCash-Project%2FInstaCash)

InstaCash is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for budget proposals. The goal of InstaCash is to achieve a decentralized sustainable crypto currency with near instant full-time private transactions, fair governance and community intelligence.
- Anonymized transactions using the [_Zerocoin Protocol_](http://www.instacash.org/zich).
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftX_.
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

More information at [instacash.cc](http://www.instacash.cc) Visit our ANN thread at [BitcoinTalk](https://bitcointalk.org/index.php?topic=2900624.0)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>30 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>100,000,000 ICH</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>Infinite</td></tr>
<tr><td>Premine</td><td>~500,000 ICH</td></tr>
</table>


### Reward Distribution

<table>
<th colspan=4>Genesis Block</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th></tr>
<tr><td>1</td><td>500,000 ICH</td></tr>
</table>

###POW REWARD STRUCTURE:
=> Phase -1: Block 1 - 10000: 100 ICH per block [no MN reward] [3.47~ days] => total 1,000,000 ICH <=
=> Phase -2: Block 10001 - 100000: 10 ICH per block [Miner Reward is 75% - 7.5 coin per block] [MN reward is 25% - 2.5 coin] [31.25~ days] => total 900,000 ICH <=

Total ICH in circulation in POW: 1,000,000 [phase-1] + 900,000 [phase-2] + 500,000 [premine] = 2,400,000 ICH
N.B.: First 10k PoW blocks have 100 ICH reward because many people are well informed about the launch because of per-announcement, so we'll see big hashrate and high mining difficulty in first few days. so we have increased block rewards for first 3~4 days so that no one get any loss from high difficulty mining. Also it'll sustain coin value.

###POS REWARD STRUCTURE:
=> Block 100,001 - Inf: 5 ICH [MN - 75%] [STAKE - 25%] <=
POW REWARD STRUCTURE:
=> Phase -1: Block 1 - 10000: 100 ICH per block [no MN reward] [3.47~ days] => total 1,000,000 ICH <=
=> Phase -2: Block 10001 - 100000: 10 ICH per block [Miner Reward is 75% - 7.5 coin per block] [MN reward is 25% - 2.5 coin] [31.25~ days] => total 900,000 ICH <=

Total ICH in circulation in POW: 1,000,000 [phase-1] + 900,000 [phase-2] + 500,000 [premine] = 2,400,000 ICH
N.B.: First 10k PoW blocks have 100 ICH reward because many people are well informed about the launch because of per-announcement, so we'll see big hashrate and high mining difficulty in first few days. so we have increased block rewards for first 3~4 days so that no one get any loss from high difficulty mining. Also it'll sustain coin value.

###POS REWARD STRUCTURE:
=> Block 100,001 - Inf: 5 ICH [MN - 75%] [STAKE - 25%] <=
