# Description
Can you read files in the root file?The system admin has provisioned an account for you on the main server:`ssh -p 65446 picoplayer@saturn.picoctf.net`Password: `NBD+zO8s4y`Can you login and read the root file?
# Solution
```bash
picoCTF{uS1ng_v1m_3dit0r_1cee9dcb}
```
1. This challenge is based on the linux privilege escalation
2. write the command `sudo -l` to check what permissions you have currently
3. write the command `sudo vi /root` you can see the `.flag.txt` file is available
4. write the command `sudo vi /root/.flag.txt` and get the flag
