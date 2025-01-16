UPDATE: There's been some activity in the kernel:

https://git.kernel.org/pub/scm/linux/kernel/git/hid/hid.git/log/?h=for-6.14/lenovo 

ARCHIVED: I'm currently using Windows.

The keyboard of the Lenovo ThinkPad X12 Detachable gen1 is a USB device.
Like other Lenovo keyboards, the ctrl and fn keys are in the reverse layout than most "Windows" laptops.
ThinkPads traditionally have a BIOS option to switch them to the more common layout.
However, the X12 does not provide this option.
The "Vantage" software by Lenovo can do the swap, but only on Windows.
This setting persists across reboots, but not after you power down the computer.

The [`usb.pdml`](usb.pdml) file contains a USB packet capture from the "Vantage" software when toggling the setting.
