# Description
All we know is the file with the flag is named `down-at-the-bottom.txt`... Disk image: [dds2-alpine.flag.img.gz](https://mercury.picoctf.net/static/544be9762e9f9c0adcbeb7bcf27f49a2/dds2-alpine.flag.img.gz)
# Solution
```bash
picoCTF{f0r3ns1c4t0r_n0v1c3_69ab1dc8}
```
1. Write the command `mmls disk.img` 
2. write this command and go the directory /var `fls -o 2048 disk.img <number of var directory>` and get the flag