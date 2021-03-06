# Vega64SoftPowerTableEditor
Windows Vega 56/64 Soft Power Table Editor

Written in C# Mono with GTK#.

If you find this useful consider [Donating](#donations)

## Warnings / No Liability:
 - No verification is done to make sure the values are sane.
 - You can pretty much edit anything in the power table even values you should not touch.
 - You are on your own if you break your GPU.

## Current Status:
 - Saving works!
 - Works on VEGA 64 and VEGA 56
 - Parse Registry File
 - Display and edit Gfx/Mem Clock, Gfx/Mem Vdd, PowerTune Table, Fan Table
 - Clamping on data to its type
 
 <img src="https://github.com/halsafar/Vega64SoftPowerTableEditor/blob/master/screenshots/screenshot.png" width="800"/>

## Disclaimer:
 - Have not coded in C# for over 10 years.  Why I chose to for this is merely a forced refresher.
 
## Want To Help:
 - Pull requests are always welcome!  
  
# Installation
 - Acquire an existing registry file for your VEGA 56/64
 - Load into this program
 - Edit as you see fit
 - Save
 - Open Wattman and reset your GPU, set Voltage to manual, apply.
 - Apply the registry file to each card (if you have multiple cards adjust the path)
 - Reboot
 - Open Wattman
 - Hit reset, apply, set voltage to manual, apply.

# Compiling From Source
 - The easiest way to compile from source is to download Xamarin Studio and open the project.

# Thanks
 - Hellm @ http://www.overclock.net [Profile](http://www.overclock.net/u/511964/hellm)
 - If I missed anyone in the discovery of the SoftPowerTable trick let me know.

# Donations

Consider donating if you find this useful.  You can donate praise, a beer or if you are feeling generous some sweet sweet crypto:

* __ETH__ - 0xcAB239517F2e394425B3Fc5250b6b21A38B921E3
* __LTC__ - LKh2BUW5iK7HqSoPF2AsS67TJ8PQ9QJNUE
* __BTC__ - 16CAns1mLFUx5Hr1DTrqpFJ17FU1dHZUzB


