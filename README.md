# Jarkom-Modul-5-D07-2022

## Kelompok D07

| **No** | **Nama**                     | **NRP**    |
| ------ | -----------------------------| ---------- |
| 1      | Reza Maranello Alfiansyah    | 5025201071 |
| 2      | Nuzul Abatony                | 5025201107 |
| 3      | Muhammad Raihan Athallah     | 5025201206 |


IP Prefix Kelompok: `192.188`

![image](https://user-images.githubusercontent.com/72775603/206851940-2732de75-b118-4bfa-ae22-95e7f8e72bb5.png)
![image](https://user-images.githubusercontent.com/72775603/206852065-7c68848b-ad43-45f2-a99b-6349da338a46.png)
![image](https://user-images.githubusercontent.com/72775603/206852068-bf81f75c-1719-467f-874e-a0e1bd3b9fd3.png)
![image](https://user-images.githubusercontent.com/72775603/206852071-5ee90981-ce52-436e-b1fa-96b6665ef3c6.png)

Dest Network	A2   

Next Hop	    Ostania eth0

Command	      route add -net 192.188.4.0 netmask 255.255.254.0 gw 192.188.7.146

Dest Network	A3

Next Hop	    Ostania eth0

Command	      route add -net 192.188.6.0 netmask 255.255.255.0 gw 192.188.7.146

Dest Network	A5

Next Hop	    Ostania eth0

Command	      route add -net 192.188.7.128 netmask 255.255.255.248 gw 192.188.7.146

Dest Network	A1

Next Hop	    Westalis eth0

Command	      route add -net 192.188.0.0 netmask 255.255.252.0 gw 192.188.7.150

Dest Network	A4

Next Hop	    Westalis eth0

Command	      route add -net 192.188.7.0 netmask 255.255.255.128 gw 192.188.7.150

Dest Network	A6

Next Hop	    Westalis eth0

Command	      route add -net 192.188.7.136 netmask 255.255.255.248 gw 192.188.7.150

