1. Abstract:
	Our client was Andre Houssne from Jacob Springs Farm. He came to us because he uses flood irrigation to water his crops, which caused a problem for him that he did not know whether or not he was adding too much or too little water to his crops. Our solution to this problem was that we created a moisture sensor that can be inserted into the soil wherever he chose, and gave him live readings of the moisture at that location. That way, the guess work in watering his crops would be eliminated. After much brainstorming, we designed our final product that had a wooden stand which kept the electronics above the ground when the water was running over the soil. We had three PVC pipes of different lengths which housed the wiring that connected the Raspberry Pi to the moisture sensors. The pipes were inserted into the ground at a forty-five-degree angle facing the water source so that the moisture sensors would have the most surface area possible to come in contact with the water to get the most accurate reading. Our moisture sensors were at the bottom of the pipes, which were waterproofed using a waterproof foam that expanded and hardened when dry. On top of the wooden stand we had a weatherproof box that housed our electronics, including the Raspberry Pi, the LCD screen, the wires, and the solar panel. The Raspberry Pi could easily be removed and plugged into a computer monitor in order to extract and analyze the moisture readings at different depths and when they changed. Our final product was very sturdy and strong. After the moisture sensors were calibrated, they sent readings to the LCD screen to display, which changed colors depending on the moisture level. When we showed our product to Mr. Houssne, he was ecstatic and couldn't wait to use it on his farm.

2. Background/ Client Info:
	Our client was Andre Houssne from Jacob Springs Farm. He runs a small farm with several products, mainly dairy and meat. However, he also has a field in which he grows all variations of vegetables. The problem Andre had was that he did not know whether or not he was giving his crops enough water because the method he uses to water his crops is flood irrigation. That part of the farm was running on intuition only. He asked us to find a way to determine the moisture levels of the soil, so that he may use that data to determine how often and how much he has to water his crops and how deep the water goes when he waters them.

3. Design Requirements - Quantitative Measures:
	The requirements we have for this project are that we need to be able to measure moisture levels at different depths and at different locations in the field. Furthermore, we need to be able to take the data given to us from the moisture sensors and put it into a graph so that other farmers would be able to use the given data for their own farms. We need to have sensors at one, two, and four feet in order to measure moisture at different depths in the soil. We also need these measurements to be fairly accurate so that the efficiency of the farm is as high as possible. The sensors also need to be easily moveable and reinstallable to measure moisture at differenct sections of the field.

4. Design Alternatives (Brainstorming etc.)
	At first, we thought about having three moisture sensors in one pipe and the sensors would stick out horizontally from the pipe. However, this posed a problem because it would be very difficult to get the sensors in the soil and have the soil be tightly packed around the sensors. We thought about having a device that would push them into the soil from the pipe after the pipe was inserted in the soil, but that idea proved to be too complex. We then came up with the idea to put the sensors at the bottom of the pipes, sticking out directly downwards, but that idea would have caused possible error because, as the water flows and saturates the soil at an angle, it would not fully sense the moisture. Finally, we came up with the idea to put three pipes in right next to each other at a forty-five dergree angle with the sensors at the bottom. The reason we chose to do this was so that the sensors could face the water source, thus giving the sensors the maximum amount of surface area to come in contact with water, thus giving the most accurate reading. The pipes would have a length of one, two, and four feet to measure the moisture at different depths. This is the design that we chose to stick with.

5. Overview of Process:
	Our solution has two identical devices so multiple areas can be monitored at the same time. Both devices will be powered by a Raspberry Pi because it will be able to log data more easily than an arduino, and  it is small enough to fit in our critical component that is the waterproof encasement. The encasement will allow for the device to be left outside independant of common weather. There are also pipes that allow for the moisture sensors to get to their required depths. Multiple wires allow for the Raspberry Pi to control the sensors, and the multiple wires allow for easy removal of the Raspberry Pi as the wires can be removed at different segmentations. Our device will be powered by a solar panel that charges a battery inside the encasement. To easily read immediate data there will also be LCD screens.

6. Final Design:
	Description:
		Each device will have one Raspberry Pi, three moisture sensors, one waterproof encasement, one LCD screen, three pipes at 45 degree angles, one solar panel, and wiring to connect the electrical components. The moisture sensors will reach depths of one, two, and four feet.

	![Device out of the ground](https://github.com/elfi1585/Water-detection-plans-for-farm-fields/blob/master/Pictures/20141204_181332.jpg)
	
	Manufacturing Process:
		The only parts that needed manufacturing were the critical components, which were the encasements and protection of our electronics. We measured the pipes very carefully before cutting them to the right length and angle, and also drilled holes in the box for the wires to go through and be directly centered over the pipes.

7. Testing & Analysis:
	Critical Components:
		Our critical components are the waterproof encasement and the piping of our device. We chose these to be our critical components because they are what separates our device from other moisture sensors. Other moisture sensors are often used for indoor watering of plants, or just briefly used outside in the garden. Our device will have to withstand weather from being left outside for extended periods of time, and also the flood of water that comes from actually flood irrigating the farm. It will also have to be placed deep underground as opposed to how most moisture sensors simply read the surface moisture of the soil. Our critical components serve the purposes that the waterproof encasement protects the Raspberry Pi and LCD screen from weather and the flood irrigation. Also, the pipes allow the moisture sensors to reach the required depths and also are high enough above the ground that the flood irrigation won't flow into the pipes and disturb the moisture reading.
	Analysis used in Design:
		We designed our pipes to be at 45 degree angles so the moisture sensors collected more accurate data as the water saturated the soil. We also have our pipes reach depths of one, two, and four feet because the roots will be a arround one to two feet deep, but can draw water from around four feet. The wooden stand also left holes from each end for the water to flow under as to not get pushed away by the flow of the water.
		
	User Testing:
		The first test showed that we needed an ADC for our Raspberry Pis to read analog input, and that our moisture sensors needed some calibrating before use. Testing also showed that the moisture was not 100% in pure water. This was because pure distilled water will not conduct any electricity. A moisture sensor works by sending a current through one prong to the other. The sensor then uses that data to make a moisture reading. Thus, since water does not always conduct electricity, we found that pure water will not always give a 100% reading. 
  
8. Conclusion:
	In summation, this project proved to be a difficult one, but one that we learned immensely from. We gained a lot from building this project, such as team dynamics, manufacturing skills, and so on. It was exciting to go from knowing minimal information about the engineering and manufacturing process to suddenly having a finished product to give to a client that we worked for. After much brainstorming, building, coding, and hard work we designed a moisture sensor that met all the criteria given to us by our client. We were happy with the design and thought the we built it to the best of our ability given the time and resources. If given more time, something to add to the product would be a better way to mount the moisture sensors inside the tube. Also, it would be beneficial to have a better way to waterproof the bottom of the tubes. Something else to think about for the future would be to find a more efficient way to dig holes in the ground prior to inserting the tubes. Thus, in conclusion, we have formed the foundation for a moisture sensor for farmers, and we hope that it can be expanded upon and bettered from what we have created.

9. Bill of Materials:
	Total Budget: $375
	20' PVC Piping: $4.31
	Two Raspbery Pis: $79.90
	Two Adafruit Waterproof Encasements: $66.40
	Six Moisture Sensors: $33.36
	Two LCD Screens: $53.98
	Two Solar Charching Batteries: $71.98
	ADCs, wires, and breadboards: $46.64
	Rubber O-rings: Free (made from bicycle tires)
	Total Spent: $356.57
	Ammount Left to Spend: $18.43

10. Timeline:
	

11. Appendix:
	We calculated the lengths to cut the pipes to by using the Pythagorean Theorem:	a2+b2=c2. The moisture level is determined by an analog signals sent from the moisture sensors, that are then converted into digital signals that the Raspberry Pi can read, and a code library that came with the MCP will convert the signal into a percentage that is easy to understand.
