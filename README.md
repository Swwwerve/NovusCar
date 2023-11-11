## DATASETS FOR AI
https://www.kaggle.com/datasets/sshikamaru/car-object-detection/
https://www.kaggle.com/datasets/daggysheep/find-a-car-park/

## CODE ON KAGGLE FOR AI
https://www.kaggle.com/code/andrewchen2804/yolo-time

#Autonomous Car Report ‘NOVUS’
##Our Solution to the Problem: 
	Fascinating as self-driving cars may be, creating complex systems working in unison to provide users with a safe yet comfortable driving experience is a difficult challenge. Therefore, our team has created the ‘NOVUS’ car that depicts how an autonomous car would function through the integration of simulation and code.
 
##Detection Systems:
	Being able to detect other vehicles and pedestrians while driving is possibly the single most important function of an autonomous vehicle. The NOVUS car is able to detect other vehicles and traffic lights through a YOLO one pass detection algorithm using machine learning. YOLO divides an image into a set of grids and the center of the object becomes its detection point. With data of how wide and tall the object is along with the location of its center, YOLO trains a convolutional neural network to detect that item. **Testing of the model requires the user to input an image in the ‘test set’ directory. **May be some error in ‘re-showing’ the image with the detected vehicles. In order to see this visually, a simulation using Pygame was created to both detect incoming cars and pedestrians, detect which side they were on, and subsequently turn the car in the opposite direction to avoid collision. 

##Communications System:
	Typically, texting/calling while driving poses a great safety hazard as your focus deviates from the road in front of you. Therefore, one of the most paramount systems required in an autonomous car is a communications system that allows the user to send/receive texts and calls in an automated fashion. In our system, once a user enters ‘t’ to trigger a ‘text’ event on the keyboard, the program automatically reads the text message and asks if you want to respond or not. Depending on whether you say yes or no out loud (using Speech Recognition and Regex module in python), the program will allow you to send or not send a message of your choice. Similarly, for calls, the user can click ‘c’ on the keyboard to trigger a call event, and a call will occur prompting the user to say ‘yes’ or ‘no’ to respond to the call or hang up respectively. If the user says ‘yes’, their input to the call will be saved as a .wav file. **Ensure while testing this method, a decent quality mic (at least earbuds) are used to ensure the audio is clear to the system.
 
##Parking System:
	Finally, the last essential feature that the NOVUS car takes account of is parking and where it is safe to do so. Using a Pygame simulation, a set-size parking lot is generated with parking spots (denoted by two thin white rectangles), and randomly generated car objects (denoted as red rectangles within the parking lots). Once the car enters the parking lot, …. FINISH

##Future Improvements:
	As difficult and as much of a time crunch as this project was, it was certainly an interesting one that proved to be fruitful. However, there are certainly some modifications and additions that could be made to improve upon the NOVUS car. Firstly, integrating all of these systems into a single program file would allow for a more seamless user experience. Next, for the calling feature for the communications system, an additional option could be implemented to hang up the call once the user was done. As a last addition, we would factor in weather (e.g. rain, sunny, snowy conditions) and other road conditions (e.g. rough or muddy roads) to change the speed of our car. 

