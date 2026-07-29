
# Netflix Cookie Checker

**Checks Cookies for validity.**

*<b>Education purpose only.</b>*<br><br>
![Logo](images/netflix_logo.jpg)



# 🆕 What's New

> **Latest update** improves cookie validity detection, duplicate filtering, and proxy safety.

<details open>
<summary><b>Checker Reliability — Latest</b></summary>

### ✨ New Features
- **Updated cookie validity check** — More reliable detection of valid and expired cookies.
- **Stronger duplicate detection** — Prevents saving the same working cookie multiple times.
- **Existing-output duplicate scan** — Checks previously saved cookies to avoid duplicates across runs.
</details>

# Installation

```cmd
  git clone https://github.com/oussamamaad/Netflix-cookie-checker.git
  cd Netflix-cookie-checker
  pip install -r requirements.txt
```

**make sure you have a good internet connection.**

| Network Speed | Recommended no. threads |
|---------------|-------------------------|
| < 5 Mbps      | 1-3                     |
| 5-20 Mbps     | 3-5                     |
| 20-100 Mbps   | 5-10                    |
| > 100 Mbps    | 10-20                   |


# Proxy Support
 
### Proxy File Format
 
Your proxy file should be a plain `.txt` with one proxy per line. All common formats are supported:
 
```
# host:port
1.2.3.4:8080
 
# host:port:user:pass
1.2.3.4:8080:myuser:mypass
 
# user:pass@host:port
myuser:mypass@1.2.3.4:8080
```
 
Lines starting with `#` are ignored.
 
 
## Features
 
- ✅ Multi-threading
- ✅ JSON + Netscape cookie support
- ✅ Optional proxy support (HTTP / HTTPS / SOCKS4 / SOCKS5)
- ✅ Automatic proxy validation before use
- ✅ Safer proxy mode with no silent direct-IP fallback
- ✅ Super fast
- ✅ Identifies duplicate cookies using cookie fingerprints
- ✅ Detects extra memberships

