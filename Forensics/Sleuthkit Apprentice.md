# Description
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/136/disk.flag.img.gz)
# Solution
```bash
picoCTF{by73_5urf3r_3497ae6b}
```
1. First write this command `mmls disk.img` to get to know the partition
2. write this `fls -o <highestoffset> disk.img` to get list of root directories
3. write this `fls -o <highestoffset> disk.img < number of root directory>` and go to the my_folder subdirectory
4. write this `icat -o <highestoffset> disk.img <number of that flag file>` and get the flag