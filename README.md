WinCoin (WIN) is an advanced PoW/PoS coin with X11 hash algorithm. It uses the innovative PoW and PoS separated technologies and true random superblocks. With shorter PoS block time the transactions are confirmed with light fast speed (usually less than 1 minute), and the generation of PoS has no effect on the PoW mining - a defect most of the previous PoW/PoS coins have.

WinCoin is a true winner among the alt coins! Below are the detailed specifications:

- X11 hash algorithm
- PoW/PoS independent
- 4 transaction confirmations (<= 1min on average)
- 50 minted block confirmations

PoW
- 90 sec PoW block time
- diff retarget each block for PoW
- Initial payout will be 1000 coins per block
- Daily random superblock payout 10X normal payment
- Weekly random superblock payout 100X normal payment
- True random, so no cheating by someone with big hashpowers
- block payout will be reduced by 20% every 20 days (will be halved at approximately every 2 months).
- minimum PoW payout for will be 1 coin/block (will be reached after about 2 years - 620 days to be precise)

PoS
- 15 sec PoS block time
- diff retarget each block for PoS
- minimum hold for PoS: 1 day
- maximum hold for PoS (over which coin-day no longer accumulates): 100 days
- Variable PoS payout:
	- 1st year:  30%
	- 2nd year: 20%
	- 3rd year: 10%
	- 4th year: 5%
	- 5th year and on: 2%

- Total coins will be approximately 250 millions.

Ports: 
18330 (connection)
18331 (RPC)


Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Dreamcoin.

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
