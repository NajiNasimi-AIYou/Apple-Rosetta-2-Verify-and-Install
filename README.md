# Apple-Rosetta-2-Verify-and-Install
Detecting if Rosetta 2 is Installed on an Apple Silicon Mac

It first checks if the device architecture is Apple silicon (arm64), then checks if the system is able to run x86_64 intel code using the arch binary. It follows that if an Apple silicon device can run intel code, Rosetta 2 must be installed. If Rosetta 2 is not installed, it will then go ahead and install it.

Upcoming Features:
* Interactability
