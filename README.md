## FuckTelecom
使用V2Ray实现电信免流

[联通免流点此配置](https://github.com/EraserCN/FuckUnicom)

#免责声明
```
本项目仅限于学习用途，必然违反联通之用户协议。
请勿用于违法用途，本人概不负责。
您对使用此项目产生的后果负有全部责任。
如您不同意本声明之任一部分，请勿使用。
```

#使用说明

在服务器上执行以下命令
```
wget https://github.com/EraserCN/FuckTelecom/blob/main/install.sh
wget https://github.com/EraserCN/FuckTelecom/blob/main/config.json
```

> 之后强烈建议修改config.json之UUID

# 再执行以下命令

```
bash install.sh
systemctl enable v2ray
cp config.json /usr/local/etc/v2ray/config.json
systemctl start v2ray
```

# 最后导入V2Ray连接
