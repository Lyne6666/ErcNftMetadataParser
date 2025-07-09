# ErcNftMetadataParser

## Description

A smart contract suite implementing a novel NFT fractionalization and dynamic royalty distribution mechanism using on-chain verifiable random functions (VRFs) to incentivize creator participation.

## Features

- Fetches ERC-721 and ERC-1155 metadata from on-chain storage using optimized gas strategies.
- Parses metadata attributes from various formats including JSON, URI, and decentralized storage protocols like IPFS.
- Validates metadata schema against predefined standards and custom user-defined rules.
- Caches parsed metadata locally with configurable expiration policies to minimize blockchain interactions.
- Integrates with popular NFT marketplaces APIs (e.g., OpenSea, Rarible) to enrich metadata with external data.
- Supports asynchronous metadata fetching and processing using a message queue for scalability.
- Exposes a GraphQL API for querying and filtering NFT metadata based on specific attributes.
- Generates previews of NFT assets (images, videos, audio) from metadata using FFmpeg and ImageMagick.
## Installation

```bash
pip install git+https://github.com/Lyne6666/ErcNftMetadataParser.git
```

## Usage

```bash
python -m ercnftmetadataparser --verbose
```

## Contributing

We welcome contributions! Here's how to get started:

1. Fork this repository
2. Create a new branch for your feature (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some awesome feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
