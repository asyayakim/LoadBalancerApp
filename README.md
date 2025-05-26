# Load Balancer Simulation in C#

A demonstration of different load balancing strategies with server capacity tracking.
## Features
- Three load distribution algorithms:
  - Round-Robin
  - Least Connections
  - IP Hashing
- Server request tracking
- Client IP simulation

## Load Balancing Strategies

| Strategy              | Method                      | Characteristics                     |
|-----------------------|-----------------------------|-------------------------------------|
| **Round-Robin**       | Cyclic server selection     | Even distribution, simple          |
| **Least Connections** | Lowest request count        | Dynamic workload balancing          |
| **IP Hashing**        | Client IP-based hashing     | Session persistence                 |
