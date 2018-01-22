Yarn caches every package it downloads so it never needs to download it again. It also parallelizes operations to maximize resource utilization so install times are faster than ever.

Yarn uses checksums to verify the integrity of every installed package before its code is executed.

Test that Yarn is installed by running:

docker run jerob/node-yarn yarn --version
