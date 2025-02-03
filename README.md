# BSA 2025 dApp Starter Template

Welcome to the [BSA](https://bsaepfl.ch/) Hackathon Official Starter Pack ! This kit should provide you with tons of tools to make your hackathon experience seamless and easy, so ou can focus on what you do best ! 

This starter pack was made by BSA comitee member [Loris](https://github.com/Loris-EPFL) and modified by [Guillaume](https://github.com/GuillaumeLepin), feel free to contact me for any questions, bug reports, etc...

This dApp was created using `@mysten/create-dapp` that sets up a basic React
Client dApp using the following tools:

- [React](https://react.dev/) as the UI framework
- [TypeScript](https://www.typescriptlang.org/) for type checking
- [Vite](https://vitejs.dev/) for build tooling
- [TailwindCSS](https://tailwindcss.com/) for styling classes
- [Daisy UI](https://daisyui.com/) for pre-built UI components
- [ESLint](https://eslint.org/) for linting
- [`@mysten/dapp-kit`](https://sdk.mystenlabs.com/dapp-kit) for connecting to
  wallets and loading data
- [pnpm](https://pnpm.io/) for package management

IMPORTANT ! : To select your desired network for the dapp, create a .env file at the root of the project, add either VITE_NETWORK="testnet" for testnet or VITE_NETWORK="mainnet" for mainnet. Dapp default to testnet if no .env file is provided.


## Starting your dApp

To install dependencies you can run

```bash
pnpm install
```

To start your dApp in development mode run

```bash
pnpm dev
```

## Building

To build your app for deployment you can run

```bash
pnpm build
```
