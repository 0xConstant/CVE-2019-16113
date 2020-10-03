# Bludit 3.9.2 - Remote command execution - CVE-2019-16113

This exploit combines two exploits in Bludit CMS 3.9.2 to gain remote code execution on the target system.

The original exploits are [CVE-2019-17240](https://rastating.github.io/bludit-brute-force-mitigation-bypass/) & [CVE-2019-16113](https://www.exploit-db.com/exploits/47699).

### Features 
- Bruteforce password + RCE 
- Bruteforce username:password + RCE

#### Reproduce 
- Setup Bludit 3.9.2 CMS
- Configure login details 
- run the exploit:
```
python3 poc.py
```


