# Water_level_monitoring_sysytem

             Step 1
Firstly, identify these components.

             Step 2
Secondly, place the Nodemcu board and LEDs on the breadboard. And then, connect the resistors for the LED bulbs.

             Step 3
Thirdly, connect the LED bulbs to the Nodemcu board. For that, use the circuit diagram

             Step 4
Now, connect the LCD screen, ultrasonic sensor, and relay module to the Nodemcu board. Please use the circuit diagram 

            Step 5
Now, let’s set up the Blynk web app step by step. For that, follow the instructions below.
First, go to the Blynk website and create a new account using your email address. And then, log in to your account and create a new template for this project.
Now, click the datastream tab and create two data streams for that.
Virtual PIN / Name — Water level / PIN — V0 / MIN — 0 / MAX — 20 (The height of the water tank)
Virtual PIN / Name — Water pump / PIN — V1 / MIN — 0 / MAX — 1
After, click the web dashboard tab and create a suitable web dashboard for this project. For that, I used a button and one gauge widget.
Now, click the one-by-one setting buttons on the widgets and select the water level data stream for the gauge widget and the water pump data stream for the button widget. Finally, click the save button.
Next, click the search icon button and create a new device. For that, select the template you created earlier.
OK, the Blynk web dashboard is ready.

             Step 6
Now, let’s set up the Blynk mobile dashboard for this project. For that, follow the instructions below.
First, download and install the Blynk app on your smartphone. Then, click the template you created on the web dashboard.
Next, add a button widget and one gauge widget to the dashboard. And then, customize these widgets as you like.
Now, select the “water level” data stream for the gauge widget and the “water pump” data stream for the button widget. And then, name these widgets as you like.
Ok, the Blynk mobile dashboard is ready for use.

            Step 7
Ok, now connect the Nodemcu board to the computer and upload the program for this system.

       After that go to our program and do this 
Now, copy and paste the Blynk auth token, It’s in the Blynk web dashboard. For that, click the device info tab.
And then, enter your WIFI SSID and password. After, enter the height of the water tank. I used a 20 cm water cup for this project.
Now, select the board and port. After, upload this program to the Nodemcu board.
Ok, now you can test this project.

HAVE A GREAT DAY......................
