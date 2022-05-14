- Solution #EvtxECmd
https://ericzimmerman.github.io/#!index.md
````
C:\> EvtxECmd.exe -d C:\WindowsEventLogs --csv C:\WindowsEventLogs
C:\> grep "WNCRYT" EvtxECmd_Output.csv
C:\> grep "@WanaDecryptor@.exe" EvtxECmd_Output.csv
````
- Answer: forensic{Isass.exe}
