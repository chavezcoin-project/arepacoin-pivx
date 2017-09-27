ArepaCoin Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/ArepaCoin-Project/ArepaCoin.svg?branch=master)](https://travis-ci.org/ArepaCoin-Project/ArepaCoin) [![GitHub version](https://badge.fury.io/gh/ArepaCoin-Project%2FArepaCoin.svg)](https://badge.fury.io/gh/ArepaCoin-Project%2FArepaCoin)

ArepaCoin is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using coin mixing technology, we call it _Obfuscation_.
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftTX_.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with a collateral of 10K ARC.

More information at [arepacoin.org](http://www.arepacoin.org) Visit our ANN thread at [BitcoinTalk](http://www.bitcointalk.org/index.php?topic=1262920)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>43,199,500 ARC</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>Infinite</td></tr>
<tr><td>Premine</td><td>60,000 ARC*</td></tr>
</table>

*60,000 ARC Premine was burned in block [279917](http://www.presstab.pw/phpexplorer/ArepaCoin/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0)

### Reward Distribution

<table>
<th colspan=4>PoW Phase</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th><th>Duration (Days)</th></tr>
<tr><td>1</td><td>60,000 ARC</td><td>Initial Premine</td><td>0 Days</td></tr>
<tr><td>2-151200</td><td>250 ARC</td><td rowspan=2>Open Mining</td><td rowspan=2> Approx 180 Days</td></tr>
<tr><td>151201-259200</td><td>50 ARC</td></tr>
<tr><th colspan=4>PoS Phase</th></tr>
<tr><th>Block Height</th><th colspan=3>Reward Amount</th></tr>
<tr><td>259201-Infinite</td><td colspan=3>Variable based on SeeSaw Reward Mechanism</td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-43200</td><td>20% (50 ARC)</td><td>80% (200 ARC)</td><td>N/A</td></tr>
<tr><td>43201-151200</td><td>20% (50 ARC)</td><td>70% (200 ARC)</td><td>10% (25 ARC)</td></tr>
<tr><td>151201-259200</td><td>45% (22.5 ARC)</td><td>45% (22.5 ARC)</td><td>10% (5 ARC)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 1</td><td>259201-302399</td><td>50 ARC</td><td>90% (45 ARC)</td><td>10% (5 ARC)</td></tr>
<tr><td>Phase 2</td><td>302400-345599</td><td>45 ARC</td><td>90% (40.5 ARC)</td><td>10% (4.5 ARC)</td></tr>
<tr><td>Phase 3</td><td>345600-388799</td><td>40 ARC</td><td>90% (36 ARC)</td><td>10% (4 ARC)</td></tr>
<tr><td>Phase 4</td><td>388800-431999</td><td>35 ARC</td><td>90% (31.5 ARC)</td><td>10% (3.5 ARC)</td></tr>
<tr><td>Phase 5</td><td>432000-475199</td><td>30 ARC</td><td>90% (27 ARC)</td><td>10% (3 ARC)</td></tr>
<tr><td>Phase 6</td><td>475200-518399</td><td>25 ARC</td><td>90% (22.5 ARC)</td><td>10% (2.5 ARC)</td></tr>
<tr><td>Phase 7</td><td>518400-561599</td><td>20 ARC</td><td>90% (18 ARC)</td><td>10% (2 ARC)</td></tr>
<tr><td>Phase 8</td><td>561600-604799</td><td>15 ARC</td><td>90% (13.5 ARC)</td><td>10% (1.5 ARC)</td></tr>
<tr><td>Phase 9</td><td>604800-647999</td><td>10 ARC</td><td>90% (9 ARC)</td><td>10% (1 ARC)</td></tr>
<tr><td>Phase X</td><td>648000-Infinite</td><td>5 ARC</td><td>90% (4.5 ARC)</td><td>10% (0.5 ARC)</td></tr>
</table>
