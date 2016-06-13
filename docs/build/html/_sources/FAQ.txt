.. satoshkey documentation master file, created by
   sphinx-quickstart on Wed Jan 07 21:34:54 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   
FAQ
***

Overview
=========

What is satoshkey?
-------------------
Satoshkey manufactures a universal crypto currrency switch, that can be activated using bitcoin payments.
It replaces traditional coin-operated vending machines and brings the following advantages: 

* The satoshkey switch does not hold any money on it and is therefore not prone to theft.
* Revenues are automatically received to bitcoin addresses. No cost related to manually collecting coins.
* The satoshkey switch supports displaying prices in your local currency.
* Prices as low as a few cents can be assigned to activations.
* Rich statistics are available out of the box in your satoshkey web panel.
* Services can be configured remotely. One can for example increase the price for an activation without being physically present at the switch.


How does the satoshkey switch work?
-----------------------------------
After registering a swich on the web panel, activation sequences can be defined.
Each sequence is associated with a price tag, name and description. A QR-Code containing the switch id directs the user to a list with services offered by the switch.
After a payment for a specific sequence is received, the switch activates.

Can I activate the satoshkey switch with credit card payments instead of bitcoin?
----------------------------------------------------------------------------------
It is not intended to support activating the switch through credit card payments.
The satoshkey switch was built with the aim to support bitcoin and other crypto currencies in becoming the number one payment system.

What kind of hardware specs does the satoshkey switch have?
------------------------------------------------------------
The following list gives an overview of the satoshkey switch hardware specs.
Please do not hesitate to contact us if you have questions.

* ARM Processor Cortex M3 / 32 bit
* Ethernet Connector
* Micro SD Card
* 2 Potential free inputs
* QR Reader
* 2.8\" LCD Display
* 2 x Relais 10 A / 230V AC
* DIN Rail Case, IP 65
* Internal / external 12 V DC power supply


How do I install the satoshkey switch?
---------------------------------------
It is recommended to have the satoshkey switch installed by an electrician on order to ensure safe operation and comply to local regulations.

Technical
=========

Does the satoshkey switch need to be connected to the internet?
----------------------------------------------------------------
Yes.

How many outputs does the satoshkey switch have?
-------------------------------------------------
The satoshkey switch contains 2 outputs. A service can be defined as a sequence of activations of both outputs.

Merchant
========

What is the process for payouts?
---------------------------------
You configure the payout address for your switch using the *My Devices* section in your account.
Satoshkey immediately transfers all transactions received to your switch to the configured address.

Do you take fees?
------------------
No fees are charged apart from the bitcoin mining fee.

Is there a minimum price limit for an activation?
--------------------------------------------------
The minimum price limit is given by the least amount bitcoin wallets support of transfering.
Satoshkey recommends not to configure prices below 0.0005 BTC.







