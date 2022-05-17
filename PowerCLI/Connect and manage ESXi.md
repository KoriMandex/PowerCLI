# Kori Hanes
# 13MAY2022

# Commands for testing and viewing 

https://adamtheautomator.com/powercli-tutorial/

Connect-VIServer -Server vcsa.c4iusmc.local -User <USER_NAME> -Password <USER_PASSWORD>

# OutPut:

# Name                           Port  User
# ----                           ----  ----
# vcsa.c4iusmc.local             443   C4IUSMC\hanes.kori


Get-VMHost
Output
Name                 ConnectionState PowerState NumCpu CpuUsageMhz CpuTotalMhz   MemoryUsageGB   MemoryTotalGB Version
----                 --------------- ---------- ------ ----------- -----------   -------------   ------------- -------
10.104.200.103       Connected       PoweredOn      32        9104       83168          92.139         383.908   7.0.3
10.104.200.101       Connected       PoweredOn      32        1903       83168         169.840         383.908   7.0.3
10.104.200.102       Connected       PoweredOn      32         819       83168         187.770         383.908   7.0.3
10.104.200.107       Connected       PoweredOn      32        6265       83168         253.771         511.907   7.0.3
10.104.200.108       NotResponding   Unknown        32           0       83168           0.000         511.908   7.0.3
10.104.200.109       Connected       PoweredOn      32       19327       83168         314.887         511.908   7.0.3
10.104.200.106       Connected       PoweredOn      32       18674       83168         118.173         255.908   7.0.3
10.104.200.104       Connected       PoweredOn      32        7178       83168         120.683         255.908   7.0.3
10.104.200.105       Connected       PoweredOn      32        9654       83168         119.255         255.908   7.0.3

