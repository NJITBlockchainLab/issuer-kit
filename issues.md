1. AUTHTOKEN error in ngrok. Issue fixed added environment Variable
    In main directory add .env file. And add NGROK_AUTH_TOKEN variable
2. ./manage rm if testing multiple versions to delete container data
3. For connecting to hosted ledger create .env in docker directory. Add variables
    ACAPY_WALLET_SEED and LEDGER_URL. Add the IP of the hosted ledger or set it
    to localhost for local development.