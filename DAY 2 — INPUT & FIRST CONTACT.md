## ติดตั้งสภาพแวดล้อมให้พร้อมใช้งาน
### โหลด Nmap จาก link

[ดาวน์โหลด Nmap](https://nmap.org/download.html)

## ทำตาม Tutorail Nmap พื้นฐาน 

1. Enter `scanme.nmap.org` in the **Target** box at the top left.
2. Click inside the **Command** text bar and edit it to match the exact command you want to run.
3. Click the **Scan** button on the top-right corner.

---

### Step-by-Step Examples

* **Basic Scan**
* **Command:** `nmap scanme.nmap.org`
* **What it does:** Performs a standard scan on the 1,000 most common TCP ports.


* **Scan Specific Ports**
* **Command:** `nmap -p 22,80,443 scanme.nmap.org`
* **What it does:** Scans only SSH (22), HTTP (80), and HTTPS (443).


* **Scan with Service Version**
* **Command:** `nmap -sV scanme.nmap.org`
* **What it does:** Probes open ports to determine service/version info (e.g., Apache 2.4.41).


* **Output to File**
* **Command:** `nmap -oN output.txt scanme.nmap.org`
* **What it does:** Saves normal output to a text file named `output.txt` in your current directory. *(Note: Use `-oN` for standard text files, as `-o` alone is incomplete in Nmap).*



---

### Alternative Option: Command Prompt / PowerShell

Since Zenmap is a graphical user interface wrapper around Nmap, you can also run these exact commands natively by opening **Command Prompt** (`cmd`) or **PowerShell** in Windows and typing the commands directly into the terminal window.