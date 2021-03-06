<!DOCTYPE html>
<html>
<body>
<h1 align=center>I3 and IOTA</h1>
  
**This workshop includes step-by-step instructions for buying and selling data on the I3 Marketplace**  

Researchers at USC and IOTA teamed up to conduct experiments building IoT Devices and connecting them to the I3 Marketplace so they could buy and sell sensor data.  They stored data in the IOTA Tangle.  The results were demonstrated at the <a href="pubs/I3-Onramp.pdf">Aug-2019 I3 Intelligent-Integrated IoT Conference and Workshop hosted by USC</a>

In this workshop, you learn to build your own IoT Device, connect it to I3 Marketplace, and store data in the Tangle.  You can follow these step-by-step tutorials or you may attend this workshop in person by joining this [MeetUp](https://www.eventbrite.com/e/intro-to-iot-i3-and-iota-tickets-71737176827).  If you want to facilitate this workshop, here is the [facilitator's guide](FacilitatorsGuide.md).

<h3>Step 1:  Building your IoT device</h3>

[AstroPiOTA](https://github.com/NelsonPython/AstroPiOTA) and [EnviroPhat](https://github.com/NelsonPython/EnviroPhat) are easy to build because you snap together two components.  [CO2-TVOC](https://github.com/NelsonPython/CO2TVOC) requires connecting a few wires.  [Autonomous Gardener](https://github.com/NelsonPython/AutoGardener) has multiple components with a more complex wiring scheme. 

<h3>Step 2:  <a href="https://github.com/NelsonPython/Connect_IoT_Device_to_I3">Connecting your IoT device to the I3 Marketplace</a>	</h3>

This [Software Development Kit](https://github.com/ANRGUSC/I3-SDK) provides sample scripts that can be used by publishers and subscribers on the I3 real-time IoT data marketplace for smart communities.  Each of these tutorials includes a step-by-step code walkthrough explaining its data publisher and subscriber:

- <a href="https://github.com/NelsonPython/AstroPiOTA">AstroPiOTA environment sensor</a>

- <a href="https://github.com/NelsonPython/EnviroPhat">EnviroPhat temperature</a>

- <a href="https://github.com/NelsonPython/CO2TVOC">CO2-TVOC air quality sensor</a>

<h3>Step 3: Storing and evaluating your data</h3>

Here is a sample chart showing data collected by four IoT devices over a 24 hour period

<img src="chart.png" width=900>

### Viewing data on the [Tangle](https://docs.iota.org/docs/getting-started/0.1/introduction/what-is-the-tangle)

<a  class="w3-btn" href="https://devnet.thetangle.org/address/VFMEYGUNJVBMRFORVRIOHVET9L9A9AJFCETCOEVI9WPJPRWWALLOBFLXQGGHTZWQKTBJELJNVA9SILXVZTMPMXKPWC">AstroPiOTA</a>

<a  class="w3-btn" href="https://devnet.thetangle.org/address/ZNJWDJBGQVLCNJIRXPDUKHESBYXGFADCKAUCXFZFCWEOUJOJIDZHDCMVQQTEMZIMPOXFCTM9QSNNUZVBX">AutoGardener</a>

<a  class="w3-btn" href="https://devnet.thetangle.org/address/K9LYCBRIBMKPDPMDPTJSQTCXYVPBULSIRQZJEHINYQXBYNFCFSWUXIMXELKTGXCZLYDZNDJEVKSOBWDXXTTNMMPRPC">CO2-TVOC</a>

<a  class="w3-btn" href="https://devnet.thetangle.org/address/ORTP9BWTENDHERKNXRHRN9CAYPWSUXDPUZGFJVV9APCWORUFSE9N9OQYBSJEQAIBHJSWBIGFNQUDT9IUWBBPUYLAHB">EnviroPhat</a>

### Viewing data in ThingSpeak channels

[AstroPiota data visualization](https://thingspeak.com/channels/865101)

[EnviroPhat data visualization](https://thingspeak.com/channels/865246)

[CO2 data visualization](https://thingspeak.com/channels/865249)

### Prototyping and testing utility

[Retrieving data from Tangle test addresses](utility/README.md)

### Learning resources

[Learn Python Playlist](PythonPlaylist.md)


</body>
</html>
