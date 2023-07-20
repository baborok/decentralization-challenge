# A report assessing the decentralization of the Aave project

Aave (aave.com) is an Open Source and Non-Custodial protocol to earn interest on deposits & borrow assets. The depositors provide liquidity to specific asset markets to earn a passive income. Borrowers may take out loans secured by over-collateralized deposits, paying interest at a stable or variable rate. Users may also perform non-collateralized borrowing through flash loans while paying a fee. Users must first deposit a supported asset to interact with the protocol. This deposit will accrue interest based on the amount deposited and the market borrowing demand. Users can also use these deposited assets as collateral for borrowing money in the protocol, contributing to the total interest rate accumulatted. 


**1. GitHub Metrics:**

There are 3 repositories with Aave protocol code:
* `Aave Protocol Version 1.0` (https://github.com/aave/aave-protocol):
     - Total number of commits: 47
     - Number of contributors: 5
     - Percentage of commits from top-5 contributors: 100%
     - Number of pull requests: 26
     - Ratio of open/closed issues: 19/18

* `Aave Protocol V2` (https://github.com/aave/protocol-v2):
     - Total number of commits: 1741
     - Number of contributors: 23
     - Percentage of commits from top-5 contributors: 46%
     - Number of pull requests: 72
     - Ratio of open/closed issues: 54/54

* `Aave V3 protocol` (https://github.com/aave/aave-v3-core).
     - Total number of commits: 2145
     - Number of contributors: 27
     - Percentage of commits from top-5 contributors: 62%
     - Number of pull requests: 7
     - Ratio of open/closed issues: 9/369

For comparison Bitcoin Core integration/staging tree repository (https://github.com/bitcoin/bitcoin):
     - Total number of commits: 38047
     - Number of contributors: 914
     - Percentage of commits from top-5 contributors: 18%
     - Number of pull requests: 299
     - Ratio of open/closed issues: 352/7161


** 2. Token Distribution:**

* The distribution of tokens among the top holders to understand the concentration of ownership (https://etherscan.io/token/tokenholderchart/0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9):
   - Token Total Supply: 16,000,000.00 Token
   - Total Token Holders: 153,338
   - The top 100 holders collectively own 82.89%

* The percentage of total tokens held by the largest token holders (https://etherscan.io/token/tokenholderchart/0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9):
    - Aave:Stacked Aave - 19.75%
    - Balancer:Aave-Weth - 7.56%
    - Aave: Ecosystem Reserve - 7.30%
    - Aave:aAAVE Token V2 - 7.23%
    - Binance 7 - 3.75%
    - Binance: Binance - Peg Tokens - 3.12%


**3. Governance Metrics:**

The level of community participation in governance voting. Accourding to the last 10 proposals on snapshot.org/#/aave.eth:

  - The average number of the voters: 8.8K
  - The average share of TOP-1 voter (aavechan.eth): 42%
  - The maximum voting power: 243K AAVE

The top-5 discussions of all time on governance.aave.com (https://governance.aave.com/c/governance/4/l/top):

  - The average number of replies: 71
  - The average share of views: 27.3K
  - The average number of users involved: 52

The latest 5 discussions on governance.aave.com (https://governance.aave.com/c/governance/4/l/latest):

  - The average number of replies: 46
  - The average share of views: 19.5K
  - The average number of users involved: 20


**4. Operational Metrics:**

   - Maximum Total supply - 16,000K AAVE
   - Circulating Supply (https://coinmarketcap.com/currencies/aave/) - 14,485K AAVE (91%)
   - Token holders (the number of active users utilizing the Aave platform) - 153K
   - Total transfers (transactions) of all time - 2,056K

   - AAVE Price (16 Jul 2023)  - USD 79,14
   - Market capitalization (the total value of assets locked in the Aave protocol) - USD 1,266,285K

   - Average AAVE value for one holder - USD 8,276
   - Maximum factual value for one holder (for Aave: Staked Aave) - USD 243,769K

   - The mechanism by which profits are generated and distributed within the project. Aave generates profits through borrowing and lending fees. These profits are distributed to Aave token holders.

   - On coinmarketcap.com (https://coinmarketcap.com/currencies/aave/) aave token is on 412K watchlists


**5. User Engagement Metrics:**
According to https://coinmarketcap.com/currencies/aave/holders/:

  - Top 10 Holders control - 55.96% AAVE
  - Top 20 Holders control - 66.03% AAVE
  - Top 50 Holders control - 76.57% AAVE
  - Top 100 Holders control - 82.95% AAVE

The percentage of token holders actively participating in governance voting (Voting Turnout) - around 6% (number of votes on snapshot.org proposals/ total number of token holders)


**6. Transparency and Auditing:**

The number and results of independent security audits performed on the Aave smart contracts and protocols (https://github.com/aave/aave-v3-core): 8. 

- V3.0.1 - December 2022

    - PeckShield
    - SigmaPrime
    - V3 Round 1 
- October 2021

    - ABDK
    - OpenZeppelin
    - Trail of Bits
    - Peckshield
    - V3 Round 2 
- December 2021

    - SigmaPrime

- Formal Verification - November 2021-January 2022

    - Certora

Nethetheless, in reports the system's decentralization was not considered.


**7. Community Treasury:**

Aave Community Treasury (https://aave.com/#governance) - USD 115,666K consists of Ecosystem Reserve (AAVE tokens) USD 91,134K and Treasury Collectors USD 24,531K:

  - AAVE - 78,8%
  - DAI -   6.8%
  - USDT -  5,4%
  - USDC -  5,2%

Sources of Treasury collectors earnings: 
* Reserve factor: percentage of protocol interest paid by borrowers
* Instant liquidity fees: percentage of fees from instant liquidity transactions (V3 only)
* Liquidation fees: percentage of collateral liquidation bonus (V3 only, not yet active)
* Portal fees: paid by bridging protocols to re-back assets (V3 only, not yet active)

Distribution between platforms:

* ETH Mainnet - 42,2%
* Polygon - 38,4%
* Avalanche - 14,5%
* Optimism - 4,2%


**8. Markets Distribution:**

Aave operates on 3 markets (https://classic.aave.com/#/markets).

  - AAVE v2 market. Total market size USD 5,350,450K. 13 assets. The maximum borrowed sum is USD487M in USD Coin, USD486M in Ethereum, USD445M in USDT Coin. These three assets account for 26% of the total market size.
  - AAVE market Polygon. Total market size USD 192,742K. 7 assets.
  - AAVE market Avalanche. Total market size USD 57,214K. 7 assets.



**9. Interoperability:**

- The number and significance of integrations with other DeFi protocols, wallets, or platforms.

- The ability of Aave to operate or integrate with multiple blockchain networks.
