# The UNOFFICIAL Asuswrt-Merlin firmware for ASUS RT-N18U router.

This project is to make Asuswrt-Merlin firmware support for ASUS RT-N18U router.   
The primary goal is to integrate the Asuswrt-Merlin features based on the codebase of official RT-N18U GPL release.   
Please note that the firmware version does not directly map to official Asuswrt-Merlin release starting from 384.9.  

Please read the installation note before starting to use this firmware. 

## Installation

There is no special procedure to install this firmware. Just upload it to the router via the web UI. A few notes:

1. Installing this firmware voids your warranty. Although it is very hard to brick an ASUS router, I take no responsibility for the result caused by using this firmware.
2. If coming from the official AsusWRT, please upgrade to the latest version (3.0.0.4.382.52288) first and then install this firmware. Restore to default by hardware button is required after the router is switched to this firmware.
3. It's not recommended to use the version older than 384.18 since the latest GPL version was merged into it.
4. It's not recommended to restore settings saved under a different firmware version. It might work, but there is no guarantee.
5. It's recommended to backup settings before updating router firmware to make sure you can restore the last router status.

![Asus Merlin panel screenshot](https://github.com/hattimon/SmartWAN-Manager/raw/main/docs/merlin_img.png)  

# TRY ALSO: SmartWAN Manager  

This panel was created for ASUS RT-N18U running the unofficial gzenux Asuswrt-Merlin RT-N18U firmware version 386.3_3.   
Most applied settings continue to operate on the router after the panel is stopped:   
SmartWAN rules and presets, router-side watchdog and failover, managed VPN/DMZ policy, and Merlin hooks.  

Keep the container running for WAN country/location checks, Cloudflare DDNS, Tailscale access, persistent WAN-event archiving, the public status/network map, and Aurelka notifications.  

![SmartWAN Manager panel screenshot](https://github.com/hattimon/SmartWAN-Manager/raw/main/docs/Panel_img.png)  

## Links

- [Project page](https://hattimon.github.io/SmartWAN-Manager)
- [GitHub repository](https://github.com/hattimon/SmartWAN-Manager)

---  

This project contains proprietary components from ASUSTeK, Broadcom, 
Trend Micro and Tuxera (and possibly others).

These components are only licensed for use on original
ASUSTeK devices.  Any use of these components on devices from other
manufacturers is strictly forbidden, and might be illegal in your
country according to your local laws.  The developers of the
Asuswrt-Merlin project will take no responsability for third party
use of these licensed components on unlicensed hardware.  
  
