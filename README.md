# ht4032l-fw
Hantek 4032L firmware collection

## FX2

* V0 from year 2013. Minimal functionality. No EEPROM programming support.

## FPGA

* V0 from year 2013. No external clocking. Bug: slowdowns at low sample rates. Bug: all-zero IN packets before first STATUS/DATA packet.
* V4303 from 29 Apr 2015. External clocking. Both bugs of V0 listed above are fixed.
* V4304 from 2 Mar 2018. No visible differences from V4303.
