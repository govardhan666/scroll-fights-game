# SCROLL💪FIGHTS
Buy weapons and battle with other scroll NFTs.

⚙️ Built using NextJS, Alchemy, RainbowKit, Hardhat, Wagmi, and Typescript.

Deployed smart contract on scroll sepolia testnet : https://sepolia.scrollscan.com/address/0x0cad79e1699b3422e49344fe69c3d814771cf443

Alchemy usage: I deployed my project on Scroll sepolia and also I leveraged the Alchemy RPC via the Scroll API. You can go through `hardhat.config.ts` file of this project to find more about usage of Alchemy in Scroll💪Fights Game.

## Welcome to SCROLL💪FIGHTS Homepage

![Screenshot_30-9-2024_172926_localhost](https://github.com/user-attachments/assets/1f9eeab7-04be-46ca-ab91-63324fc1ae20)

## Marketplace page

![Screenshot_30-9-2024_172943_localhost](https://github.com/user-attachments/assets/8baddaa5-9f69-4d8a-9b3e-946318f0e1b4)

## Gameplay page

![Screenshot_30-9-2024_17306_localhost](https://github.com/user-attachments/assets/6cddde3e-c602-46ee-bd21-36fecc43f884)

## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with SCROLL💪FIGHTS, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/govardhan666/scroll-fights-game
cd scroll-fights-game
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/scaffold.config.ts`.

# Thank you for visiting SCROLL💪FIGHTS game.
