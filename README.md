# CodeRed GUI Wallet
 * <b>Coin Info</b>
 * Supply: 5,000,000 CR
 * PoW algorithm: CryptoNight
 * Block reward: Smoothly varying
 * Block time: 180 seconds
 * Difficulty: Retargets at every block

<br>

* <b>Ubuntu Build</b><br>
<b>Dependencies:</b> GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

* <b>You may download them from:</b><br>
    http://gcc.gnu.org/<br>
    http://www.cmake.org/<br>
    http://www.boost.org/<br>
* <i>Alternatively, it may be possible to install them using a package manager</i>
* Easy install dependencies: `sudo apt-get update && sudo apt-get install build-essential libboost-all-dev libboost-all-dev cmake qt5-default git`
* Clone Repository: `git clone https://github.com/codered-project/codered-gui.git && cd codered-gui`
* `make`

* <b>Advanced options:</b>
* Set threads, <b>x</b> is the number of threads your system has: `make -j x`
* Debug build: `make build-debug`
* Test suite: `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.

