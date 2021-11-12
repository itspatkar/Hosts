# Hosts Script
Bash script to create a uniq sorted hostlist from multiple sources.

## Configuration :
- `LOCAL_HOST` : local server to which the request is redirected, set to `0.0.0.0` or `127.0.0.1` (default is `0.0.0.0`)
- `OUTPUT_HOST` : output hosts-styled blocklist (default is `hosts.txt`)
- `source.list` : plain text file from which hosts-styled sources are to be fetch
- `source.domain` : plain text file from which only ip/domain sources are to be fetch

**NOTE -**
- `source.list` : should have only host-styled format sources, Ex- `0.0.0.0 www.example.com`
- `source.domain` : should have only ip/domain format sources, Ex- `www.example.com`

## Usage :
- Clone repo
- Add hosts sources/links in `source.list` and `source.domain` per line *(remember above noted points)*
- If the list has only one entry, then add an extra empty line at the end. *(some issue in script/curl)*
- Run `generate.sh`


<br>

# Hosts Lists
Curated and well-maintained hostlists to block social media, trackers, porn sites &amp; ads.

| Hosts | Recipe | RAW Link |
| --- | --- | --- |
| Porn | Porn Sites + Pornaway's Porn Sites + Porn Ads | [link](https://raw.githubusercontent.com/itspatkar/hosts/main/LISTS/porn.txt) |
| Trackers | MIUI + Microsoft Trackers | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/trackers.txt) |
| Facebook | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/facebook.txt) |
| Google | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/google.txt) |
| Instagram | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/instagram.txt) |
| Linkedin | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/linkedin.txt) |
| Twitter | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/twitter.txt) |
| WhatsApp | - | [link](https://raw.githubusercontent.com/itspatkar/Hosts/main/LISTS/whatsapp.txt) |

## Credits For Sources :
- [Steven Black Hosts](https://github.com/StevenBlack/hosts)
- [Pornaway](https://github.com/mhxion/pornaway)
- [Fanboy Hosts](https://www.fanboy.co.nz)
- [Energized.pro](https://energized.pro)
- [LukeSmithxyz Hosts](https://github.com/LukeSmithxyz/etc)
