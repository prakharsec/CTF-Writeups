# Description
Download the disk image and use `mmls` on it to find the size of the Linux partition. Connect to the remote checker service to check your answer and get the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.[Download disk image](https://artifacts.picoctf.net/c/164/disk.img.gz)Access checker program: `nc saturn.picoctf.net 56621`
# Solution
```bash
picoCTF{mm15_f7w!}
```
1. First of all use `mmls disk.img` to check the image partition
2. Run the netcat and write the current linux partition and get the eflag