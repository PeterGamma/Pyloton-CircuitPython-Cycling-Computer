Pyloton: Open Source cycling computer that displays heart rate, speed, cadence, and song playback info

https://learn.adafruit.com/pyloton

To stream sensor data from a Garmin sensor to Matlab or Python, it has in Matlab an instruction which is probably easy to make real for PhD in computer engineering. The Adafruit instruction CircuitPython BLE Heart Rate Zone Trainer Display is a 33 pages when printed it out on my PC printer.

With Bitalino, you can pair an ECG devise via bluetooth to a PC running Matlab or Python directly. Why can Garmin BLE sensors not be paired directly to a PC?

I could not find an option to stream sensor data further to PC applications in the Adafruit apps, but circuits of the Adafruit Pytholon cycling computer are Arduino compatible. Arduinos can be connected over usb to Matlab. 

It maybe will take some time to go through the instruction of the Pyloton, but it is an extraordinary device in that sense that it is very rare to find a device which is open source in the field of sporting devices. It is a device, which you don t have to develop first, and the instruction is excellent.

Pyloton - CLUE Bike computer. Instructional video:

https://www.youtube.com/watch?v=viR-2dUP55g&t=2s

Discussion in the Matlab community:

.
https://www.mathworks.com/matlabcentral/answers/538547-example-code-to-connect-a-bluetooth-smart-ble-heart-rate-sensor-to-matlab?s_tid=prof_contriblnk

Discussion in DC Rainmakers Blog:

.
https://www.dcrainmaker.com/2020/01/computers-worldtour-peloton.html/comment-page-1#comment-3574150

You can also download the instruction for the Pyloton from Adafruit, PDF is 55 pages:

https://cdn-learn.adafruit.com/downloads/pdf/pyloton.pdf?timestamp=1590963864

There is no real-time Open Source Data aquisiton software available fot the Pyloton. Integration into OpenSignals?

https://forum.bitalino.com/viewtopic.php?f=19&p=2207#p2207

Adafrui'ts Little Secret - CLUE

https://youtu.be/_7QsbwBeSiU

I was looking for optimal tools for meditators. Bike Computers seem to be specially suitable for it. I was interested in the Garmin Varia Vision. It works best with Bike Computers. Now I m looking for a real time data aquisition system. Most promising looks a Bike Computer. I m happy that the Pytolon is an  Open Source cycling computer, so I can adapt it sooner or later to the needs of meditators.

Review I wrote in the DC Rainmakers Blog:


Here is a new one:

Pyloton: CircuitPython Cycling Computer

Open Source cycling computer that displays heart rate, speed, cadence, and song playback info!

link to learn.adafruit.com

You have to build it yourself. But it is only limited by your imagination.
Reply

    Peter Gamma
    May 31, 2020 at 1:05 pm #16

    I m new in the field of Pelotons. The name of the Adafruit Pyloton is probably a composition of the word Peloton and Python. It is extraordinary in the sence that is the only commercially available open source device which I could find to this date.

    The name Pyloton suggests, that it was designed to be used as a Peloton, which is great. Since I was looking for a device where it is possible to access the ANT or BLE sensor by a PC application.

    The instruction for the Peloton on Adafruits websites is excellent. They have also a forum, but I could not find any entries yet for the Pyloton, it is a new product. Here I could find a demo video:

    link to youtube.com
    Reply
    Peter Gamma
    May 31, 2020 at 1:14 pm #17

    I was looking for a long time for a solution to stream ANT+ sensor data from sports sensors to Matlab or Python. But it’s difficult. In Matlab, there is an example for BLE sensors, but it is very theoretical, no practical application yet. So I was looking for an application for BLE GATT client-server, and then I found the Pyloton.

    It s an excellent instruction, and I love it. I was looking for a solution to pull out sensor data from the Pyloton, and I was looking at the Adafruit apps. But I could not see a solution. The circuit is Arduino compatible, and Arduinos can be connected by usb to Matlab or Python. That’s the solution which currently looks most promising to me.

    I propose to try to use this device in connection to Matlab or Python on a PC. As far as I know, there is no practical example with sensors in Matlab or Python to this date:

    link to mathworks.com
    Reply
    Peter Gamma
    May 31, 2020 at 2:10 pm #18

    Resellers for Bike computers, when customers asks for a device to send your training data in real-time to Matlab, recommend this device. Shame on Garmin 🙁
    Reply
    Peter Gamma
    May 31, 2020 at 2:27 pm #19

    Excellent device and instruction from Adafruit, but shame on Garmin when a modern cycling computer is compaired to this device, what a modern cycling computer could do with an open standard, which allows users to do anything they want with the device, and not limiting users in making real own developements.

    Adafruits device is a new developement, but Adafruits device does not limit users in what is possible with this device. Anything is possible with this device, sooner or later.
    Reply
    Peter Gamma
    June 1, 2020 at 7:32 am #20

    There where several Rasperri PI projects with an ANT+ stick, one of a former PhD student of the Swiss Federal Institute of Technology, one with a script which sends sensor data to an MQQT brocker to for instance Matlab or Python.

    But the Pyloton Open Source Cycling Computer is simpler. The path goes from a BLE to the Pyloton which consist only of one chip, and from there via usb to Matlab or Python. The software on the Pyloton is similar to the Matlab BLE example code.

    The sensor data are already displayed on the Pyloton, so there is nothing to do anymore in Matlab, exept for analysing the data. The path is short, and therefore more stable.

    What I miss on the PYLOTON is a open source real-time data aquisition software. It is difficult to access raw data from sporting activies for instance from a Garmin watch. Integration of the Pyloton into OpenSignals could solve this problem:

    link to forum.bitalino.com

    or a Windows Python project for the PYLOTON with graphs, plots and a format of data (csv?) which easy to access.
    Reply
    Peter Gamma
    June 1, 2020 at 10:41 am #21

    The Pytolon is based on a circuit which is Arduino compatible. It should be possible to port the code to a Rasperri Pi. And code which runs on a Rasperri Pi should also run on the new Linux Pinephone.

    link to store.pine64.org

    Pine, the developer of the Linux Pinephone produces mini PC which are Rasperri Pi compatible. The Linux Pinephone and a Rasperri Pi are very close to each other. Therefore, the code which runs on the Pytolon Open Source Bike Computer should also run on a Linux Pinephone in theory. This would be a very handy Bike Computer which has the size of a large Android Phone.

    Although I don t have any followers for this project yet, I m optimistic that this project will be successful, and will become attractive to more and more people, the easier the setup becomes.
    Reply
    Peter Gamma
    June 1, 2020 at 12:44 pm #22

    Summary:

    The GATT client-server for Bluetooth smart (BLE) is a path to stream BLE sensor data. It can be found in a Matlab example code without any practical example yet.

    But the same code is in the Pytolon Open Soure Bike Computer, and it has been demonstrated with heart rate and cadence sensors that it is working there. But the same code could also run on a Rasperri PI, a Linux Pinephone, a Linux PC or as mentioned before on a PC running Matlab.

    It is not about the right device, it is about the right code and the right sensors. This GATT client-server works as far as I know only with Bluetooth smart (BLE) sensors, and it is easier to use in my view than to use a ANT+ stick with ANT+ sensors.


