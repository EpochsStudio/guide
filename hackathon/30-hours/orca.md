# 30-Hours Task - Orca

## 1. Description of the Task

- The challenge for Orca will be broken up into two tasks. 
  - The first task will be an optional scavenger hunt designed to help you get familiar with our data and source tables.
  - The second task is that you will have the option to do two things (or both!):
    1. Create a novel Orca dataset within Dune such as orca.swaps or orca.liquidity, which others can leverage to create dashboards showing insights about the activity taking place on Orca.
    2. Build a Dune dashboard which leverages your knowledge of Orca data to show a novel insight about how Orca is performing across common DEX metrics such as TVL, swap volume, and more. Extra points for creativity in analysis or if you bring other Solana DEXs into your dashboard

### Scavenger Hunt (optional - tutorial):

**We’ve also created a Dune Dashboard to help you understand how to use the source tables linked below to answer questions and test your hypotheses!** Try to create queries that will answer the following questions.

### Scavenger hunt questions (the dashboard with answers is linked at the end – don’t peek!)

- Which wallet executed the first trade on Orca, what pool was it, and how much it for denominated in USDC?
- What is the largest trade that has been executed through Orca?
- Which wallet has executed the most trades?
- What was the average daily trading volume in February 2022?

### Challenge questions (optional, with no answer provided): 

- Which wallet is the largest liquidity provider in the SOL/USD pool?
- How many unique liquidity providers are there in the ORCA/SOL pool?
- Which pool has the largest amount of liquidity? Which has the least?

> Click here to reveal answers

## 2. Description to the Package

Orca is one of the first general-purpose AMMs launched on Solana. Users can swap assets, provide liquidity, and earn yield through an easy-to-use interface. Orca has also created custom smart contracts for its concentrated liquidity product, Whirlpools. In traditional AMM liquidity pools, a user provides liquidity across the entire continuous price curve. With Whirlpools, each user can specify the price range where they will provide liquidity.
The Orca team has created two source tables to lend a helping fin to hackathon participants:

### Dune specific source data

- orca.swaps: swap volume by pool (SQL query that uses a globalFarm address to pull all swaps)
- orca.users: user table for swaps data (aggregated stats for a user)
- Orca-Dune Scavenger Hunt Dashboard: example dashboard that answers the above questions using the above source tables

> Task: create a Dune dashboard or source tables to provide analytics and insights into Orca’s data.

## 3. What are the Must-Haves?

*[List down the primary features that the DApp must implement]*

- A dune dashboard or query that showcases your understanding of the Solana ecosystem and the ecosystem’s existing apps that work with, and work like, Orca
- A functioning dashboard with accurate data

## 4. What are the Nice-to-Haves?

- If your dashboard can demonstrate a solid understanding of a trader’s mindset and the type of data they look for when deciding how to manage their portfolio on Solana
- If your dashboard highlights liquidity provision on Orca, such as fees earned, fees donated through the Orca Impact Fund, or distribution of LPs across and within pools
- If you build a source table for any of the following areas:
- Liquidity adds/removes by pool (SQL query that uses a globalFarm address to pull all additions or removal of liquidity)
- Fees allocated to LPs, Orca Treasury, and Orca Impact Fund
- Active Wallets, Number of traders by pool, Number of LPs by pool
- Transactions by instruction type
- Ability to toggle the table key (e.g., filter for certain pools, LPs above a certain size, etc.)

## 5. **Judging Criteria**

- Usability and Accuracy: is your dashboard easy to use for users and is the data accurate?
- Insight: does your dashboard provide a unique or clear insight into the Orca or Solana ecosystems?
- Composability and Stability: did you build queries or dashboards that can be leveraged by others? Is the data called and indexed in a sustainable manner?

## 6. Resources

- [Building Blocks / Scavenger Hunt Dashboard](https://dune.xyz/twocrows/Test)
- [Dune Analytics Docs](https://github.com/duneanalytics/projects)
- Orca’s API Endpoints:
  - [Provides pool data](https://api.orca.so/pools)
  - [Provides allpool data](https://api.orca.so/pools)(https://api.orca.so/allpools)
  - [Provides pool addresses and configs](https://api.orca.so/configs)
- Orca’s SDK:
  - [Whirlpools SDK](https://github.com/orca-so/whirlpool-sdk)
  - [Orca SDK](https://github.com/orca-so/typescript-sdk)

<!-- - https://docs.google.com/document/d/1_hObafwZe4ctjDa9OR8sP2shthfmjVD9gJ1vrlTnFUs/edit#heading=h.bzgaom1ldj5e -->

###### tags: `hackathon`
