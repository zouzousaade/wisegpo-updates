# WiseGPO updates

Public OTA update feed for WiseConcepts WiseGPO controllers based on the
Waveshare ESP32-P4-ETH.

WiseGPO checks this feed only when an operator presses **Check online** in
Advanced settings. The browser downloads the OTA image, verifies its SHA-256
digest against `updates.json`, and then transfers the verified image directly
to the selected device on the local network.

The repository intentionally contains only public update artifacts. It does
not contain credentials, private keys, device settings, or the firmware source.
