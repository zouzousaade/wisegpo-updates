# WiseGPO updates

Public OTA update feed for WiseConcepts WiseGPO controllers based on the
Waveshare ESP32-P4-ETH.

WiseGPO checks this feed only when an operator presses **Check online** in
Advanced settings. The browser obtains the OTA image through GitHub's Contents
API and transfers it to the selected device, which verifies its SHA-256 digest
against `updates.json` before changing the boot partition.

The Windows wiseTool utility can also check this feed, show the release's
What's new and Fixes notes, and download a checksum-verified OTA image.

The repository intentionally contains only public update artifacts. It does
not contain credentials, private keys, device settings, or the firmware source.
