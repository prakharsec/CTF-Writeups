# Description
Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image: [dds1-alpine.flag.img.gz](https://mercury.picoctf.net/static/4f3df7052b4121aff89af1a3f517afb1/dds1-alpine.flag.img.gz)
# Solution
```bash
picoCTF{f0r3ns1c4t0r_n30phyt3_a011c142}
```
1. Write this command ` srch_strings dds1-alpine.flag.img | grep picoCTF` and to  get the flag