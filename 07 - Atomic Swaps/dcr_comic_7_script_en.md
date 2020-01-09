01

**Atomic** **Swaps** are **trustless cross-chain transactions**. How do they work?

They ensure both users get their funds by using two time-locked contracts that require the same secret, but different signatures to be redeemed.

02

To allow Atomic Swaps, both chains must support branched transactions, signature checks, a way of timelocking coins and share a hashing function.

03

To begin, the **initiator** sends coins to a smart contract using the **participant**'s address, but securing it with a secret.

04

Then the **initiator** shares with the **participant** the secret **hash**, the contract and the contract transaction.

05

The **participant** must audit the contract and make sure it uses her address, has the coins they agreed and is locked for more then 48hs. 

If everything is fine, she publishes a similar contract on the other chain using the same **secret** **hash**.

06

The **initiator** then audits the second contract. If everything is ok, the **initiator** can redeem the funds, revealing the secret. Because the secret in now public, the **participant** can also redeem his funds using her signature.

07

If something goes wrong, both can get their funds back after 48 hours, when the timelock expires.

08

Atomic Swaps are already here. Decred has built a command line app tool that makes it easy for anyone to make P2P cross-chain transactions with complete strangers in the cyberspace!
