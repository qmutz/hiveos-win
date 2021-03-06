Bminer: When Crypto-mining Made *Fast*
======================================

Bminer is a highly optimized cryptocurrency miner that runs on modern NVIDIA GPUs (Maxwell and Pascal, i.e. GPUs that have compute capability 5.0 or above). Bminer is one of the *fastest* publicly available miners today -- we use various techniques including tiling and pipelining to realize the full potentials of the hardware.

Bminer also comes with REST APIs to facilitate production deployments (e.g., mining farms).

Bminer currently supports mining Equihash-based coins (e.g., Zcash) with 2% of devfee. It also provides experimental supports for Ethash-based coins (e.g., Ethereum) with 0.65% of devfee.

Features
========

  * Fast
    * Equihash on stock settings:
    * 735-745 Sol/s on GTX 1080Ti
    * 450-460 Sol/s on GTX 1070
    * 315-325 Sol/s on GTX 1060
  * Secure and reliable
    * SSL support
    * Automatic reconnects to recover from transient network failures
    * Automatic restarts if GPUs hang
  * Operation friendly
    * Comes with REST APIs to facilitate production deployments

Quickstart
==========

To mine [Zcash](https://z.cash) on Windows on [nanopool](https://zec.nanopool.org/):

  * Download and extract Bminer into a folder (e.g. C:\bminer)
  * Edit mine.bat and change the address to the desired Zcash address that Bminer mines towards
  * Open command line prompt and run mine.bat.
  * Enjoy mining :-)

To mine [Ethereum](https://www.ethereum.org/) on Windows on [ethermine.org](https://ethermine.org/):

  * Download and extract Bminer into a folder (e.g. C:\bminer)
  * Edit mine.bat and change the parameters according to https://www.bminer.me.
  * Open command line prompt and run mine.bat.
  * Enjoy mining :-)


Please see https://www.bminer.me for advanced usages, APIs and updates.
