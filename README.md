# Battery checker

I did that battery checker to trigger some actions when battery is low in my archlinux,
the best option is to just use the udev rules, but sometimes things don't work because
udev will not send events when battery is low, so in that case just use the systemd timer
