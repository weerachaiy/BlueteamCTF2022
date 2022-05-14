- Solution
````
$ tshark -nr "CTF_Secret Communication.pcapng" -Y "icmp.type == 0" -Tfields -e data | sed 's/^/0/g' | sed 's/000/1/g' | tr -d '\n' | sed 's/\(........\)/\1\ /g' | xargs bindechexascii --b2a
````
- Answer: Binary to ASCII: forensic{P1ngP0ng_Fl@g}
