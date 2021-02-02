Do Read This Before Proceeding :-

Clone the OTA repo in your ROM directory.
To generate json and push ota,
```bash
bash OTA/support/ota.sh <device_codename> <rom_directory> <maintainer_name> <maintainer_url> <forum_url>

e.g
bash OTA/support/ota.sh dumpling Nezuko "Maitreya Patni" https://t.me/Maitreya29 https://forum.xda-developers.com/
```
NOTES:
- ROM directory will look for *home/<os_username>/<rom_directory>*.
- Add doble quotes for parameters with more than a single word, like maintainer name in the example above.
- Forum URL parameter is optional.
