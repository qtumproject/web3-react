# `qtum-web3-react` 🧰

_A simple, maximally extensible, dependency minimized framework for building modern [Qtum dApps](https://www.qtum.org/developers/documentations)_

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)


| Packages                              | `@latest` Version                                                                                                                                                         | Size                                                                                                                                                                                 | Description                                                                         |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| 🏠 **Core**                           |
| `@qtum-web3-react/core`                    | [![npm version](https://img.shields.io/npm/v/@web3-react/core/latest.svg)](https://www.npmjs.com/package/@qtum-web3-react/core/v/latest)                                       | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/core/latest.svg)](https://bundlephobia.com/result?p=@qtum-web3-react/core@latest)                                       | [React](https://reactjs.org/) Interface                                             |
| 🔌 **Connectors**                     |
| _Browser Extension/dApp Browser_      |
| `@qtum-web3-react/injected-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/injected-connector/latest.svg)](https://www.npmjs.com/package/@qtum-web3-react/injected-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/injected-connector/latest.svg)](https://bundlephobia.com/result?p=@qtum-web3-react/injected-connector@latest)           | [Injected](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1193.md) Connector |
| 🐉 **Low-Level**                      |
| `@qtum-web3-react/abstract-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/abstract-connector/latest.svg)](https://www.npmjs.com/package/@qtum-web3-react/abstract-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/abstract-connector/latest.svg)](https://bundlephobia.com/result?p=@qtum-web3-react/abstract-connector@latest)           | Shared Connector Class                                                              |
| `@qtum-web3-react/types`                   | [![npm version](https://img.shields.io/npm/v/@web3-react/types/latest.svg)](https://www.npmjs.com/package/@qtum-web3-react/types/v/latest)                                     | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/types/latest.svg)](https://bundlephobia.com/result?p=@qtum-web3-react/types@latest)                                     | Shared [TypeScript](https://www.typescriptlang.org/) Types                          |

## [Documentation](docs)

## Projects using `qtum-web3-react`

_Open a PR to add your project to the list!_

- [Qiswap.exchange](https://github.com/qiswapexchange/frontend_react)


## Local Development

- Clone repo\
  `git clone https://github.com/qtumproject/web3-react.git`

- Install top-level dependencies\
  `yarn`

- Install sub-dependencies\
  `yarn bootstrap`

- Build and watch for changes\
  `yarn start`
