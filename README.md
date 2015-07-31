
Copyright (c) 2014-2015 Axiom Developers  
Copyright (c) 2014-2015 Blackcoin Developers  
Copyright (c) 2013-2015 NovaCoin Developers  
Copyright (c) 2011-2015 PPCoin Developers  
Copyright (c) 2009-2015 Bitcoin Developers  


Axiom
===================
**Axiom** is a hybrid Proof of Work and Proof of Stake cryptocurrency.


Axiom is a cutting edge digital network designed to provide novel
solutions to the deficiencies of the current generation of cryptocurrencies.

Proof of work calculations are hashed with the unique AxiomHash, which
is based on Sergio Lerner's RandMemoHash, described in the paper:

"STRICT MEMORY HARD HASHING FUNCTIONS (PRELIMINARY V0.3, 01-19-14)"

https://bitslog.files.wordpress.com/2013/12/memohash-v0-3.pdf

Shabal-256 is used for creating transactions and non-POW hashing.


Schnorr signatures have been integrated by using the work in secp256k1 (modified Schnorr signatures) that is not yet integrated with Bitcoin.

The Schnorr patent has expired and this is the first step in moving away from ECDSA and the oddball curve used by Bitcoin and all of its clones.


More information about Schnorr signatures and the discussion around moving Bitcoin to them can be found here:

http://bitcoin.stackexchange.com/questions/34288/what-are-the-implications-of-schnorr-signatures

This implementation is of course experimental, and we will be making additional code improvements over time for enhanced security and performance.



#####For more information, please see our BitcoinTalk forum thread or website.

https://bitcointalk.org/index.php?topic=1135151.0
http://axiomcrypto.org


###Development process


Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Axiom.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be
labeled 'stale'.

[![](https://i.imgur.com/MisSNti.png)](http://axiomcrypto.org)
