# openvedeo
A self-hosted client/server model for video hosting and sharing. This project consists of two parts:
<br>
<br>
<b>Web Service</b>
<br>
The web service is the method for uploading, storing, and sharing video content. A content creator will download a simple installation file (script, Snap package, etc), execute the file, answer a few questions, and then have a server ready to point to the outside world. From there, creators will use a front-end web client to upload content, customize their channel page, and make other modifications. The web service will also make a subscription URI available for viewers to subscribe to a server channel with and push out notifications when new content is available, among other actions.
<br>
<br>
<b>Clients</b>
The clients will be what viewers use to subscribe to new server channels, view content, and more. Clients will be available as mobile apps, desktop applications, and potentially a web interface. A cross-platform environment such as Electron might be desirable here, to make porting to Windows, Mac OS, Linux, and other environments easier.
<br>
<br>
<b>Service Diagram</b>
![Diagram of Openvedeo service](https://i.imgur.com/dtrJDQr.png)
