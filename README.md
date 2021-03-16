# Trails from Zero Lutris Installer
I decided to write up a quick and easy Lutris install script for The Grofront's Trails from Zero's localization to make it even easier to get this game up and running on Linux. Do note that in order for this install script to be useful to you, you must provide your own setup file for the game. This script simply downloads the Geofront launcher’s data and guides you through the install process. The Geofront mod only works on the Japanese PC version published by Falcom. It can be legally purchased from the following places:

* https://www.dlsite.com/soft/work/=/product_id/VJ009178
* https://falcom.shop/products/detail/15
* https://www.amazon.co.jp/dp/B00CIDFK2K/

The install script itself mentions this, but I cannot stress enough that you should NOT click the play button after the initial install of the game. Important Wine DLL overrides are applied after the installer is closed, so if you attempt to launch the game through the installer, the Geofront mod will not actually get loaded and a reinstall may be required.

I originally experienced a few graphical issues when playing the game with DXVK, so I tested it with WineD3D for a while and the game was perfectly playable. After a while, I decided to test DXVK again and found no issues with that either, so your mileage may vary. I’d recommend trying the game with DXVK first (which is the default option with this script) and falling back to WineD3D if you have any rendering problems.

To run this script, simply download it and run `lutris -i zero-lutris-installer.yml` in your console.

If anybody experiences any problems with the install script, feel free to create an issue and I'll be sure to fix it. Thanks!!
