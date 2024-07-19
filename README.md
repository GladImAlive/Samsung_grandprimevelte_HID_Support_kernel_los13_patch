Convert your Android device into USB keyboard/mouse, control your PC from your Android device remotely, including BIOS/bootloader. Use it as Rubber Ducky.

While compiling Kernel for this device,use this command

```
patch -p1 < SM-G531F_HID_Support_Kernel.patch
```
the above applies for the stock ROM

```
patch -p1 < hid_support_patch_los13.patch
```

this one applies for the Lineage 13.0 ROM
