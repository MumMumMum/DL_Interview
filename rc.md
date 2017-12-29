Robocist familarity doc:  
1. Do you have experience with any of the following?  
If so, rate your proficiency (no experience, novice, experienced, expert)?  
Tensor Flow, Keras, OpenCV, OpenML, C, C++, Python, CUDA, ROS, OpenAI.   
    A. On scale of 5 I would rate:  
        . Tensor Flow -3 Used as part of course, still exploring on my own.   
        . Keras - 2 Used as part of course, still exploring on my own. 
        . OpenCV -2 Used as part of course, still exploring on my own. 
        . OpenML-0 Not used.  
        . C-4, C++ - 4, Python - 4:  
        . CUDA - 1, Used it indirectly through tensorflow, But never used CUDA instruction set.  
        . ROS-1,  Used part of course, SDC but still a novice.  
        . OpenAI-0 Never contributed nor used anything from there yet.  

2.Road and Lane detection:  How clear do the markings on the road need to be?  Can it be done without road markings?  
A.The marking on lanes if clear help in lane detection without ambugity.  
If uder shadows and situation like not clear lane makrings are present, preprocessing should be dealt with.  
Yes Lane detection can be marked even for roads that have not lane marking. With marking 
Lane detection should never fail even if road markings are not seen like a situation where road is covered under heavy snow.  


3.Object Detection:  Can you detect any object in the field of view that is moving 
and if it is not recognized, label it as a "Blob'?  What method do you use for object Detection? 
A. Yes we can detect static as well as moving object in frame.
I have used Tensorflow object detection api for the task of traffic light deetction and classification.
used models ssd_mobilenet_v1_coco,rfcn_resnet101_coco,faster_rcnn_resnet101_coco  
Also used HOG parameters for vehicle detection.  


4.Object Recognition:  What method do you use for this?  What objects have you developed recognition models for? 

5.Labeled Object Data Sets: Getting labeled image data to train the model is difficult and/or expensive. 
Where do you get your labeled data sets?  What methods are you aware of to generate your own labeled data?  
Is there a way to automate the process?  Are you aware of any labeling tools - which ones?  
A. I have used LabelImg


6.Perception/Depth:  Our hardware use inertia sensors coupled with either a single camera (monocular) 
or stereo cameras (binocular). We do NOT use LIDAR or RADAR, only vision and inertia. 
Do you have experience using vison (and potentially inertia readings) for depth perception?  
This will be needed to identify potential collision threats.  What method do you use?
A. Sorry I do not the answer for this.

7.Mapping and Localization:  Can you use the camera, inertia sensors and GPS data to generate a 3D map of a driven environment?

8.Trajectory / Path Planning: Do you know how to model a projected vehicle path as well as objects in the field of view?  
For example, if the road is curving, the car will continue around the curve. 
Knowing that, will an object in the field of view be entering the vehicle path? 
If so, when and where and is it a threat?  Do you have any related experience?
A. In SDC there was Lidar and Radar data giving information of vehicle velocity and position. 
Used FSM in behavior modelling and Have understanding of JTMfor path planning.
But in Robocopilot, the vehicle which is detceted and tracked in view there is no LIDAR or RADAR. Hence using the IMU data which will read accelaration and angular velocity, we can decide if the vehicle is about to turn or what and then decide if we should do lane change or not.
This is totally my understanding just trying to fix the zig saw. 


9.Learning from Demonstration (LFD) is where the system can learn from human behavior.  Do you have any related experience? Can design the system to learn from human drivers?
A. I have no experience in this, but there are papers suggesting that this is possible.
   Learning parameters from driving data and modeling driving experience as the features learnt.
   Yes, Indeed possible.

10.What other skills / experience do you feel are important for the development of autonomous 
vehicle technologies that rely on cameras, inertia sensors and GPS?  
A.  Go data extarcation from images, like robust object detection.
    Traffic light detection.
    Detction of distance of objects in images
    SLAM
   
11.How do you feel you could best contribute to our RoboCopilot initiative?   

  Well, My only experience in Autonomous Vehicle is through SDC course. I have learnt few things from general reading here and there. I am trying to make few models for my own understanding. I have the ability to learn and do things. If I get some guidenance from a someone it will be great and some more enriching.Completing the course in SDC gives me a kind of confidence that yes any task seems doable. To work on modules in SDC is still like there is tarining happening and there are lables found. Its more like supervised learning. What remains is testing (my learning )model in unspervised domains. That is where industry experience comes.Hands on I need to do and try many more things.  I had no idea of LDF. I had read about IMU but still I am not sure how it works and how is it interfaced and used in collision detect. I have used simple app like LabelImg for my SDC project, but while answering your questionare realized there are many automated process and tools available. So every step has been a learning intiative. 

  I am in strange situation, In My country there are no much opprtunities in SDC, Computer vision.  
  I would be glad to contibute to any of the modules you would want me to work on be  
  it Computer Vision, Labeling ,Testing any    that would help you achieve your target of March 2018 .

