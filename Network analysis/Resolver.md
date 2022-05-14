- Solution
````
$ tshark -nr "I am a robot.pcapng" -Y "dns.resp.name contains cncnet.ggez && dns.resp.type == 1" -Tfields -e dns.a | tr '\n.' ' ' | xargs bindechexascii --d2a
````
- Answer: Decimal to ASCII: echo "forensic{7H3_1P_15_Cmd}"
