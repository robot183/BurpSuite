# Burp-
记录burp插件编写 思路 以及过程
被动burp 插件 测试 任意文件读取漏洞。
初版有点简陋
BurpSuite 插件编写

12.14  
之前的版本，不方便使用；新版本 预期增加  参数定制  poc 定制
v1.1  增加了 payload 定制
payload 批量输入方法：不同payload之间使用， 作为分隔符。
举例：../../../../../etc/passwd,../../../../../etc/host,../../../../../../windows/win.ini，
