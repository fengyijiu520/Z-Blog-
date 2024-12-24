**BUG_Author:**
yijiu feng

**Affected version:**
Z-Blog

**Vendor:**
https://www.zblogcn.com/

**Software:**
https://www.zblogcn.com/program/zblogphp17/

**Vulnerability File:**
zba主题文件

**Description:**

Z-Blog后台文件上传漏洞，影响版本1.7.3及以下
系统对主题文件代码没有做审查，导致将恶意代码写入主题文件后，被系统生成为文件。黑客可以利用这个漏洞，将恶意代码生成至网站目录，而后通过工具完全控制其主机。
状态：严重

登陆管理后台后，通过上传精心构造的zba主题文件，成功将木马存放至\zb_users\theme\shell\template\目录下，使用中国蚁剑连接成功

![image](https://github.com/user-attachments/assets/121f913b-f52a-4fcf-84f6-adf9ecd9900e)
![image](https://github.com/user-attachments/assets/7fb8b38b-4cae-4a9a-9263-e07ea4236550)
