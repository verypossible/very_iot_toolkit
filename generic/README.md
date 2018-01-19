# Powering (and power cycling) Your Device

## Powered USB Hub
In most cases, a powered USB hub will get you where you need to go.  This will
allow your dev machine to have serial communication with your device (for
programming or debugging).

In addition, check out a hub that can be controlled via
[uhubctl](https://github.com/mvp/uhubctl).  This will allow you to
programmatically power cycle your device, which can really come in handy.
**Repeatedly plugging and un-plugging usb cables can become tedious, so avoiding
it can save a lot of time and energy.**

## Manual Switches
As mentioned, it's no fun to plug and un-plug a usb cable all the time, so look
for usb hubs that have manual switches or a cable with a switch in-line.  **Be
careful with in-line switched cables, as some of them only carry power and no
data**.  If you have trouble finding one, it's easy enough to make your own with
something like
[this](https://www.amazon.com/Switch-Inline-Button-line-Light/dp/B071K4DP9N/ref=sr_1_1_sspa).

## Current Limited Power Supply
If you are "hacking" with hardware that needs higher power than USB will
provide, you should be using a [benchtop power supply with a current
limiter](https://www.amazon.com/Eventek-KPS305D-Adjustable-Switching-Regulated/dp/B071RNT1CD/ref=sr_1_1).
This will prevent you from accidentally frying your fancy electronics if you
hook something up wrong.
