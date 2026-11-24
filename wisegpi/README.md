# WiseGPI updates

Firmware for 16-input WiseGPI controllers using the Waveshare ESP32-P4-ETH.

## Latest firmware

[Download WiseGPI 2.3](WiseGPI-2.3-ESP32P4.wisegpi)

One bundle contains full serial and OTA images for ESP32-P4 Rev 1 and Rev 3. wiseTool 1.19 or later selects the full image after reading the chip revision over USB. WiseGPI firmware 2.1 or later selects the OTA image when this bundle is uploaded through Advanced settings.

## Online updates

After installing 2.3 once, open **Settings > Advanced > Check online**. An available update is downloaded through the browser, matched to the board revision, checked by the device against its SHA-256 checksum, and installed after confirmation. Installation restarts the unit. Saved settings are retained.

The browser needs Internet access. The controller can stay on its local network. Checks and installation run when requested by the operator.

The [update feed](updates.json) contains the current version, versioned bundle URL, bundle size and checksum, and each revision's OTA offset, length and checksum. Future releases add a versioned bundle and update this feed.
