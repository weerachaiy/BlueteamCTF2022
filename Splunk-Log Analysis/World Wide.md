- Solution
#OTX
https://otx.alienvault.com/
````
$ cut -f17 -d" " "CTF_ Splunk Multiple Country.txt" | sort| uniq -c | sort -h
$grep "\[185.220.100.240]" "CTF_ Splunk Multiple Country.txt" | cut -f19 -d" " | sort | uniq -c
````
- Answer: forensic{185.220.100.240_germany_f3netze}
