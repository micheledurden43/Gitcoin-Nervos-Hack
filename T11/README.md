# TASK 11 - Use A Tron Wallet To Execute A Smart Contract Call

### 1- A screenshot of the accounts you created

<img src="https://github.com/micheledurden43/Gitcoin-Nervos-Hack/blob/master/T11/accounts.png" />

### 2- A link to the Layer 1 address you funded on the Testnet Explorer

- <a href="https://explorer.nervos.org/aggron/address/ckt1qyq0vaxmp2mz5yje80f6h8tuuq5a3p3x3l4qdvhlkc">Funded Account Address </a>

### 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/micheledurden43/Gitcoin-Nervos-Hack/blob/master/T11/depst.png" />

### 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

- <small> Take a look the "like" property of the read call result. It increased by 1 </small>


<img src="https://github.com/micheledurden43/Gitcoin-Nervos-Hack/blob/master/T11/result.png" />

### 5- The transaction hash from the console output

- Write call transaction hash:

```bash
0x4544a2f6abcd59bf598d19ca3522eb0cc21c01cb489ab33ee6040d49cebe477e
```


### 6- The contract address that you called

```bash
0x67af743000c08943F754D7AA475d83D7bdd417Eb
```
### 7- The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [],
      "name": "totalWorker",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "workers",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "title",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "description",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "likes",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_name",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_title",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_descr",
          "type": "string"
        }
      ],
      "name": "createNewProfile",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_id",
          "type": "uint256"
        }
      ],
      "name": "likeProfile",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getAllWorkers",
      "outputs": [
        {
          "components": [
            {
              "internalType": "uint256",
              "name": "id",
              "type": "uint256"
            },
            {
              "internalType": "string",
              "name": "name",
              "type": "string"
            },
            {
              "internalType": "string",
              "name": "title",
              "type": "string"
            },
            {
              "internalType": "string",
              "name": "description",
              "type": "string"
            },
            {
              "internalType": "uint256",
              "name": "likes",
              "type": "uint256"
            }
          ],
          "internalType": "struct Profile.Worker[]",
          "name": "",
          "type": "tuple[]"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]

```

### 8- Your Tron address

```bash
TXQSjfVXKt2Bi3bSpDL1sQ2swyfhuJgCVe
```
