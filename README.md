 For this SOA Project, I decided to work on five different scenarios: 
 
● The first scenario, opening / closing of shutter depending on the luminosity: For this service to work properly it was necessary to consider the managing of the shutter, from monitoring the current opening level to updating the shutter’s status.

● The aim of the second scenario is to control air temperature. If the temperature is higher than 25°C, windows have to be opened so the room can be ventilated. This scenario uses a temperature sensor and a window actuator. 
 
● The third scenario is Air quality scenario: the microservices created was for the CO2 sensor. The CO2 microservice simulates a sensor reading and was fairly simple to code. Accessing the service returns a randomly generated number between 0-3000 ppm. With better planning and time management it would be possible to program this virtual sensor further, adding the more complex functionalities I originally planned for. Unfortunately I had to discard most of these ideas in the interest of finishing the project on time with what I had.
 
● The aim of the fourth scenario is managing closing and opening doors and windows according to constraints of Covid pandemic, here I defined three use cases depending on the number of students in the classroom.

Use case 1: After every use of the classroom and for 15 minutes, the door is automatically closed, and the windows are being opened in order to start the aeration process.
 
Use case 2: When the number of students in the room is >= 25, then the alarm is trigged until the number of students decreases.
 
Use case 3: When the number of detected persons is > 0 and < 25, the door is open and the windows are closed:
 
● The fifth scenario, I want to turn on lamp if a presence is detected in the room. To do so, I just need lamp and a presence sensor. 
 
