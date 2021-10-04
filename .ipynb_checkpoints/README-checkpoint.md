# Blockchain-Project

This project is built on the Ethereum blockchain.  It is an example how to build a Proof of Authority algorithm on the Ethereum network.  It then used to nodes to mine Ether and uses the MyCrypto wallet to send and receive transactions on that blockchain network. 

## Technologies
This use project uses Go Ethereum version 1.9.7 and My Cryptowallet running on Windows 10. 

## Libraries Uses
    Puppeth - this is used to setup the network to run the blockchain 
    Geth 1.9.7 - used to create nodes and start mining blocks
    MyCrypto - used to link the wallet from the custom Ethereum network and used to view balances, send and receive transactions. 
    
## Installation Guide
This needs a MyCrypto wallet and Go Ethereum and All Tools version 1.9.7

## Examples
![](./Screenshots/transaction.JPG)
![](./Screenshots/txstatus.JPG) 

## Usage

To send a transaction: type in the address that you are sending it to and then select the amount of money that you want to send.  Click the transactions and send it.  It will give you a hash that you can use to look up and verify the transaction. 

## Contributors
Ryan Dibeler

ryandibeler@gmail.com

## License
MIT License

Copyright (c) [2021] [Ryan Dibeler]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
