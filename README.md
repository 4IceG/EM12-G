# LTE-A EM12-G

![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/20201001.jpg)

## Firmware & QFlash_V4.18 download:
<a href="http://www.ofmodemsandmen.com/firmware/EM12GPAR01A21M4G_01.001.01.001.zip" title="Firmware EM12GPAR01A21M4G_01.001.01.001.zip">Firmware EM12GPAR01A21M4G_01.001.01.001.zip</a>

<a href="https://drive.google.com/file/d/124LQr3dZvyNPtNkrwYIhrZfwgXYnYuIR/view?usp=sharing" title="Firmware EM12GPAR01A21M4G_01.004.01.004.zip">Firmware EM12GPAR01A21M4G_01.004.01.004.zip</a>

<a href="https://drive.google.com/file/d/1RxYTDpxjcLEUSPtSRoa5lkxE_8eJMAeb/view?usp=sharing" title="QFlash_V4.18">QFlash_V4.18</a>

EM12GPAR01A21M4G_01.004.01.004.zip

## AT commands
``` bash
#All bands:
AT+QCFG="band",0,42000000003300185a,1

AT+QNWINFO < Current band in use
AT+QCFG=”Band” < Current bands config
AT+CSQ < Check signal strength

AT+QCAINFO < CA Info
AT+QNWINFO
AT+QENG="servingcell"

#Change scan mode
AT+QCFG="nwscanmode",0,1 < Scan all modes
AT+QCFG="nwscanmode",1,1 < GSM only
AT+QCFG="nwscanmode",2,1 < WCDMA only
AT+QCFG="nwscanmode",3,1 < 4G-LTE only

#Set Connection Modes
AT+QCFG="usbnet",0 - QMI/PPP/Default
AT+QCFG="usbnet",1 - ECM
AT+QCFG="usbnet",2 - MBIM

#Factory reset
AT&F
AT&F1
AT+CFUN=1

AT+CFUN=0 - Turn off modem

#Band_value - Band#
1 - LTE BC1
2 - LTE BC2
4 - LTE BC3
8 - LTE BC4
10 - LTE BC5
20 - LTE BC6
40 - LTE BC7
80 - LTE BC8
100 - LTE BC9
200 - LTE BC10
400 - LTE BC11
800 - LTE BC12
1000 - LTE BC13
2000 - LTE BC14
10000 - LTE BC17
20000 - LTE BC18
40000 - LTE BC19
80000 - LTE BC20
100000 - LTE BC21
1000000 - LTE BC25
2000000 - LTE BC26
8000000 - LTE BC28
100000000 - LTE BC33
200000000 - LTE BC34
400000000 - LTE BC35
800000000 - LTE BC36
1000000000 - LTE BC37
2000000000 - LTE BC38
4000000000 - LTE BC39
8000000000 - LTE BC40
10000000000 - LTE BC41
20000000000 - LTE BC42
40000000000 - LTE BC43
20000000000000000 - LTE BC66
400000000000000000 - LTE BC71
```
![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/Quectel_EM12-G_LTE-A_Specification%20V1.1-1.png)
![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/Quectel_EM12-G_LTE-A_Specification%20V1.1-2.png)
