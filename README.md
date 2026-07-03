<div align="center">
  <h1 align="center">Awesome Arc</h1>
  <div align="center">
      <a href="https://www.arc.io">
        <img alt="Arc Logo NavyGradient" src="https://dweb.link/ipfs/bafkreicrgswfiqkz4rqoqcngduc26uaau24ec7hgfgtviyjgh7tys7sfqe" height="130">
      </a>
    <p>The Economic OS for the internet</p>
    <a href="https://awesome.re">
      <img alt="awesome list badge" src="https://awesome.re/badge.svg">
    </a>
    <a href="https://github.com/0xBitzz/awesome-arc/blob/main/CONTRIBUTING.md">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/website-arc.io-blue">
    </a>
  </div>
  <br/>
  <div align="center">A curated list of awesome resources related to the <a href='https://www.arc.io'>Arc</a> L1 Blockchain.
    <br/>
    <br/>
    Arc is a purpose-built Layer-1 blockchain for stablecoin-native financial applications, with USDC as gas, sub-second deterministic finality, and full EVM compatibility.
  </div>
</div>

## Contents
- [Getting Started](#getting-started)
- [Official Resources](#official-resources)
    - [Sites](#sites)
    - [Channels & Community](#channels--community)
- [Learning Resources](#learning-resources)
    - [Talks & Presentations](#talks--presentations)
    - [Architecture & Concepts](#architecture--concepts)
- [Developer Resources](#developer-resources)
    - [SDKs](#sdks)
    - [Tutorials](#tutorials)
    - [Example Projects](#example-projects)
    - [Contract Templates](#contract-templates)
    - [Integration Guides](#integration-guides)
    - [AI & Agents](#ai--agents)
- [Research Papers](#research-papers)
- [Ecosystem Projects](#ecosystem-projects)
    - [Analytics](#analytics)
    - [DeFi](#defi)
    - [Exchanges](#exchanges)
    - [Infrastructure](#infrastructure)
    - [Interoperability](#interoperability)
    - [Oracles](#oracles)
    - [Payments](#payments)
    - [RWAs](#rwas)
    - [Wallets](#wallets)
- [Community Projects](#community-projects)
- [Contributing](#contributing)
- [License](#license)

## Getting Started
New to Arc? Start here to learn about the platform, set up your environment, and deploy your first contract.
- [Introducing Arc](https://www.circle.com/blog/introducing-arc-an-open-layer-1-blockchain-purpose-built-for-stablecoin-finance) - Learn about Arc, a Layer-1 blockchain purpose-built for stablecoin finance.
- [Connect to Arc](https://docs.arc.network/arc/references/connect-to-arc) - Set up your wallet and configure your development environment for Arc Testnet.
- [Faucet](https://faucet.circle.com) - Get testnet USDC and EURC.
- [Deploy your first contract](https://docs.arc.io/arc/tutorials/deploy-on-arc) - Learn to deploy, test, and interact with a Solidity smart contract on Arc Testnet.

## Official Resources
> Official websites, documentation, tools, and community channels for Arc.

### Sites
- [Website](https://www.arc.io) - Official Arc website.
- [Documentation](https://docs.arc.io/arc-chain) - Official Arc developer documentation.
- [Blog](https://www.arc.io/blog) - Official Arc blog.
- [Faucet](https://faucet.circle.com) - Get testnet USDC, EURC, and Circle Wrapped Bitcoin (cirBTC) for development on Arc.
- [Explorer](https://testnet.arcscan.app) - Block explorer for exploring transactions, blocks, addresses, and smart contracts on Arc.
- [Status Page](https://status.arc.io) - Uptime and incident tracker for the Arc network.

### Channels & Community
- [GitHub](https://github.com/circlefin/arc-node) - Official Arc GitHub organization.
- [X](https://x.com/arc) - Official Arc X account.
- [Discord](https://discord.com/invite/buildonarc) - Official Arc Discord server.
- [Arc House](https://community.arc.io) - Official community hub for Arc builders.

## Learning Resources
> Resources for understanding Arc's architecture, design, and core concepts.

### Talks & Presentations
- [Building the Internet Financial System](https://www.youtube.com/watch?v=aZ_3BLcJUNQ) - Explore Circle's vision for the internet financial system, from USDC to governed networks.
- [Why Circle built Arc: The Vision and Key Features](https://www.youtube.com/watch?v=ITEpvUhD3Dc) - Explore the vision behind Arc and its core features.
- [Arc Developer Overview](https://www.youtube.com/watch?v=BG0sHuTqGRc) - Provides an overview of Arc's developer experience and how to get started.

### Architecture & Concepts
- [System Overview](https://docs.arc.io/arc/concepts/system-overview) - Provides an overview of Arc's dual-layer architecture, including the execution and consensus layers.
- [Consensus Layer](https://docs.arc.io/arc/concepts/consensus-layer) - Learn how Arc's Malachite-based consensus layer validates and finalizes blocks.
- [Execution Layer](https://docs.arc.io/arc/concepts/execution-layer) - Learn how Arc's Reth-based execution layer maintains the full blockchain state and processes transactions.

## Developer Resources
> [!NOTE]
> Arc is EVM-compatible with some unique differences. Review the [EVM differences](https://docs.arc.io/arc/references/evm-differences) before building on Arc.

### SDKs
- [App Kit SDK](https://docs.arc.io/app-kit) - All-in-one SDK for transfers, crosschain bridging, swaps, and unified balance management.
- [App Kit SDK Reference](https://docs.arc.io/app-kit) - Describes the public interfaces, methods, and types available in the App Kit SDK.

### Tutorials
- [Porting Contracts to Arc](https://docs.arc.io/arc/tutorials/porting-contracts-to-arc) - Learn to migrate existing EVM smart contracts to Arc.
- [Integrating RainbowKit with Bridge Kit for crosschain USDC transfers](https://www.circle.com/blog/integrating-rainbowkit-with-bridge-kit-for-crosschain-usdc-transfers) - Learn to integrate RainbowKit and Bridge Kit for crosschain USDC transfers.
- [How to Build Real-Time Stablecoin FX in Your App with StableFX](https://www.circle.com/blog/how-to-build-real-time-stablecoin-fx-in-your-app-with-stablefx) - Learn to build real-time stablecoin FX in your app with Circle StableFX.
- [Tokenizing Real-World Assets with Circle Contracts](https://www.circle.com/blog/tokenizing-real-world-assets-with-circle-contracts) - Learn to tokenize real-world assets with Circle Contracts.
- [Choosing Between Circle Gateway and CCTP with Forwarding Service for Crosschain USDC](https://www.circle.com/blog/choosing-between-circle-gateway-and-cctp-with-forwarding-service-for-crosschain-usdc) - Learn when to use Circle Gateway or CCTP for crosschain USDC transfers.
- [Consolidate Crosschain USDC: Fast, Low-Cost Transfers with CCTP and Gateway](https://www.circle.com/blog/consolidate-crosschain-usdc-fast-low-cost-transfers-with-cctp-and-gateway) - Learn to consolidate crosschain USDC into a unified Arc Gateway balance.
- [Building a Gas-abstracted Crosschain USDC UX with Gateway and Gas Station](https://www.circle.com/blog/building-a-gas-abstracted-crosschain-usdc-ux-with-gateway-and-gas-station) - Learn to build a gas-abstracted crosschain USDC experience.
- [Build a Multichain Treasury System on Arc: The Fintech Starter](https://www.circle.com/blog/build-a-multichain-treasury-system-on-arc) - Learn to build a multichain treasury system on Arc.
- [Pay First, Settle Later with CCTP](https://www.circle.com/blog/pay-first-settle-later-with-cctp) - Learn how a local fulfiller can pay first and CCTP can settle reimbursement crosschain later from a platform treasury.

### Example Projects
- [Arc Lending Platform](https://github.com/circlefin/arc-defi-lend-borrow) - Demonstrates DeFi lending using cirBTC as collateral to borrow USDC on Arc.
- [Arc P2P Payment](https://docs.arc.io/build/sample-apps/arc-p2p-payments) - Demonstrates gasless peer-to-peer payments on Arc.
- [Arc Commerce](https://docs.arc.io/build/sample-apps/arc-commerce) - Demonstrates integrating USDC payments for purchasing credits on Arc.
- [Arc Multichain Wallet](https://docs.arc.io/build/sample-apps/arc-multichain-wallet) - Demonstrates a seamless crosschain USDC wallet experience with Arc and Circle Gateway.
- [Arc Fintech](https://docs.arc.io/build/sample-apps/arc-fintech) - Demonstrates a multichain treasury management system on Arc.
- [Arc Stablecoin FX](https://github.com/circlefin/arc-stablecoin-fx) - Demonstrates USDC and EURC stablecoin FX swaps using the App Kit's Swap SDK.
- [Arc Nanopayments](https://github.com/circlefin/arc-nanopayments) - Demonstrates gasless USDC nanopayments using Circle Nanopayments on Arc.
- [Arc Escrow](https://docs.arc.io/build/sample-apps/arc-escrow) - Demonstrates an end-to-end escrow workflow on Arc.
- [Arc Prediction Markets](https://github.com/circlefin/arc-prediction-markets) - Demonstrates a prediction market powered by UMA Protocol on Arc.

### Contract Templates
- [Deploy Contracts](https://docs.arc.io/arc/tutorials/deploy-contracts) - Provides pre-audited ERC-20, ERC-721, ERC-1155, and airdrop contract templates using Circle Contracts.
- [Interact with Contracts](https://docs.arc.io/arc/tutorials/interact-with-contracts) - Provides contract templates for interacting with ERC-20, ERC-721, and ERC-1155 contracts.

### Integration Guides
- [Exchange Integration](https://docs.arc.io/integrate/exchanges) - Explains how to integrate Arc into centralized exchanges.
- [On/Off-Ramp Integration](https://docs.arc.io/integrate/on-off-ramps) - Explains how to integrate Arc into fiat on-ramp and off-ramp platforms.
- [Wallet Integration](https://docs.arc.io/integrate/wallets) - Explains how to integrate Arc into wallet applications.
- [Infrastructure Integration](https://docs.arc.io/integrate/infrastructure) - Explains how to integrate Arc into blockchain infrastructure such as block explorers.
- [Bridge Integration](https://docs.arc.io/integrate/infrastructure/bridges) - Explains how to integrate Arc into crosschain bridge protocols.

### AI & Agents
- [AI skills for building on Arc](https://docs.arc.io/ai/skills) - AI coding skills for building on Arc with Circle's products, including USDC, agent wallets, crosschain transfers, and smart contracts.
- [Arc MCP server](https://docs.arc.io/ai/mcp) - Provides AI tools with direct access to Arc documentation for searching relevant content and retrieving full pages during conversations.
- [Register your first AI Agent](https://docs.arc.io/arc/tutorials/register-your-first-ai-agent) - Learn to register AI agents with onchain identities using ERC-8004 on Arc Testnet.
- [How to Prompt Claude with Circle Skills to Build a Crosschain USDC App](https://www.circle.com/blog/how-to-prompt-claude-with-circle-skills-to-build-a-crosschain-usdc-app) - Learn to build a crosschain USDC app with Claude and Circle Skills.
- [From Prompt to Deployment with Circle Skills and Vercel Skills](https://www.circle.com/blog/from-prompt-to-deployment-with-circle-skills-and-vercel-skills) - Learn to build and deploy apps with Circle Skills and Vercel Skills.
- [Build Agentic Systems for High-Frequency Sub-Cent Transactions](https://www.circle.com/blog/build-agentic-systems-for-high-frequency-sub-cent-transactions) - Learn to build agentic systems for high-frequency sub-cent payments.
- [Turn Your API into a Storefront for Agents](https://www.circle.com/blog/turn-your-api-into-a-storefront-for-agents) - Learn to monetize APIs with Gateway and USDC nanopayments.

## Research Papers
> Technical papers covering Arc's architecture, consensus, privacy, and security.

- [Arc Litepaper](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/Arc%20Litepaper%20-%202025.pdf) - Provides an overview of Arc's architecture, use cases, and roadmap. Also available in:
    - [Chinese](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/Arc-litepaper_chinese_simplified.pdf)
    - [Korean](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/Arc-litepaper_korean.pdf)
    - [Spanish](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/Arc-litepaper_spanish.pdf)
- [Arc Multi-Proposer Protocol with Bounded Inclusion Guarantees](https://arxiv.org/pdf/2605.23677) - Describes AMP, its design, and bounded inclusion guarantees.
- [AMP: Rethinking Block Building with Multi-Proposer Consensus](https://www.circle.com/blog/amp-rethinking-block-building-with-multi-proposer-consensus) - Provides an accessible overview of AMP for efficient block building.
- [Arc Whitepaper](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/PDFs/arc_whitepaper.pdf) - Explores the ARC token's role in security, governance, and network utility.
- [Introducing the Arc Whitepaper](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/PDFs/arc_whitepaper.pdf) - Provides a concise, non-technical overview of the ARC token.
- [Privacy Whitepaper](<https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/PDFs/Whitepapers/Arc_Privacy_Sector%20(5).pdf>) - Explores Arc Privacy Sector (APS) for confidential smart contract execution.
- [Post-Quantum Whitepaper](https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/PDFs/quantum_paper.pdf) - Explores Arc's roadmap for post-quantum security.

## Ecosystem Projects
> [!NOTE]
> This is a curated selection of Arc ecosystem projects and is **not** exhaustive. For the complete and up-to-date list of ecosystem projects, see the [official Arc Ecosystem page](https://www.arc.io/ecosystem).

### Analytics
- [Blockscout](https://www.blockscout.com) - Open-source blockchain explorer for EVM-compatible networks.
- [Chainalysis](https://www.chainalysis.com) - Blockchain intelligence platform for compliance, investigations, and risk monitoring.
- [Elliptic](https://www.elliptic.co) - Blockchain analytics platform for crypto compliance and forensic investigations.

### DeFi
- [Aave](https://aave.com) - Decentralized liquidity protocol for lending and borrowing digital assets.
- [Aerodrome](https://aero.drome.eth.limo) - Decentralized exchange on Base for token swaps and liquidity provision.
- [Curve](https://www.curve.finance) - Automated market maker (AMM) optimized for stablecoin and correlated asset trading.
- [GetLiquid](https://www.getliquid.io) - Infrastructure layer connecting lenders and borrowers in onchain private credit markets.
- [Maple](https://maple.finance) - Institutional onchain credit marketplace offering fixed-rate lending.
- [Morpho](https://morpho.org) - Decentralized lending protocol optimizing capital efficiency through peer-to-peer matching.
- [Superform](https://www.superform.xyz) - Onchain platform for sending, swapping, earning yield, and managing stablecoins and crypto assets.
- [Velodrome](https://velo.drome.eth.limo) - Decentralized exchange on OP Mainnet for token swaps and liquidity incentives.
- [Uniswap](https://app.uniswap.org) - Leading decentralized exchange enabling peer-to-peer token swaps.

### Exchanges
- [Bybit](https://www.bybit.com/en) - Cryptocurrency exchange for spot, derivatives, and digital asset trading.
- [Coinbase](https://www.coinbase.com) - Cryptocurrency exchange for buying, selling, trading, and staking digital assets.
- [Kraken](https://www.kraken.com) - Cryptocurrency exchange for spot trading, futures, staking, and institutional services.
- [Robinhood](https://robinhood.com) - Financial services platform for cryptocurrency and traditional asset trading.

### Infrastructure
- [Alchemy](https://www.alchemy.com) - Blockchain developer platform offering APIs, node infrastructure, and developer tooling.
- [AWS](https://aws.amazon.com) - Cloud computing platform providing scalable infrastructure and developer services.
- [Blockdaemon](https://www.blockdaemon.com) - Institutional blockchain infrastructure providing nodes, APIs, staking, and wallet services.
- [Cloudflare](https://www.cloudflare.com) - Connectivity cloud platform offering networking, security, and developer services.
- [dRPC](https://drpc.org) - High-performance RPC infrastructure and developer platform.
- [QuickNode](https://www.quicknode.com) - Decentralized RPC infrastructure for scalable Web3 applications.
- [Sequence](https://sequence.xyz) - Wallet infrastructure with embedded wallets and crosschain payments.
- [Turnkey](https://www.turnkey.com) - Secure wallet infrastructure and key management platform.

### Interoperability
- [Across](https://across.to) - Crosschain bridge for fast, low-cost asset transfers.
- [LayerZero](https://layerzero.network) - Omnichain interoperability protocol connecting blockchain applications.
- [Stargate](https://stargate.finance) - Crosschain liquidity transport protocol for seamless asset transfers.
- [Wormhole](https://wormhole.com) - Interoperability protocol connecting assets, applications, and data across blockchains.

### Oracles
- [Chainlink](https://chain.link) - Decentralized oracle network providing secure data feeds and crosschain interoperability.
- [Chronicle](https://chroniclelabs.org) - Oracle infrastructure for tokenized financial markets.
- [RedStone](https://www.redstone.finance) - Modular oracle network for DeFi and institutional applications.

### Payments
- [Bridge](https://www.bridge.xyz) - Stablecoin-native payments infrastructure for global money movement.
- [Catena](https://catena.com) - Banking and governance platform built for AI agents.
- [dLocal](https://www.dlocal.com) - Payment infrastructure platform enabling local payments and cross-border payouts in emerging markets.
- [Visa](https://usa.visa.com) - Global payments network connecting consumers, merchants, businesses, and financial institutions.
- [Corpay](https://www.corpay.com) - Global business payments company providing solutions for vendor, international, and employee payments.
- [EBANX](https://www.ebanx.com) - Payments platform connecting global businesses to local payment methods across emerging markets.
- [Noah](https://noah.io) - Stablecoin-powered payment infrastructure for global money movement.
- [Nuvei](https://www.nuvei.com) - Global payment technology platform for payment acceptance, payouts, and processing.
- [PhotonPay](https://www.photonpay.com) - Stablecoin-powered payment platform for global commerce.
- [Worldpay](https://www.worldpay.com/en) - Global payment processing and commerce technology company.
- [Yellow Card](https://yellowcard.io) - Stablecoin infrastructure platform enabling cross-border payments across Africa and other emerging markets.

### RWAs
- [BlackRock](https://www.blackrock.com/us/individual) - Leading asset manager bringing institutional investment products onchain.
- [Centrifuge](https://centrifuge.io) - Open infrastructure for tokenizing and managing real-world assets.
- [Securitize](https://securitize.io) - Institutional platform for issuing and managing tokenized real-world assets.

### Wallets
- [Crossmint](https://www.crossmint.com) - Platform for integrating wallets, stablecoins, and payment rails.
- [Fireblocks](https://www.fireblocks.com) - Enterprise platform for securely storing, transferring, and issuing digital assets.
- [MetaMask](https://metamask.io) - Self-custodial wallet and gateway to decentralized applications.
- [Privy](https://www.privy.io) - Authentication and embedded wallet infrastructure for Web3 applications.
- [Rainbow](https://rainbow.me) - Open-source, self-custodial Ethereum wallet for storing crypto assets and NFTs.

## Community Projects
> Highlights open-source projects and tools built by the Arc community.

> [!NOTE]
> Built an open-source project on Arc? We'd love to feature it! Before submitting a pull request, please review the [Contribution Guidelines](CONTRIBUTING.md#community-project-submission-guidelines).

## Contributing
Contributions are welcome! Please see the [Contribution Guidelines](CONTRIBUTING.md) for details on how to contribute.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [@0xBitzz](https://github.com/0xBitzz) has waived all copyright and related or neighboring rights to [Awesome Arc](https://github.com/0xBitzz/awesome-arc).

For the full license, see [LICENSE](LICENSE).
