- Solution
````
$ cut -f11 -d" " control.log | sort| uniq -c | sort -h
✅4 "https://pwnedbank.co.uk/qkhpagct.aspx"
$ grep https://pwnedbank.co.uk/qkhpagct.aspx control.log
````
- Answer: forensic{93.159.204.215}
