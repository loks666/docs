### 1. 下载 Office Deployment Tool
在[Microsoft 官网](https://www.microsoft.com/en-us/download/details.aspx?id=49117)上下载 Office Deployment Tool。

### 2. 配置 config 文件
在 [这个页面](https://config.office.com/deploymentsettings) 配置并导出 XML 文件。

### 3. 安装 Office
在你安装的文件夹下打开命令提示符（cmd）执行以下命令：

```bash
setup.exe /download config.xml
setup.exe /configure config.xml
```

### 4. 激活 Office
执行以下命令：

```bash
cd C:\Program Files(x86)\Microsoft Office\Office16 
```

或者

```bash
cd C:\Program Files\Microsoft Office\Office16
```

接着执行：

```bash
cscript ospp.vbs /sethst:kms.03k.org 
cscript ospp.vbs /act
```

### 5. 备选的 KMS
如果上面的 KMS 服务器无法使用，你可以尝试以下备选 KMS 服务器：
- kms.03k.org
- kms.chinancce.com
- kms.luody.info
- kms.lotro.cc
- kms.luochenzhimu.com
- kms8.MSGuides.com
- kms9.MSGuides.com

