# ipixelgalaxy-automator
https://www.github.com/big-sur-automator but with iPixelGalaxy's patcher

-1. If you have a barrykn patched usb, i suggest to keeping it
0. Format your USB as macOS Extended Journal | GUID Partition | Name as "BS" (It doesn't stand for BullShit ok?)
1. Run the script
2. Reboot
3. Open Terminal
4. Enter the following commands in order
csrutil disable
csrutil authenticated-root disable
nvram boot-arg="-no_compat_check amfi_get_out_of_my_way"

5. Install macOS on the partition you wan't normally
6. Wait until the setup shows

# kext patching

Two choices'

choice 1 (better)
Boot into barrykn patched usb
enter terminal
type the following
/Volumes/[usb name]/patch-kexts.sh
wait
reboot to big sur drive

choice 2
https://medium.com/@andv/making-wifi-on-big-sur-unsupported-macs-with-failed-with-66-error-36c98e3f7965

