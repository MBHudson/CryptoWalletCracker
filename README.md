---
# Mass Crypto Wallet Cracker
---
---
## Installation: 
<b><i>System Requirements</i></b>
- Minimum 4gb RAM
- i7 Intel Processor 
- 4gb Free Space
- ~~Internet Connection~~
- Linux OS (Debian 10+/Ubuntu 18+)
---
<b><i>Copy/Past into a terminal and press the ENTER key</b></i>
```
cd && git clone https://github.com/MBHudson/CryptoWalletCracker.git && cd CryptoWalletCracker && sudo chmod +x install && sudo ./install
```
---
## Usage: 
- To run the program type the command <i><b> "cryptowalletcracker" </b></i> into a terminal and press the ENTER key. 
- When prompted enter a delay time for when the cpu limiter should start. You want this the start AFTER the script has begun to generate hashes. Typically 20-30 seconds will suffice...

### <b>Results:</b>
- Results can be found in the cracked.txt file inside the CryptoWalletCracker directory.

### <b>Sample Results:</b>
- hex private key: 5A4F3F1CAB44848B2C2C515AE74E9CC487A9982C9DD695810230EA48B1DCEADD
- WIF private key: 5JW4RCAXDbocFLK9bxqw5cbQwuSn86fpbmz2HhT9nvKMTh68hjm
- public key: 04393B30BC950F358326062FF28D194A5B28751C1FF2562C02CA4DFB2A864DE63280CC140D0D540EA1A5711D1E519C842684F42445C41CB501B7EA00361699C320
- address: 1Kz2CTvjzkZ3p2BQb5x5DX6GEoHX2jFS45
---
---
### Notes:
- Without limiting resource use all cores maintain 100% CPU consumption risking damage to the user's device. It is possible 
for one or two cores to persist. In these events I have found it beneficial to simply close the terminal and restart 
the script with the <i><b> "cryptowalletcracker" </b></i> command. Using a tool such at <b><i>"htop"</i></b> is strongly advised because you then see current state of CPU usage and whether or not the script is running properly. (To install "sudo apt install htop") You can run Htop anytime in a seperate terminal with the "htop" command.

## Todo:

- [x] Add delay variable (01282022)
- [ ] Add CPU% variable
- [ ] Launch Menu
- [ ] CC/CCV/Validator
- [ ] TOR Relay/Node/Hidden Service*
- [ ] Self-Propagating ProxyChains*
- [ ] Hot/Cold Wallet Support
- [ ] Bettercap jsinjection minner.js Tab-Minner*

Already written, awaiting implementation *

## Credits:
- Franz Kruhm
- Isaac Delly
