# Waf
Run waf:
python waf.py

See at:
http://localhost:5000

Use waf by pasting url in browser:
    "http://localhost:5000/get.php?input=%3Cscript%3Ealert%281%29%3C%2Fscript%3E",
    "http://localhost:5000/sqli.php?input=%27or+1%3D1%3B--",
    "http://localhost:5000/cmd.php?input=;ls",
    "http://localhost:5000/path.php?input=/etc/passwd"
