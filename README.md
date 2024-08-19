<h1 align="center">Project Satellite</h1>

<p align="center"><img src="https://github.com/Gregster31/Satellite-Project/assets/123277418/9702bb2e-7b63-49f1-a217-794bc5e0a41c" alt="project-sat"></p>
<p align="center">Receiving and decoding telecommunications from a NOAA weather satellite into images</p>

<h2>🚧Project explanation</h2>
This project uses an homebuilt double-crossed antenna and a <a href="https://www.nooelec.com/store/sdr/sdr-receivers/nesdr-smart-sdr.html">Nooelec SDR</a> to capture frequencies from a weather satellite and convert them into readable data. This project stems from my found interest in receiving different kinds of frenquencies. I will now be showing my process.

<h2>📒Guide</h2>
<h3>📡Assembling the Antenna</h3>
The satellite telecommunications that we are trying to intercept are 137Mhz and right hand circularly polarized. That's why I chose to use a double-cross antenna which makes it easier to intercept these frequencies from different directions.

![Circular Polarization Animation](https://upload.wikimedia.org/wikipedia/commons/d/d1/Circular.Polarization.Circularly.Polarized.Light_Left.Hand.Animation.305x190.255Colors.gif) <br>

Article used for construction of antenna: https://qsl.net/py4zbz/DCA.pdf <br>
![Double Cross Antenna](https://www.dxzone.com/dx30769/double-cross-satellite-antenna.jpg)

Step 1:  
For the antennas, I used galvanized metal hangers. I stripped them to bare metal and cut 8 of them to 52cm. The length is very important because it will affect the frequencies you can intercept.  
<img src="https://github.com/user-attachments/assets/1bec0462-2b62-496e-bede-df4f3bdc0a76" style="transform: rotate(-90deg); width: 500px; height: 600px;" />

Step 2:  
I taped 2 antennas to a small piece of wood.  
<img src="https://github.com/user-attachments/assets/6acc4e71-f2ff-4e50-bbc1-9c9d65e3a7a5" style="transform: rotate(-90deg); width: 500px; height: 600px;" />

Step 3:  
I made a support for the antenna.  
<img src="https://github.com/user-attachments/assets/65dfd295-3544-4637-bfaf-10471c833dbb" style="width: 500px; height: 700px;" />

Step 4:  
Screwed all the pieces together to make the antenna.  
<img src="https://github.com/user-attachments/assets/7e2abdcd-1df4-4fa6-b7f4-5974534d9656" style="width: 500px; height: 700px;" />


Step 5:  
Add the coaxial cable of 50 ohms. I have to go buy some.

<h3>💿Setting Up the SDR</h3>


<h3>🗺️Tracking the Satellites</h3>
-NOAA 19 passes directly on top of us
-NOAA 15 TOO
-NOAA 18 MEH

<h3>🛰️Receiving the Signal</h3>
TODO

<h3>🌐Decoding the Signal</h3>
TODO

<h3>📍Results</h3>
TODO
