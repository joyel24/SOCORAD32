# SOCORAD32 - ESP32 SOftware COntrolled RADio
<br />This device contains all you need to build a fully functional walkie talkie. It shares the same properties as the commercial one. Here it is used both for voice and data communication. Because it can communicate data, we can explore the amateur radio frequency for IoT.
<br />The central module contains the special purpose RDA1846 IC. This same IC is used in commercial walkie talkies such<br/>
as in Baofeng and Hytera.
<br />Other of its peripherals are an onboard ESP32 for paramter settings (via bluetooth or WiFi), control and storage. 
<br/>The ESP32 talks to the central module using simple AT commands. The specifications are listed below

# Specifiications
Frequency Range 400mhz -470mhz covers most countries allocated walkie talkie frequencies, escpecilly the license free ones.
<br/> Frequency Step: 5K/6.25K/12.5K/25K
<br/> RF Output Power: 2W/1W/0.5W
<br/> Voice encryption (scrambling): 8 type
<br/> Voice Compression -Expansion:
<br/> SMS Receive/Transformer, The space Baut: 1200
<br/>CTCSS (38 group) + CDCSS (83 group)
<br/> Automatic eliminination tail
<br/> Volume Adjustable (1-8)
<br/> SQ level adjustable (0-9)
<br/> MIC sensitivity level adjustable (1-8)
<br/> Sleep Mode (0.1uA)
<br/><br/>To talk to the module, a generic blueooth serial communication APP is used on phone to connect to the ESP32 module which in turn communicate with the module via UART. Due to the SOCORAD32 rich features, it can be used for the following applications.

<br/>The device contains a dedicated PTT button and extra   vvvvvvvvvvvvvvvvvvv buttons for users configurations.

# Applications
walkie talkie
<br/>Intercom
<br/>Pager
<br/>IoT (data transmission module)
<br/><br/>The AT commands are in the repository. It includes commands for volume control, power output, transmit/recieve frequency, Voice Ativated Exhange, squelching, etc