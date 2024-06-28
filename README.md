# Decentralized CAS using P2P with Golang

This project is an implementation of a Decentralized Content Addressable Storage (CAS) system using Peer-to-Peer (P2P) networking in Golang. The system allows peers to store and retrieve data efficiently without relying on a central server.
## Features

- **Decentralized Storage**: Data is stored across multiple peers in the network.
- **Content Addressable**: Files are accessed using their hash, ensuring data integrity.
- **Peer-to-Peer Networking**: No central server; peers communicate directly with each other.
- **Distributed Hash Table (DHT)**: Efficient peer discovery and data lookup. TODO

## Getting Started

### Prerequisites

- Go 1.16 or higher

### Installation

```bash
git clone https://github.com/mexirica/casp2p.git
cd casp2p
make run
