# Guide to installing Windows 10/11 on Lenovo Ideapad 3 CB (Lick)
### This guide is based on the [Chrultrabook Docs](https://chrultrabook.github.io/docs).


Step 1: [Enable developer mode](https://chromium.googlesource.com/chromiumos/docs/+/HEAD/developer_mode.md)
   > WARNING:
   > Doing this will wipe **all** user data! Make backups if needed before proceeding.

   * Press `esc` `refresh` (f3) and `power` at the same time. Doing this should cause your system to reboot into a screen that prompts you to insert a recovery USB or SD card.
   * Press `ctrl` and `d` at the same time.
   * Follow the on screen instructions, then once it reboots, you should be in Developer Mode. **Do not enable debugging features.**
   * Setup the system as you would on any other Chromebook.
  
Step 2: [Disable Write Protect](https://wiki.mrchromebox.tech/Firmware_Write_Protect#Hardware_Write_Protection)

   * Unscrew and remove the back cover.
   * Disconnect the battery.
   * Plug in the charger and turn on your chromebook.

Step 3: [Flash Firmware](https://chrultrabook.github.io/docs/docs/firmware.html)
   > WARNING:
   > **Flashing the firmware has the potential to brick your device.**

   * Press `ctrl` `alt` and `t` at the same time.
   * Type `shell` and press Enter.
   * Type `cd; curl -LO mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh` and press Enter.
   * Choose `Install/Update UEFI (Full ROM) Firmware` and follow the prompts to install the firmware.
   * Press `p` to shutdown your Chromebook.
   * Plug in the battery and install the back cover.


