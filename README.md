# Arithm0-Gath3r
### Numbers in Your Documents can reveal your personal informations. "Especially banking informations! "

### This tool is an OSINT tool to gather informations from CreditCard number, BIN code, MICR number, IFSC code , Phone number

### It can be useful for OSINT researchers, Dumpster diving , hackers , and Law & enforcement officers
![Arithmo-Gather Screenshot](https://github.com/febinrev/arithmo-gather/raw/master/arithmo_gather.jpg)

## Disclaimer : It is only for Educational Purposes!!


-----------------------------------------------------------------------------------------------------------------------------------
### Note : Feel free to modify my code and make your own! But give me a credit before You use my code.

## Usage:
------------------------------------------------------------------------------------------------------------------------------
    $ pip3 install -r requirements.txt
    $ python3 arithmo-gather.py
    
    [Then Enter the Appropriate option number and enter the Code/number like CC or PhoneNumber to gather the informations about it!!]

## Examples:
#### Credit Card informations 
![CC info](screenshots/CC.jpg)

#### IFSC code informations
![IFSC info](screenshots/IFSC.jpg)

#### MICR number informations
![MICR info](screenshots/micr.jpg)

#### Phone number informations
![Phone info](screenshots/phone.png)

### TroubleShoot:
-------------------------------------------------------------------------------------------------------------------------------
    * If you are constantly facing errors it may be caused due to API key expiry. 
    * So if you want to run it more smoothly and efficiently it is recommended to use your own API keys from bincodes.com and numverify.com . 
    * Paste the api key of bincodes.com in the " key1 " variable and numverify.com api key in " pkey " variable.
    Both variables are declared at the beginning of the source code.
