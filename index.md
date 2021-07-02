# IoT Weather Indicator
My weather indicator will show green, white, and yellow for each of the weathers cloudy, snowy, and clear. Personally, I believe it is much easier to look at a colored ring compared to checking the weather channel. I have modified the colors and weathers for my project to be most useful for myself since we don't usually get rain here. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Zijin Qin | American Fork High School | Computer Science | Incoming Senior

![Head Image](https://i.imgur.com/REjwurq.jpg)

# Demo Night

[![Demo Night](https://i.imgur.com/n97CQ60.png)](https://www.youtube.com/watch?v=EhOgjXtLBQo&t=4s "Demo Night"){:target="_blank" rel="noopener"}
  
# Final Milestone
I soldered the power, ground, and data input on the NeoPixel LED ring to three wires, which are connected to the breadboard. I then used the breadboard to connect the wires to different pins on the ESP32 development board using jumper wires. I used Weather Underground from IFTTT to connect the data to Adafruit, setting each of the weather as three numerical values. In Arduino, I used for and if loops to display the three different colors for each of the three weathers on the LED ring.

[![Final Milestone](https://i.imgur.com/EdGaPXt.png )](https://www.youtube.com/watch?v=qQdap_ZYzFU "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
I connected the LED circuit created for my first milestone to Adafruit. I created a dashboard on Adafruit and then created two feeds under that dashboard. The feeds controlled the output of the LED pin and its color. However, since the LED light bulb only has one color, the output can only be blue. I modified the Wifi SSID and passowrd in the Arduino code and changed the IO username and key to my own account in order for the connection to succeed. 

[![Second Milestone](https://i.imgur.com/teYTR6U.png)](https://www.youtube.com/watch?v=XbeRFjYvVtw "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone
My first milestone was creating a blinking LED circuit since an LED light bulb would be easier to control than the LED ring that would be used in my weather indicator. I used a breadboard and jumper wires for creating the circuit and linking the light bulb to my ESP32 development board. The cathode of the LED was linked to ground while the anode of the LED was linked to a resistor that was linked to D5 on the ESP32 board. I used Arduino to write the code, which put the LED's outputs as "high" and "low" with delays in between, creating a blinking appearance. 

[![First Milestone](https://i.imgur.com/m7CrPYl.jpg)](https://www.youtube.com/watch?v=l1HJ_1RsJoE&t=3s "First Milestone"){:target="_blank" rel="noopener"}

# Challenges
Some of the challenges I encountered during this project were creating the circuits and coding. During my first attempt at soldering the wires to the LED ring, the wires that came with the NeoPixel ring broke, so I had to use other wires to connect the ring to the breadboard. The coding part was stressful yet satisfying. Although I panicked over the LED not lighting up, I eventually figured out how to display the colors through researching about the coding language and my instructor's help. 
