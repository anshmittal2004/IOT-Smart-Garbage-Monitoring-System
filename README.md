# IOT-Smart-Garbage-Monitoring-System
The unhygienic and nasty areas are increasing due to the overflow of garbage in public areas. To maintain cleanliness we made IOT-based garbage Monitoring System that will tell us whether the trash can is empty or full through the web server and you can know the status of your ‘Trash Can’ or 'Dumpsters' .
***************************************************************************************************************************************************************************************************************************
Introduction :
With an increase in population, the scenario of cleanliness with respect to garbage management is degrading exponentially. The unhygienic and nasty areas are increasing day by day due to the overflow of garbage in public areas. They are responsible for provoking several diseases to nearby people and degrading the value of the area. Nobody likes to visit these places due to its uncleanliness. To maintain cleanliness we are going to make an IOT-based dumpster/garbage Monitoring System that will tell us whether the trash can is empty or full through the web server and you can know the status of your ‘Trash Can’ or 'Dumpsters' from anywhere in the world over the Internet. It will be very useful and can be installed in Trash Cans in public places as well as at home.
***************************************************************************************************************************************************************************************************************************
The high increase in industrialization and human population resulted in higher levels of garbage generated in urban areas.Therefore,the number of garbage bins needs to be increased and placed in strategic locations for  real time monitoring and collection to protect the environment.
Currently,smart cities are highly populated due to rural inflow to urban regions.This causes a significant increase in waste disposal and cause harmful effects to humans by certain respiratory problem and also air and land pollutions.Due to the lack of proper monitoring and control of wast,the garbage bins mainly appear to be flooded and spilling out into the surrounding causing many health problems.This situation should be taken into serious consideration by the relevant authorities and communities to manage waste disposal.
Basically a ‘Smart Garbage Monitoring System’ is a technology-driven solution to better waste management processes by utilizing sensors, data analytics, and IoT devices. This system helps in efficiently managing waste collection, reducing fuel costs, and improving overall cleanliness in cities.
Smart Garbage monitoring system offers a promising solution to enhance the waste management process making them more efficient, promising solution to enhance waste management practices, making them more efficient, cost-effective environmentally friendly, and sustainable. These systems lay out the way for smarter, cleaner, and more livable cities.
***************************************************************************************************************************************************************************************************************************
Literature Survey:
The Idea of Smart Garbage monitoring system is not an original idea,it is implemented beforehand.Some authors used mobile applications designed by them and enhanced them with more technology for receiving signals and displaying information.Some authors proposed garbage monitoring system using microcontroller and IR sensor and Wifi module.This system indirectly reduced traffic in the city,also helped to monitor fake reports by municipality area workers and hence improved the overall waste management system.This also improved cleanliness of the city. The System informed the 
status  of  each  and  every  dust  bin  in  real  time  so  that  the 
concerned  authority can  send the  garbage  collection vehicle 
only when the dustbin is full.
***************************************************************************************************************************************************************************************************************************
Methodology:
Working-
In this project, an Ultrasonic sensor is utilized to detect whether the trash can is filled with garbage or not. Here, the ultrasonic sensor is installed at the top of the trash can and it will measure the distance of garbage from the top of the trash can and we can set a threshold value according to the size of the container. If the distance is less than this threshold value, it means that the Trash can is full of garbage and we will print the message “Basket is Full” on the if the distance is more than this threshold value, then we will print the message “Basket is Empty”. Here we have set the Threshold value of 5cm in the Program code. We will use the ESP8266 Wi-Fi module for connecting the Arduino to the web server. Here we have used a Local webserver to demonstrate the working of this Garbage Monitoring System.
Basically, as the level of the dustbin is full the sensor will send a signal to the Arduino and we can see the output through the IP Address on the screen, by message as “Trash can Full”, otherwise if the trash can is full by 50% or more then we can measure the distance through the ultrasonic sensor.
***************************************************************************************************************************************************************************************************************************
COMPONENTS REQUIRED-
•	Arduino Uno
•	ESP8266 Wi-Fi Module
•	HC-SR04 SENSOR
•	1K RESISTORS
•	BREADBOARD
•	JUMPER WIRES
***************************************************************************************************************************************************************************************************************************
ARDUINO UNO-
A well-known microcontroller board built on the ATmega328P is the Arduino Uno. Because of its versatility and ease of use, it is frequently utilized by professionals, students, and amateurs to create a wide range of electronics projects.
Microprocessor-The ATmega328P microprocessor, running at 16 MHz, is the brains behind the Arduino Uno. In addition to analog inputs, timers, serial communication interfaces, digital input/output pins, and more, this microcontroller has them all.
The Uno includes six analog inputs and fourteen digital input/output pins, six of which can be utilized as PWM outputs.
Programmability-The Arduino Software (IDE), which is built on a condensed version of the C and C++ languages, can be used to program the Arduino Uno. Programmable tasks are carried out by the board when users create code and submit it to it via USB.
Options for Power: The board can be powered by a battery, an external power source, or a USB connection. It uses 5 volts DC to function.

ESP8266 Wi-Fi Module-
WIFI Module ESP8266 (NodeMCU) ESP8266 is inexpensive device that is designed with self contained SOC and integrated TCP/IP protocol stack which allows microcontroller to access the WiFi network. The module is capable to host an application or offloading all WiFi networking functions from another application processor. The module produced enough power and storage capability that allows it to be integrated with sensor or other applications through its general-purpose of input or output pin (GPIO). In this project, ESP8266 is used to access the Wifi network in order to send data to the database. The ultrasonic sensor is connected to o Wifi module GPIO pin act as a Nano microcontroller.

Ultrasonic Sensor HC-SR04-
Ultrasonic  sensor  (HC-SR04)  measures  the  distance  of  an object  by  using  sound  waves. The Ultrasonic Sensor is used to measure the distance with high accuracy and stable readings. It can measure distance from 2cm to 400cm or from 1 inch to 13 feet.  It emits an ultrasound wave at the frequency of 40KHz in the air and if the object will come in its way then it will bounce back to the sensor. By using that time which it takes to strike the object and comes back, you can calculate the distance. The  distance  is measured  by sending out a sound wave at a specific frequency and emitted to the sound wave . The time between the sound wave being transmitted  and  emitted is  recorded to  calculate the  distance between  the ultrasonic  sensors and object.  The  sound  wave travelled two times of distance towards the object before it is detected by the sensor. The distance is considered as a distance from ultrasonic sensor to object and from object to ultrasonic sensor. This measurement is known as a round-trip. Therefore, the  distance  can  be  measured  by  dividing  the  round-trip distance into  half using  equation (1), with  the speed  value is equivalent  as  the  sound  wave  travelled  through  air approximately at 344 m/s.
***************************************************************************************************************************************************************************************************************************
Result and Discussion:
The implementation of a Smart Garbage Management System using IOT has proven to be transformative for analyzing successful waste optimization and management. The advancement of technology will further improve system efficiency and enhance operations for more efficient sustainability. The use of ultrasonic sensor in waste bins will be used for monitoring of waste levels and reduce the littering of extra garbage. Hence, this setup can be used within the garbage boxes in the municipality areas and the ultrasonic sensors will be used for waste level to ensure the cleanliness of the area.
***************************************************************************************************************************************************************************************************************************
Conclusion and Future Work:
The smart garbage monitoring system plays a vital role in modern waste management by leveraging technology to optimize waste collection processes. It offers municipalities and waste management authorities an efficient means of monitoring, managing, and optimizing waste collection, thereby contributing to cleaner and more sustainable urban environments. Despite certain challenges, the benefits in terms of resource optimization, cost savings, and environmental impact make it a valuable solution for modern cities striving for efficient waste management practices.
***************************************************************************************************************************************************************************************************************************
Applications:
Urban Areas: Effective management of waste in urban areas where population density and waste generation rates are high.
Smart Cities: Fits into the concept of smart cities, promoting sustainability and efficient resource management.
***************************************************************************************************************************************************************************************************************************
Benefits:
Efficient Collections: Helps in optimizing waste collection routes, reducing fuel consumption and operational costs.
Timely Collection: Ensures bins are emptied before reaching overflow, preventing littering and environmental hazards.


























FUTURE WORKS:

This model can be used optimally in farms to help farmers reduce their time and work.
Farms often generate animal waste. Smart garbage monitoring systems can track waste levels in designated areas or bins, enabling timely removal or treatment.


 



Monitoring crop residue bins helps in managing agricultural waste, ensuring it's removed or repurposed efficiently.
Monitoring waste levels in compost piles or bins enables farmers to optimize composting processes, ensuring proper decomposition and nutrient-rich soil production.
By optimizing waste handling and resource utilization, smart garbage monitoring systems can potentially lead to cost savings through reduced labor and waste management expenses.
