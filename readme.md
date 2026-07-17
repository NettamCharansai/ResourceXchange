# ResourceXchange

A decentralized, peer-to-peer computing platform designed to optimize high-RAM task distribution and scale data-intensive workloads across a network of idle devices.

This project bypasses traditional, expensive cloud infrastructure by enabling local-first data sharing and RAM pooling, creating a scalable and cost-effective alternative for compute-heavy operations like machine learning and simulations.

## ⚙️ System Architecture & Tech Stack

* **Frontend:** React.js for dynamic user interfaces and node management.
* **Backend:** Python / Flask handling API routing and core compute logic.
* **Database:** MySQL for managing user states, node availability, and ledger tracking.
* **Networking:** Scapy for network scanning, device discovery, and secure cross-device communication.
* **AI Integration:** Google GenAI for dynamic resource allocation and intelligent workload routing.

## 🚀 Core Capabilities

* **RAM Pooling:** Intelligently splits high-memory tasks across multiple network devices to parallelize execution and minimize cloud dependency.
* **Dynamic Resource Allocation:** Monitors idle resources in real-time to prevent network bottlenecks and optimize system efficiency.
* **Local-First P2P Sharing:** Drastically reduces latency and operational costs for data-heavy workloads by utilizing local network topologies.

## 🛠️ Local Development Setup

### 1. Backend Environment Setup
```bash
# Navigate to the project directory
cd ResourceXchange

# Create and activate a Python virtual environment
python -m venv my_env
source my_env/bin/activate  # On Windows use: my_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt