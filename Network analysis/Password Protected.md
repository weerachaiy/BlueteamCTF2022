- #Solution
````
$ tshark -nr "Password protected.pcapng" -Y "ftp-data&&ip.dst==172.16.2.133" -Tfields -e text
````
- Answer
````
<+ohcAo(mg+DGm>AoD^$DKBN%HZ`)!:,$le+>[n&0OunU3IL
#BASE85
flag is forensic{uNkN0wN 3nC0d1n9}
````
