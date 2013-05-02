![Gitcoin](http://i.imgur.com/bnM0kon.png)
================================

What is Gitcoin?
----------------

Gitcoin is an implementation of the Bitcoin protocol that makes use of Git revision control to manage the block chain.

The Bitcoin [block chain](https://en.bitcoin.it/wiki/Block_chain) is a Git repository, with each commit being an individual [block](https://en.bitcoin.it/wiki/Block).

Why Bitcoin and Git?
----------------

Bitcoin and Git have many similarities:

| Bitcoin       | Git           |
| :-------------:|:-------------:|
| Open source software released under the [MIT license](http://creativecommons.org/licenses/MIT/).     | Open source software released under the [GPLv2 license](https://gnu.org/licenses/gpl.html).      |
| Decentralized & distributed P2P system.     | Decentralized & distributed P2P system. |
| Assumes branching and trusted sources. | Assumes branching and trusted sources.      |
| Cryptographic authentication of block history. | Cryptographic authentication of commit history.      |

***

#On Cryptographic Authentication of History

**Cryptographic authentication of block history**:

>Every block contains a hash of the previous block. This has the effect of creating a chain of blocks from the genesis block to the current block. Each block is guaranteed to come after the previous block chronologically because the previous block's hash would otherwise not be known. Each block is also computationally impractical to modify once it has been in the chain for a while because every block after it would also have to be regenerated.

**Cryptographic authentication of commit history**:

>The Git history is stored in such a way that the ID of a particular commit depends upon the complete development history leading up to that commit. Once it is published, it is not possible to change the old versions without it being noticed.

