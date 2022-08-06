# Wall_Collision_Avoidance_In_Turtlesim
This is a basic Turtlesim ROS package coded in both c++ and python to avoid the collision of turtle bot from the walls in turtlesim 

### Instruction 

1. Clone this github repositiory into your ros workspace/src folder (eg - catkin_ws/src/automate_turtlesim)
   
   ```console
   git clone https://github.com/Robo-Dude/Wall_collision_avoidance_in_turtlesim.git
   ```   
   
2. Go back to catkin_ws folder open the terminal run catkin_make for building code in a catkin workspace.
 
   ```console
   catkin_make
   ```
   
3. Now Open three terminals and run:

   for C++ Nodes on terminal
   
   3.1 Terminal 1
   
     ```console
     roscore
     ```
     
   3.2 Terminal 2
    
      ```console
      rosrun turtlesim turtlesim_node 
      ```
      
   3.3 Terminal 3   
      
      ```console
      rosrun automate_turtlesim collision
      ```
      
   --------------------------------------------------------
   
    for Python Nodes on terminal
    
    Note - Don't forget to give executable permission to python nodes files
    
    ```console
    chmod +x filename.py
    ```
   
   3.1 Terminal 1
   
     ```console
     roscore
     ```
     
   3.2 Terminal 2
    
      ```console
      rosrun turtlesim turtlesim_node 
      ```
      
   3.3 Terminal 3   
      
      ```console
      rosrun automate_turtlesim collision.py
      ```
      
      
 Video - 
 
 [turtle_wall_colision_avoidance.webm](https://user-images.githubusercontent.com/65345575/183122066-a3591aac-f605-46e0-aa35-451294140aae.webm)

      
      
   
   
   

   

   
