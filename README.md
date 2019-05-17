# mql4-BlockTrailer
This MT4 Expert Advsior is to facilitate order SL trailing by block.

This EA is made for StackOverflow question https://stackoverflow.com/questions/56177003/how-to-keep-a-10-pip-profit-gap-between-stop-loss-and-current-price-as-profits-i

Example:
viProfitToActivateBlockTrailInPip=100, viTrailShiftProfitBlockInPip=30, viTrailShiftOnProfitInPip=20.

The Block-Trailing will start when order is floating-profit by 130 pips (100+30). SL will be set to guarantee 20pip profit.
When floating-profit reach 160pips (100+30+30), SL will be set to guarantee 40pips (2x20pips).

I am putting this into GitHub so that everyone can use it, and for others to build and improve upon it.


DONATION: If this is useful to you, please send a donation to:
Ether 0xf635118870abe8fd904551a6fb3bb689d10ecec7
Bitcoin 1Ep1zvNnDPd2trhGMfHtALjFNBxvD82gku
