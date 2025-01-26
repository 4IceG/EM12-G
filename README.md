# LTE-A EM12-G

![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/20201001.jpg)

## Toolz:
<details>
   <summary>Show me</summary>
  
<a href="https://drive.google.com/file/d/1z-ZPvb3Uh9V_uFDk8V3xW2ztFhnZPBgn/view?usp=sharing" title="Quectel_LTE_5G_Windows_USB_Driver_V2.2.4">Quectel_LTE_5G_Windows_USB_Driver_V2.2.4</a>

<a href="https://www.easypaste.org/file/n2AotGpX/QFlash.V5.1.EN.zip?lang=pl" title="QFlash.V5.1.EN">QFlash.V5.1.EN</a>

<a href="https://drive.google.com/file/d/1j3Wy_znL2ajt2_Rc4gejgoJRcp8ieQLm/view?usp=sharing" title="QFlash.V5.8.EN">QFlash.V5.8.EN</a>

<a href="https://drive.google.com/file/d/1RxYTDpxjcLEUSPtSRoa5lkxE_8eJMAeb/view?usp=sharing" title="QFlash_V4.18">QFlash_V4.18</a>

<a href="https://drive.google.com/file/d/1Gx1Ab5uLSAOaIlWzKHS17qE3Wo9hVQ7i/view?usp=sharing" title="Qnavigator_V1.6.10">Qnavigator_V1.6.10</a>

<a href="https://drive.google.com/file/d/1_s2tsLvVxjqN16O672-2sdwD6DZsmw9j/view?usp=sharing" title="Qnavigator_V1.6.9.1.zip">Qnavigator_V1.6.9.1</a>

<a href="https://drive.google.com/file/d/1xVw5IBowlKn7HPqfyYfoZdBx1p5Xs7aU/view?usp=sharing" title="QCOM_V1.6">QCOM_V1.6</a>

<a href="https://drive.google.com/file/d/1amE1TgwuLh0bgos1T6rQMphIOnv_f1_T/view?usp=sharing" title="Quectel_Linux_Android_SPRD_PCIE_Driver_V1.1.1">Quectel_Linux_Android_SPRD_PCIE_Driver_V1.1.1</a>

<a href="https://drive.google.com/file/d/1V9zK4IWE0zuZxEpAr2JOm4AID0yZrm6h/view?usp=sharing" title="Quectel_Linux_PCIE_MHI_Driver_V1.3.3">Quectel_Linux_PCIE_MHI_Driver_V1.3.3</a>

<a href="https://drive.google.com/file/d/1sg7HvKe5e66q7LfsqavEM9RiaKhCQjth/view?usp=sharing" title="QWinLog_V1.6.8_2021_0125.zip">QWinLog_V1.6.8_2021_0125</a>

<a href="https://drive.google.com/file/d/1QsTLaBU464WsqzK6KvBrz1ux730Ft1dJ/view?usp=sharing" title="QFirehose_Linux_Android_V1.4.9">QFirehose_Linux_Android_V1.4.9</a>


</details>

## Firmware:
<details>
   <summary>Show me</summary>

| Date | Version | Hint | Link |
| --- | --- | --- | --- |
| `2023-12-28` | *EM12GPAR01A21M4G_01.204.01.204* | `-` | <a href="https://drive.google.com/file/d/1t4VIvt4fgRwEN1SfrzXaNrmrqKKms3B1/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.202.01.202* | `-` | <a href="https://drive.google.com/file/d/15zlBsKhCQGmCyBmBclQcv3d2dnL3SUHW/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.009.01.009* | | <a href="https://drive.google.com/file/d/1u5RvZH4TxvCf6mUTDGe8smJPMqyZ6rr9/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.007.01.007* | | <a href="https://drive.google.com/file/d/12ZrR0ojtn1IITuzTVJ7m8j8sByLDSkdw/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.005.01.005* | | <a href="https://drive.google.com/file/d/1JC5TT5SDpaM8xacR_LXbMYE4JGbPCo7u/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_BETA1022_01.005.01.005* | | <a href="https://drive.google.com/file/d/1rSOZlNmB2hYXegyrTjYkDJ3V0mC40qsH/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.004.01.004* | | <a href="https://drive.google.com/file/d/124LQr3dZvyNPtNkrwYIhrZfwgXYnYuIR/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.003.01.003* | | <a href="https://drive.google.com/file/d/1cxDE2Hj8gT5Rowxg0rHuWru2G7hCEgln/view?usp=sharing">Download</a> |
| `-` | *EM12GPAR01A21M4G_01.001.01.001* | | <a href="http://www.ofmodemsandmen.com/firmware/EM12GPAR01A21M4G_01.001.01.001.zip">Download</a> |


</details>


## AT commands
<details>
   <summary>Show me</summary>
  
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

#Hard reset
AT+CFUN=1,1

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

</details>

![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/Quectel_EM12-G_LTE-A_Specification%20V1.1-1.png)
![](https://raw.githubusercontent.com/4IceG/EM12-G/main/Screens/Quectel_EM12-G_LTE-A_Specification%20V1.1-2.png)
