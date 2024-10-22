# IoTeX Desktop Wallet

Desktop wallet for the IoTeX network, built with Electron.

## About

IoTeX Desktop Wallet is a desktop application for interacting with the IoTeX network.

The wallet connects to the IoTeX network using [IoTeX Antenna](https://github.com/iotexproject/iotex-antenna), the IoTeX Chain SDK.

## Download

Pre-built versions of IoTeX Desktop Wallet are available on the [Releases](https://github.com/iotex-team/iotex-desktop-wallet/releases) page.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/iotex-team/iotex-desktop-wallet.git
cd iotex-desktop-wallet
```

Install the project dependencies:

```bash
yarn install
```

## Development

The Electron application source code is located in [`src/electron`](src/electron).

Start the application:

```bash
yarn start
```

Run the development watcher:

```bash
yarn watch
```

## Building from Source

Build the project:

```bash
yarn build
```

Create a production build:

```bash
yarn build-production
```

## Testing

Run the test suite:

```bash
yarn test
```

## Releases

Release builds and version history are available on the [GitHub Releases](https://github.com/iotex-team/iotex-desktop-wallet/releases) page.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
