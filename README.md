# ABadAvatar - XeUnshackle Alternative Included
A XeUnshackle Alternative with a ```SMBUI```_(Simple Message Box UI)_ similar to [FreeMyXe](https://github.com/FreeMyXe/FreeMyXe) made specifically for [ABadAvatar](https://github.com/shutterbug2000/ABadAvatar)

1. Loads `DashLaunch` As **Normal**.

2.  Option to skip the UI and take you straight to the Xbox 360 Dashboard.<br>
_**Note: this disables UI permanently, unless the 'config.ini' file is deleted or set to false, `XexMenu` can be used to `delete` the file**._

3. Shows console information in the ``SMBUI`` message box.

4. Option to `Save` Console Information to a ``Text File``.

_**If this is not adopted by @shutterbug2000 for [ABadAvatar](https://github.com/shutterbug2000/ABadAvatar), then this software will be rebranded to an independent software named ````'HexPatch'````**_


## [ABadAvatar](https://github.com/shutterbug2000/ABadAvatar) Original ReadMe:

<details>
   
  <summary>Click to expand ABadAvatar README</summary>

_1. Ensure your console has the Avatar update data. If you don't have an HDD, you may need to install the official offline System Update 17559 on a formatted USB. Don't use LIVE to update, just in case Microsoft decides to patch this._

_2. No xex is included. You'll need to put an xex that does what you wish in the BadUpdatePayload folder (odds are, this is XeUnshackle or FreeMyXe)._

_3. You can tell if the exploit is running by moving the cursor on the profile select screen. Additionally, the 2 LEDs on the ROL will occasionally swap. Attempting to back out of the selection screen or log in at this point will interfere with the exploit._

_4. Don't log in to the exploit profile, especially while on LIVE. There is a PIN set to prevent accidental logins._

_5. You should ensure that you are disconnected from both Wi-Fi and Ethernet before using this exploit to prevent LIVE bans. Ethernet is easy, but Wi-Fi requires you to either disconnect before turning off your console, or sacrifice the cold boot aspect (or just don't hook up the 360 to the internet at all)._

_6. Stage 2 is fully buildable start-to-finish without any trickery. If you want to modify stage1, hexedit the output into the avatar item from the release profile at address 0x2200. Stage0 is tricky to modify due to compression, but only shows the anti-scam text and performs a stack pivot and can safely be considered static._

_7. Stage 3 should be built at 0x90110000 instead of 0x98030000. Additionally, you should pad up to 0x10000 bytes with 4E 80 00 20 to ensure the module used in the exploit can be properly unloaded._
</details>
