# Uniswap Labs Widgets

[![npm](https://img.shields.io/npm/v/@dex-swap/widgets)](https://www.npmjs.com/package/@dex-swap/widgets)
[![Crowdin](https://badges.crowdin.net/uniswap-interface/localized.svg)](https://crowdin.com/project/uniswap-interface)

The `@dex-swap/widgets` package is an [npm package](https://www.npmjs.com/package/@dex-swap/widgets) of React components used to provide subsets of the Uniswap Protocol functionality in a small and configurable user interface element.

## New Demo Chain

Here is the rpc and account info:

```
CHAIN_ID=412346
RPC_URL="http://localhost:8547"
PRIVATE_KEY=""
ACCOUNT_ADDRESS=0x3f1Eae7D46d88F08fc2F8ed27FCb2AB183EB2d0E
```

These are contract addresses. The token contracts are already funded:

```
Deployed ERC20 contract 1 at address: 0xCe5303b8e8BFCa9d1857976F300fb29928522c6F
Deployed ERC20 contract 2 at address: 0x1D55838a9EC169488D360783D65e6CD985007b72
Deployed Router contract at address: 0xD92773693917F0fF664f85c3cB698c33420947ff
```

# Uniswap Labs Swap Widget

The Swap Widget bundles the whole swapping experience into a single React component that developers can easily embed in their app with one line of code. 

![swap widget screenshot](https://raw.githubusercontent.com/bullishgopher/uniswap-widgets/main/sc.png)

You can customize the theme (colors, fonts, border radius, and more) to match the style of your application. You can also configure your own default token list and optionally set a convenience fee on swaps executed through the widget on your site.

## Installation

Install the widgets library via `npm` or `yarn`.

```js
yarn add @dex-swap/widgets
```
```js
npm i --save @dex-swap/widgets
```

## Documentation

- [overview](https://docs.uniswap.org/sdk/widgets/swap-widget)
- [api reference](https://docs.uniswap.org/sdk/widgets/swap-widget/api)

## Example Apps

Uniswap Labs maintains two demo apps in branches of the [widgets-demo](https://github.com/Uniswap/widgets-demo) repo:

- [NextJS](https://github.com/Uniswap/widgets-demo/tree/nextjs)
- [Create React App](https://github.com/Uniswap/widgets-demo/tree/cra)

Others have also also released the widget in production to their userbase:

- [OpenSea](https://opensea.io/)
- [Friends With Benefits](https://www.fwb.help/)
- [Oasis](https://oasis.app/)

## Legal notice

Uniswap Labs encourages integrators to evaluate their own regulatory obligations when integrating this widget into their products, including, but not limited to, those related to economic or trade sanctions compliance.
