# dell-5537-hackintash

Dell 5537 laptop opencore 0.8

# Working:
Keybord & Touchpad
Sleep & Awake
Brightness & Keys
Audio
WLAN
Card Reader
USB

# Not working:
WIFI ar9565 (Big Sur should working using `HS80211Family` and `AirPortAtheros40-9565`)
HDMI
dGPU

## You shut down your computer because of a problem
deleting files in \Library\Logs\DiagnosticReports

## awake cause reboot
Fixing RTC `B2-B3`
https://dortania.github.io/OpenCore-Post-Install/misc/rtc.html#finding-our-bad-rtc-region