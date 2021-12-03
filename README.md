# M5-Stack-Projects
Sometimes fun and somehow useful hobby projects based on M5 Stack HW/SW
#Brought to you by shanghai-high-tech.com / J.C.Abad / Shanghai - China / 2021.12.3

Comments and instructions for "Time Till Damn Xmas Is Finally Over" App (TimeTillDamnXmasIsFinallyOverV16x.m5f) 

FOREWORD: "I hate Xmas, i really do!" ....please help stop the madness

A) The app works with two known issue (see point D and G)

B) HW/SW Platform: M5 Stack Core 2 (yellow/touch) & UI Flow V1.8.7 (webbased) 

C) The audio file is not my IP and therefore not uploaded to Github, here is how you can get it/ convert it; 
a) first download the orignal audio file from  

https://mp3download.to/8en/cIuYFCAJ2a8.html (Chose Audio tap, download Audio LOW quality M4A format (1.28MB)

b) Download WavePad audio editing software (or similar) https://www.nch.com.au/wavepad/index.html?kw=wav%20file%20cutter&gclid=Cj0KCQiA-qGNBhD3ARIsAO_o7yk6dWG67-pdULo2CpzgAl1MmgqOpoAySki63lzquZh2EWwtVUzvoVEaAmEdEALw_wcB  

c) Open *.M4A audio file, no need to cut or edit, just "Save As", chose WAV format, sampling frequency 16000 Hz (16kHz), 16 bit , calle it "Maneskin-Beggin1.wav".

d) Copy the *.wav file to the root directory of your micro-SD card (using a USB card reader/writer or your computer integrated SD card reader with a micro-SD adapter like in my case). 

e) Follow the usual steps to make sure the card content is not corrupted when unplugged. 

e) Insert the micro-SD in your M5 Stack Core2 (i would switch off the Core to insert or extract the micro SD card).


D) [KNOWN ISSUE 1] The playing of the audio file is BLOCKING i.e. the UI is frozen till song finish playing (but date time information  is based on  RTC and therefore UI refreshing every 1s is resumed correctly afterwards). 

F) IMPOPRTANT: The App needs WIFI connectivity to get local time from public website 

D) On UiFlow (webbrowser) choose Core2 (appears with gray border, no yellow version( change yoru device API KEY

E) Open the *.m5f app source coude and edit the Wifi SSID and its Password according your local WIFI netwowrk

F) Do the same with the publc website to get the local time information via internet i.e. set the right URL and adjust the time zone index accordingly ;
the time zone index follows the GMT time zone +1 apparently e.g. i am in Shanghai and the time zone index is 9. If not sure just adjust it till you get your local time.

G) [KNOWN ISSUE 2] Sometimes during app boot up the RTC information is the wrong/default one , this is the case when i have VPN on on my host computer and/or when the internet connectivity is poor/unreliable; the only way to "solve it" (workaround) is to try and reboot again. 

Please dont hesitate to contact me for hobby-like questions to jcabad100@yahoo.com. On the other hand if you need professinal consulting for engineering (HW/SW/ME) or expert sourcing of Chinese high-tech equipment, machinery and/or solutions (no matter which industry) please contact me at:

Juan Carlos Abad (MSEE/MACS/MBA/PMP/CSM/CSPO)
Managing Partner 
Shanghai High-Tech Business Consulting Co., Ltd.
总经理兼创始人/上海芯珏商务信息咨询有限公司
Email: jc.abad@china-high-tech.com
http://www.shanghai-high-tech.com/
Tel.: +86 173 2131 8574
