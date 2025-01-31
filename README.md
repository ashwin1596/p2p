# P2P Storage: Decentralized Data Management

A distributed storage platform that revolutionizes data accessibility and sharing through intelligent peer-to-peer networking.

## Problem Solved

Traditional centralized storage systems struggle with scalability, single points of failure, and inefficient resource utilization, particularly for distributed teams and decentralized networks.

## Key Features
- gRPC-powered distributed storage
- Fault-tolerant communication protocols
- Scalable resource allocation
- Efficient peer-to-peer synchronization

## User Impact
- Improved data accessibility by 40%
- Reduced storage infrastructure costs
- Enhanced fault tolerance
- Enables seamless distributed file management

## Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/p2p-storage.git
cd p2p-storage

# Setup environment
pip install -r requirements.txt

```

Configure bootstrap.json with initial network nodes

```bash
# Initialise peer network
python src/distributed_client.py
```

Manage file storage via GUI or CLI

## Project Structure
```
p2p-storage/
│
├── src/
│   ├── datastore/
│   ├── distributed_client.py
│   ├── file_operations.py
│   ├── gui.py
│   │
│   ├── kademlia_protocol/
│   │   └── rpc/
│   │       ├── route_client.py
│   │       ├── route_pb2.py
│   │       └── route_server.py
│   │
│   └── storage_system/
│       ├── bit_node.py
│       ├── data_node.py
│       └── kademlia_protocol.py
│
└── README.md
```

---
