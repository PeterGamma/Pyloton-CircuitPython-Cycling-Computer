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


You can also download the instruction for the Pyloton from Adafruit, PDF is 55 pages:

https://cdn-learn.adafruit.com/downloads/pdf/pyloton.pdf?timestamp=1590963864

Adafrui'ts Little Secret - CLUE

https://youtu.be/_7QsbwBeSiU


Discussion in DC Rainmakers Blog:

.
https://www.dcrainmaker.com/2020/01/computers-worldtour-peloton.html/comment-page-1#comment-3574150

JOHN PARK'S WORKSHOP LIVE 2/13/20 Pyloton @adafruit @johnedgarpark 

https://www.youtube.com/watch?v=5rAWbyKmK0s

Make yourself free from the dependency of Gamin. Read the 55 pages of instruction for the Pyloton Open Source Bike computer (pdf printout):

https://cdn-learn.adafruit.com/downloads/pdf/pyloton.pdf?timestamp=1591071856

And build your own Pyloton. The only problem which is not descripted is how to read out sensor data from the Pyloton usb port. But this should be possible. There are many instructions for Matlab, Python or other PC applications how to connect to an Arduino through usb, and the Pyloton is Arduino compatible.

There is no real-time Open Source Data aquisiton software available for the Pyloton. Integration into OpenSignals?

https://forum.bitalino.com/viewtopic.php?f=19&p=2207#p2207


I copied my posts from the Adafruit youtube Video to this locatotion:

https://www.youtube.com/watch?v=viR-2dUP55g&t=2s

My vision of the future of the Pyloton is:

1. A version of the Pyoton for the Rasperri PI would be great, to have a storage card device as a data grabber to store data in an easy accessible way, for instance in Matlab friendly .csv. 

2. Do you know the new Linux Pinephone? I don t have one yet, but I certainly buy one. It is a real Linux Smartphone computer. A version of the Pyloton for the Linux Pinephone would be my favorite: large display, repleacable batteries, easy to use Linux platform for software developement. 

All these things would make the Pyloton software project a great open source cycling computer which can compete with the latest bike computers from Garmin, or even beat them.

For a Rasperri PI version I would choose the Rasperri PI zero, which can run up to 20h with a 4500 mAh battery. So you get an alternative for a Garmin watch, which has a battery life of about 20 h with GPS off. A Pyloton Rasperry PI zero would be much more attractive for me personally than  a Garmin watch, for me as a meditator, and also for many other who love computing :-)

There is currently no solution for Matlab to directly access sensor data for instance from Garmin devices. A Pyloton Rasperri Pi could solve this problem. Rasperri Pi has excellent support in Matlab. BLE chest strap or Polar OH1 BLE heart rate  sensors are excellent research grade devices. These sensors are low cost high quality, and will be successful, not only for sporting activity, but also for science.
 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6732081/

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6532910/

The accuracy of the Polar H7 BLE chest strap and the Polar OH1 BLE optical heart rate sensors is near to an ECG device,  which are the most accurate heart rate measurement devices available. And they are low cost high quality, at about 10 percent of the cost of for instance an Adinstruments equipement with comparable accuracy. Support of the Polyoton for Matlab or desktop Python would make out of the Pyloton a research grade device, for research institutes, research scientists, and hobby scientists who want to write their own paper.

