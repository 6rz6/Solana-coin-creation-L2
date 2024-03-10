# Solana blockchain coin creation guide for begginrs 
# (7 minutes quick guide)
A complete guide and links to how create and manage alt coins, tokens and meme coins on the Solana Blockchain L2 with almost zero coding.

1. first a linux running machine is required, i use ubuntu linux on windows WSL2 and also on using paperspace (which offer unlimited strong GPU servers with 8 CPU and 30-45GB RAM for **free**)
2. next install conda and create a new venv -> ```conda create --name L2env``` -> next activate the L2env -> ```conda activate L2env``` 
3. open an account at Alchemy.com (fast and free)
4. once you have created your account you will get an api key and 4 options to connect to their api, choose the one which fits you most.
5. I choose the command line ```curl https://arb-mainnet.g.alchemy....```
6. next get your api keys for the chain you like, scroll down to see all chains.
7. I choose solana and got and API key, HTTPS link and Websocket link. below there is code to copy paste to check the api works.
8. ```
   curl https://solana-mainnet.g.alchemy.com/v2/cmqJEH0UZ8LWKVhWkjThNK_sLMHDC3RA \
    -X POST \
    -H "Content-Type: application/json" \
    -d '{"id": 1, "jsonrpc": "2.0", "method": "getBlockProduction"}' 
  ```
9.
