- Solution #volatility3
````
$ python3 vol.py -f CryCryCry.mem windows.info
$ python3 vol.py -f CryCryCry.mem windows.cmdline 
$ python3 vol.py -f CryCryCry.mem windows.netstat| grep ESTABLISHED | grep 443
````
````
992     windows_defend  "C:\Users\ewiges\Desktop\windows_defender.exe"
✅2828 ✅taskhsvc.exe ✅TaskData\Tor\taskhsvc.exe
4524    @WanaDecryptor  "C:\Users\ewiges\Desktop\@WanaDecryptor@.exe"
✅443 ✅ESTABLISHED ✅2828 ✅taskhsvc.exe
````
- Answer: forensic{taskhsvc.exe}
