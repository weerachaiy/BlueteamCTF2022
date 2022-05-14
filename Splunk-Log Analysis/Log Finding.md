- Solution
````
$ grep -o username=[a-zA-Z]* CTF_Log_finding_weblog.csv | sort | uniq -c| sort -h | tail
$ grep -o passwd=[a-zA-Z]* CTF_Log_finding_weblog.csv | sort | uniq -c| sort -h | tail
````
- Answer
````
forensic{md5(username=adminpassword=batman)}
forensic{5287e72b8721fad4a35ceabc0ab0d365}
````
