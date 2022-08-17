# 🎏 Why Did My Deposit Include Two Amounts on the Blockchain?

When you look at your transaction on a block explorer, you may see multiple outputs. This is because multiple coin transfers can occur in one block (and typically do), or under one transaction ID. Within the BTC protocol, there is are addresses called the "change" addresses that serve a vital function in returning unspent funds to a wallet.

\


![](<../../../.gitbook/assets/image (150).png>)

As you will see above, there are two unspent amounts. One of these is the _change address_. That means that while it is going to a new address, that address belongs to the user and is accessible via their wallet.

When the Bitcoin network has to make change, it has to give it back to you somehow, similar to the way that would happen if you exchanged cash for services but you overspent. The best way for the network to do this is by using the change address.

Learn more about UTXOs and Change addresses [**here.**](https://www.cryptocompare.com/mining/guides/bitcoin-transaction-inputs-and-outputs/)
