一个小工具：远程在域外将域用户加入到某一个域内用户组

A small tool: Remotely add a domain user to a specific domain group from outside the domain. Usage is as follows:
AOexp.exe -domain vultest2.com -priuser AOtest -pripass 1qaz@WSX -user AOtest -addgroup "Exchange Windows Permissions" -dc dc2012.vultest2.com

![image](https://github.com/user-attachments/assets/5eacb510-ccd5-4f2e-af8e-876628482a4c)

如果用户权限不足会爆拒绝访问，如下图：
![image](https://github.com/user-attachments/assets/9e6b56ed-4f7a-43ea-bf42-afe4f1eaba93)


