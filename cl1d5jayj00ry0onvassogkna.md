## Ronin network - Axie infinity lost 173,600 ETH and 25.5M USDC - what is your hypothesis?


# Summary:

- March 29th: The Sky Mavis team discovered the security breach after a report that a user was unable to withdraw 5k ETH from the bridge.
- The validator key scheme is set up to be decentralized so that it limits an attack vector, similar to this one, but the attacker found a backdoor through our gas-free RPC node, which they abused to get the signature for the Axie DAO validator.
- Five validator private keys were hacked; 4 Sky Mavis validators and 1 Axie DAO.
- Once the attacker got access to Sky Mavis systems they were able to get the signature from the Axie DAO validator by using the gas-free RPC.
- They confirmed that the signature in the malicious withdrawals matches up with the five suspected validators.

# My notes:
It does look like a 51% attack in real life and with the largest scale ever to me (about 625 millions USD today rate)
9 nodes is too little (4 nodes are internal..??)
I am discussing with my dev friends and will updating here!

 [Original source](https://roninblockchain.substack.com/p/community-alert-ronin-validators?s=w&fbclid=IwAR0OzWPQ-o4SoH3N-NjUxJgBWa1oLYqrbDO4PUYkMeFJpUecL8m5lbX2C_g)