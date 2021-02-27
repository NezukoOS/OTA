Do Read This Before Proceeding :-

Clone the OTA repo in your ROM directory.
To generate json and push ota,
```bash
bash OTA/support/ota.sh <device_codename> <rom_folder> <maintainer_tgusername> <maintainer_url> <forum_url>

e.g
bash OTA/support/ota.sh dumpling Nezuko "Maitreya29" https://t.me/Maitreya29 https://forum.xda-developers.com/
```
NOTES:
- ROM directory will look for *home/<os_username>/<rom_folder>*.
- Add doble quotes for parameters with more than a single word, like maintainer name in the example above.
- All parameters are mandatory.
