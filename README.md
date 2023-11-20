# VerifierX
记录获取各种软件的校验信息的方法(Methods for Recording Verification Information of Various Software)

## 校验命令

```
Windows 需要使用power shell SHA256可以替换成md5、sha1等
Get-FileHash -Algorithm SHA256 -Path .\YourFileName.extension 

Linux
md5sum your_file
sha256sum your_file
sha1sum your_file
```



## VMware Workstation Pro 

访问url：`https://customerconnect.vmware.com/home`

点击`Downloads`

![image-20231120212657875](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120212657875.png)

搜索`VMware Workstation Pro`，点击`Download Product`

也可以使用下面的下载地址。

下载地址：`https://customerconnect.vmware.com/downloads/info/slug/desktop_end_user_computing/vmware_workstation_pro/17_0`

选择VMware 版本

![image-20231120212127038](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120212127038.png)

点击`GO TO DOWNLOADS` 后，该页面还可以选择小版本

点击`Read More`查看校验码

![image-20231120212427342](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120212427342.png)





## Windows 11

### Windows 11 23H2

访问url `https://www.microsoft.com/zh-hk/software-download/windows11`

选择`下載 Windows 11 光碟映像 (ISO)`

![image-20231120213820092](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120213820092.png)

目前不登录状态下在官网只能查看`multi-edition 版本`的检验码

点击下载后选择产品语言，随便选择一个，点击确定

`下载->简体中文->确定->验证下载项目`

**选择你需要验证的产品语言！！！(语言不对检验码是不会对的)**



![image-20231120214028300](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120214028300.png)

```
Windows官方推荐使用校验命令（需要先开启PowerShell）
PowerShell
Get-FileHash C:\Users\用戶1\Downloads\Contoso8_1_ENT.iso
```



## 微软产品

微软大部分产品的校验码都需要登录才能查看，如果不需要登录我会单独列出来。

需要拥有一个微软账号，才能进行下面的操作

访问URL：`https://my.visualstudio.com/Downloads/Featured?mkt=zh-cn`

![image-20231120221028104](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120221028104.png)

选择需要获取校验码的产品，我这里以`Windows 10`作为例子

![image-20231120221148563](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120221148563.png)

按照你的系统版本语言选择

`Windows 10, version 1903->All Downloads->English->info`

![image-20231120221433264](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120221433264.png)

进行第五步操作后就会出现校验信息（语言不同校验信息也会不同）

![image-20231120221639333](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120221639333.png)



## java

java下载地址：`https://www.oracle.com/java/technologies/downloads/`

java的校验信息一般都会在下载地址后面

![image-20231120224308934](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120224308934.png)

或者出现在下载上方

![image-20231120224331735](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120224331735.png)

## python

python下载地址：`https://www.python.org/downloads/`

访问下载地址，往下拉找到`Looking for a specific release?`

![image-20231120224710903](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120224710903.png)

选择版本下载，下载页面底部会出现校验信息

![image-20231120224821593](https://raw.githubusercontent.com/loulan-ling/VerifierX/main/img/image-20231120224821593.png)
