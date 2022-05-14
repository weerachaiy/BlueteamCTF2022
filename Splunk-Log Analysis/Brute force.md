- Solution
````
$ grep "https://bankofpunk.local/login.aspx" targeted_iis.log | cut -f9 -d" " | sort | uniq -c | sort -n | tail
````
- Answer: forensic{23.161.240.169}
