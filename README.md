# Milk Mixing System
This repository discusses about the project I created during my internship in Siemens India.
</br>
It is a simulation of a flavoured milk mixing plant in reference to these two video:
  <ul>
    <li><a href = "https://www.youtube.com/watch?v=LRDRaJmgu8s&t=1838s">Part 1</a> </li>
    <li><a href = "https://www.youtube.com/watch?v=kZQzd4Qz1bU&t=104s">Part 2</a></li>
  </ul>
<br/>
It creates two types of flavoured milks- Chocolate and Strawberry.
<h2>Hardwares Used</h2>
The hardware component used here is the <b>IoT 2050</b>, an  IoT edge device, which is a simple, cost-effective and flexible way of ensuring that any system, whether it is new or old, can take advantage of IoT and cloud related services. The IoT 2050 was used to implement a dashboard which was created using Node-Red.
Apart from that, a laptop is used for monitoring and simulation purposes.
<h2>Softwares Used</h2>
The softwares/tools used are:
  <ul>
    <li><b>TIA Portal:</b> The primary tool used for programming the PLC and for creating SCADA.</li>
    <li><b>WinCC:</b> This is necessary for designing the SCADA. It is used along with TIA Portal.</li>
    <li><b>Node-Red:</b> For creating the Dashboard.</li>
    <li><b>PuTTY:</b> Used for accesing the IoT 2050 through SSH and through serial communication.</li>
    <li><b>PLCSIM Advanced 4.0:</b> Since I couldn't have a physical PLC, I made use of this tool to create a simulated version of the S7-1200.</li>
  </ul>
<h2>SCADA</h2>
<img src = "https://github.com/jyotissh/milk-mixing-system/assets/43207029/de2b920c-bd98-44f7-bc31-47dcc72c89a4">
<h2>Dashboard</h2>
<img src = "https://github.com/jyotissh/milk-mixing-system/assets/43207029/1678e795-34b8-4d5c-84b3-2d08d5fe440f">
