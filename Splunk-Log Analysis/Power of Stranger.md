- Solution
````
$ grep -o "\-enc "[A-Za-z0-9/=]* CTF_splunk_powershell.txt | sort | uniq | cut -f2 -d" "| base64 -d | tr -d "."| grep -o forensic{[0-9a-zA-Z]*} 
````
- Answer: forensic{hekqlcqyua}
