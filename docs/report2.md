# GameDAO UCG Update 02

## ⚙️ Technical developments and updates

Our current dapp lives in a monorepo (https://github.com/gamedaoco/gamedao-haiku), we run build pipelines, graph services, a docker swarm for test environments and more. On https://gamedao.app users can sign in and connect with Polkadot compatible wallets and Discord, the apps are deactivated, as the parachain lease will end in a while and the ink based contracts are not live yet. Furthermore, graph services are missing. Our test net is active, therefore we are considering to configure the existing apps for it to let the community have a glimpse. Account section is active, though. Main repo for Astar specific artefacts is https://github.com/gamedaoco/gamedao-astar

## 📣 Marketing and communication updates

No big updates at this point, we have visited conferences and continuously talk to other builders in other ecosystems to increase awareness. GameDAO is known to some, expanding and building on Astar for European builders a new idea.

We have allocated five percent of the total GAME token pool to activate the community to stake on GameDAO dapp. We believe this to be a crucial step to have early stage users which can contribute to governance and bring new projects.

## 🧑‍🤝‍🧑 Updates on community, partnerships and collaborations

We are working with existing and new partners and game studios to motivate new builds on Astar. At this point, web3 interested teams look at other L2 or are interested in Soneium — like us.

## 💸 dApp Staking rewards spent and reason for spending and uses

We have spent all received rewards for operational expenses of the company.

## 📅 Status of UCG milestones

Draft for porting the protocols was published in update 01.

✅ August “setup”: driving the roadmap for the complete protocol and sales funnel

✅ September “blueprints”

- xcm <> ink <> evm interaction → This needs more info from e.g. Astar dev team
- proxy / upgradability → Prototype exists

→ October "validation”

- (public) discussion of blueprints and protocols → prior to public discussion we need to publish our draft protocols, this will consume the remaining October and become visible in the repos and eventually on testnet.

## 🦾 Roadmap for next month

Keep going as suggested in our roadmap, initiate discussion with technical people on Astar.

- Proposal to list GAME on Astar
- Transfer AssetHub <> Astar L1 <> Hydration
- Integrate into dapp:
  - show GAME balance
  - show staking information and accumulated GAME rewards
  - start a collective with GAME

## 🥷 Current blockers or problems that the team is facing

At the current point, there are no blockers but setting up the whole dapp stack for Astar L1 requires additional steps, like building out a subgraph and testing out interaction between native pallets, ink contracts communicating with native pallets and EVM contracts communicating with both, pallets and ink contracts.

At this point we did not have knowingly access to technical people from Astar to discuss existing implementations, like the squid graph for dapp staking, which does not seem to work well over here, so potentially we will rebuild one.
