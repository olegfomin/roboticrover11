# roboticrover11
This project contains all the parts that are needed to run a universal chassis that is currently heavily leaned towards lawn tennis. The four wheeled base may serve to the three important tasks that are used for:
* simulating the tennis opponents. In this case a cannon ball should be mounted on top of the robot
* collecting the balls that may be scattered all around the court after a practice game/exercise   
* cleaning the playing courts with a vacuum cleaner

# The project parts
* The WEB Java-Script interface where you can correct or take the control over completelly. This part called '''UI'''
* The server part that is running the AI and it can predict the place where the ball touches the ground, and thus it can send the robotic rover to the place where it is most convenient to catch the opponent ball and then send the other ball back. This part is called '''server'''
* And eventually the part that moves across a court and execute all the commands sent by server. The '''robotic rover''' is also equipped with the web-cam and microphone that maybe sent to the server for the analisys
