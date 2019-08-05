# PCAP-CRACKER

Python script file to decrypt encrypted IEEE (802.11) Radio .pcap files captured via Wireshark. 
The script first extracts the Service Set IDentifier (SSID), and uses it to obtain the Wired Equivalent Privacy (WEP) key.
Once the WEP key has been extracted - it then decrypts the .pcap file completly (Cracked.pcap).

Usage: python pcap-cracker.py monitored.pcapng

| LANGUAGE | FILENAME | MD5HASH |
|--------  |--------- |---------|
| python | pcap-cracker.py | b0e0e3cbbba896ed1f56b75356726723 |
| zip    | Wiresharkfile.zip | 8e2d9661621cf49a04dc2cb2064161ae |

Bonus!! now includes automated username, password and object exporter.

## CONSOLE DISPLAY
![Screenshot](picture3.png) 
