# cuda-miner
Funakoshi Equihash Cuda Miner

## Can be used for mining:

     All equihash crypto coins: zcash (ZEC), ZClassic (ZCL), ...
     via any of the supported pools (using SSL ports).

## No Virus attached:

    Ask McAfee

## Developer fee:

    1.5 %

## Speed:

    Over 500 solves per-second for GTX 1080 (without overclocking).
    
    Nvidia Pascal GPUs auto manage the clock depending on current load.
    
    Note: The statistical nature of the EquiHash algorithm causes
    the reported solves per second to change all the time.
    
    Each 15 seconds, Funakoshi solver logs its counters of hashes/secs and solves/secs (no cheating).
    
    What's important to you is the pool measurement. From the pool you earn your money.
    Thus when you want to compare the speed of different miner programs ask the pool.
    Note that the pool also changes its estimation of miner speed all the time. So,
    you should take the avarage over time.
    
    The miner submits to the pool only a small portion of the solves (depending
    on the current target difficulty), and the pool estimates the miner speed.
    Each submit event is logged.
    
    Exactly 1.5 percent of all submited solves are used as developer fee.

## Supported pools:

    * Slushpool
    * Supernova
    * Flypool
    * Nanopool
    * Miningspeed
    * Coinmine
    * Miningpoolhub
    * Nibirupool

_**Note:** Only secured ports (SSL connections) are supported._
 
## Supported Operating Systems:

     * Windows7 and above  (file: funakoshiMiner.exe)
     * Some Linux distributions  (file: funakoshiMiner)

## Tested on:

    * Windows7, 10 
    * Ubuntu 16.4, 17.10
    * Fedora 26, 27

## Not working on:

    * Centos 6, 7

## Supported GPUs:

    * Nvidia Pascal and above

## Tested GPUs:

    * Nvidia GTX 1070
    * Nvidia GTX 1080
    * Nvidia GTX 1080 Ti

## Usage example (on Linux & via Slushpool & using 1 Nvidia device):

    funakoshiMiner -cd 0 -l zec.slushpool.com:4443 -u userName.workerName

## Usage example (on Linux & via Supernova & using 1 Nvidia device & max GPU temperature):

    funakoshiMiner -cd 0 -l zec.suprnova.cc:2242 -u userName.workerName -temp-max 82 -temp-min 75

## Usage example (on Windows & via Flypool Europe server & using 3 Nvidia devices):

    funakoshiMiner.exe -cd 0 1 2 -l eu1-zcash.flypool.org:3443 -u tYourWalletAddress.workerName

## Usage example (on Linux & via Nanopool Europe server & using 2 Nvidia devices):

    funakoshiMiner -cd 0 1 -l zec-eu1.nanopool.org:6633 -u tYouWalletAddress.workerName

## Usage example (on Linux & Mining ZClassic via Miningspeed US server & using 3 Nvidia devices):

    funakoshiMiner -cd 0 1 2 -l us.miningspeed.com:3054 -u tYouWalletAddress.workerName

## Usage example (on Windows & Mining ZClassic via Coinmine & using 4 Nvidia devices):

    funakoshiMiner.exe -cd 0 1 2 3 -l zcl.coinmine.pl:7017 -u userName.workerName

## Usage example (on Windows & via Miningpoolhub US-East server & using 4 Nvidia devices):

    funakoshiMiner.exe -cd 0 1 2 3 -l us-east.equihash-hub.miningpoolhub.com:20570 -u userName.workerName

## Usage example (on Windows & Mining ZEN via Nibirupool  & using 4 Nvidia devices):

    funakoshiMiner.exe -cd 0 1 2 3 -l zen.nibirupool.com:7777 -u tYourWalletAddress.workerName
