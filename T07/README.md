# Task7 - Developer Profiles DApp powered by Nervos Network
<small> You can either create new developer profiles to add Nervos Network or like existing profiles </small>

### 1- Video && Screenshot

- Project Video
 
https://user-images.githubusercontent.com/89727349/131248580-d5b8e594-8f4b-47f8-9997-c3ae647ec5ee.mp4

- Project Screenshots

<img src="https://github.com/micheledurden43/Gitcoin-Nervos-Hack/blob/master/T07/1.png" />
<br/>
<hr/>
<br/>

<img src="https://github.com/micheledurden43/Gitcoin-Nervos-Hack/blob/master/T07/2.png" />

### 2- Project Source Code

<a href="https://github.com/micheledurden43/Dev-Profiles-Dapp"> Source Code of the DApp </a>

### 3- Transaction Hash || Deployed Contract Address || ABI of the contract

Transaction Hash
```bash
0xcd4efa655ba7476f358d8722840d7e87d35e37642dbd7e7eb09b36c860d5ef66
```

Deployed Contract Address
```bash
0x67af743000c08943F754D7AA475d83D7bdd417Eb
```

ABI of the contract
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
