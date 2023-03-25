# VDI-Metasploitable2

<img src="https://github.com/ghostn4444/VDI-Metasploitable2/blob/main/img1.png">

 Metasploitable.vdi ![Link Donwload]('https://drive.google.com/file/d/1tnnVqxueOxc8KCv0LF0kxEC7SvR7Wba8/view')

#

### LOGIN
* Login: <code>msfadmin</code><br/>
* Password: <code>msfadmin</code>

# good studies!

hydra dvwa get USERS

```bash
  hydra -l admin -P /home/kali/rockyou.txt 192.168.15.28 http-post-form "/dvwa/login.php:username=^USER^&password=^PASS^&:Login=Conecte-se"
```
