# IPv6-Steganography

This tool can send and receive messages which are encrypted using AES-256-CBC Encryption. It hides the encrypted data inside of extension headers of IPv6 packets. It is entirely built in python. It runs only on Windows for now, linux support will be added later.

# UPDATE for running:
Just Run "run.bat" as Administrator.

# Steps to Run:
Run PowerShell or cmd as administrator.

Navigate to the directory of the extracted files.

Run: pip install -r .\requirements.txt

Run: .\main.py where is the interface to send and sniff packets on.

Ex. if you are sniffing on Wi-Fi, then run it as: .\main.py Wi-Fi
