#Originally modified to work with Mac OS Monterey. Compatible with: Thinkpad T450s, T450, X250, and 3rd Gen X1 Carbon.

What works: Everything besides VGA. Touchscreen support on 3rd gen X1 Carbon. SD-card slot also works without any issue.

What’s been changed:

1. Default language changed from Chinese to English, mainly noticeable when performing fresh install.
2. Intel WIFI works as it should, Location Services works for the most part. Added multiple AirportItlwm.kext drivers for: Catalina, Big Sur, and Monterey (Monterey AirportItlwm.kext is enabled by default). Can be found at: Kernel > Add > 16 + 17 + 18 . Alternatively use itlwm.kext instead by enabling 19 (and disabling all other AirportItlwm.kext that comes before it.
3. Under NVRAM > Delete > 7C436110-AB2A-4BBB-A880-FE41995C9F82, prev-lang:kbd was added to make sure that English Language is detected and selected by default.
4. ThinkPad Assistant not included. All of the function keys for T450/s and X1 Carbon work perfectly as it is, and I wanted to reduce clutter. Other files such as Lenovo Wallpapers and DW1820a driver are also not included.

This EFI has only been tested with Monterey and Catalina. This EFI will NOT boot into Catalina unless changes are made.

If you have any questions, you can get in touch with me at: Mark@OTGRepairs.net, or on Messages at: otgr340@yahoo.com

Good luck!

-Mark
