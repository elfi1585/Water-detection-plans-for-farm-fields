1. Abstract:
	

2. Background/ Client Info:
	Our client is Andre Houssne from Jacob Springs Farm. He runs a small farm with several products, mainly dairy and meat. However, he also has a field in which he grows all variations of vegetables. The problem Andre has is that he does not know whether or not he is giving his crops enough water. That part of the farm is running on intuition only. He asked us to find a way to determine the moisture levels of the soil, so that he may use that data to determine how often and how much he has to water his crops and how deep the water goes when he waters them.

3. Design Requirements - Quantitative Measures:
	The requirements we have for this project are that we need to be able to measure moisture levels at different depths and at different locations in the field. furthermore, we need to be able to take the data given to us from the moisture sensors and put it into a graph so that other farmers would be able to use the given data for their own farms. We need to have sensors at one, two, and four feet in order to measure moisture at different depths in the soil. We also need these measurements to be fairly accurate so that the efficiency of the farm is as high as possible. The sensors also need to be easily moveable and reinstallable to measure moisture at differenct sections of the field.

4. Design Alternatives (Brainstorming etc.)
	At first, we thought about having three moisture sensors in one pipe and the sensors would stick out horizontally from the pipe. However, this posed a problem because it would be very difficult to get the sensors in the soil and have the soil be tightly packed around the sensors. We thought about having a device that would push them into the soil from the pipe after the pipe was inserted in the soil, but that idea proved to be too complex. We then came up with the idea to put the sensors at the bottom of the pipes, sticking out directly downwards, but that idea would have caused possible error because it would not fully sense the moisture. Finally, we came up with the idea to put three pipes in right next to each other at a forty-five dergree angle with the sensors at the bottom. The pipes would have a length of one, two, and four feet to measure the moisture at different depths. This is the design that we chose to stick with.

5. Overview of Process:
	Our solution has two identicle devices so multiple areas can be monitored at the same time. Both devices will be powered by a Raspberry Pi because it will be able to log data more easily than an arduino, and is small enough to fit in our critical component that is the waterproof encasement. The encasement will allow for the device to be left outside independant of common weather. There are also pipes that allow for the moisture sensors to get to their required depths. Multiple wires allow for the Raspberry Pi to control the sensors, and the multiple wires allow for easy removal of the Raspberry Pi as the wires can be removed at different segmentations. To easily read immediate data there will also be LCD screens.

6. Final Design:
	Description:
		Each device will have one Raspberry Pi, three moisture sensors, one waterproof encasement, one LCD screen, three pipes, and wiring to connect the electrical components. The moisture sensors will reach depths of one, two, and four feet.
	Manufacturing Process:
		The only parts that needed manufacturing were the critical components.

7. Testing & Analysis:
	Critical Components:
		Our critical components are the waterproof encasement and the piping of our device. We chose these to be our critical components because they are what separates our device from other moisture sensors. Other moisture sensors are often used for indoor watering of plants, or just briefly used outside in the garden. Our device will have to withstand weather from being left outside for extended periods of time, and also the flood of water that comes from actually flood irrigating the farm. It will also have to be placed deep underground as opposed to how most moisture sensors simply read the surface moisture of the soil. Our critical components serve the purposes that the waterproof encasement protects the Raspberry Pi and LCD screen from weather and the flood irrigation. Also, the pipes allow the moisture sensors to reach the required depths and also are high enough above the ground that the flood irrigation won't flow into the pipes and disturb the moisture reading.
	Analysis used in Design:
		
	User Testing:
		The first test showed that we needed an ADC for our Raspberry Pis to read analog input, and that our moisture sensors needed some calibrating.
  
8. Conclusion:
	

9. Bill of Materials:
	Total Budget: $375
	20' PVC Piping: ~$10
	Two Raspbery Pis with Accessories: ~$160
	Two Adafruit Waterproof Encasements: ~$40
	Six Moisture Sensors: ~$46
	Miscellaneous Parts: ~$23
	Rubber O-rings: Free (made from bicycle tires)
	Total Spent: ~$279
	Ammount Left to Spend: ~$96

10. Timeline:
	

11. Appendix:
	
