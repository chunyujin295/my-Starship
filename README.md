toml文件不支持判断语法， 因此对于不同平台都出版了一个配置

通过设置环境变量的方式，指定Starship配置文件的位置

unix:

```bash
export STARSHIP_CONFIG= 该仓库路径/linux-starship.toml
```

windows:(Powershell)，或者直接图形化添加

```powershell
$ENV:STARSHIP_CONFIG = "该仓库路径\windows-starship.toml"
```



<img src="https://map--depot.oss-cn-hangzhou.aliyuncs.com/image/image-20250216224110846.png" alt="image-20250216224110846" style="zoom:80%;" />