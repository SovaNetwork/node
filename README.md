# Sova Node

This repository contains Docker builds to run your own node on the Sova network.

> NOTE: Only Sepolia Testnet is currently supported

## Quickstart
1. Ensure you have an Ethereum L1 full node RPC available
2. Choose your network:
    - For mainnet: Use .env.mainnet
    - For testnet: Use .env.sepolia
3. Configure the `ALCHEMY_L1_RPC_URL` in the appropriate .env file.
4. Generate your own `config/jwt.txt` file.
5. Start the node:
```bash
docker compose --env-file .env.sepolia up --build -d
```

