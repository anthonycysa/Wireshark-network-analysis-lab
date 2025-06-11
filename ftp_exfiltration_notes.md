## FTP Login in Plaintext

- Captured FTP login session
- Username and password visible in clear text
- Possible data exfiltration detected via large PUT commands

### Wireshark Filter:
```
ftp.request
```