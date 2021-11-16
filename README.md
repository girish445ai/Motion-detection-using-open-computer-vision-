# Motion-detection-using-open-computer-vision-
This project is about designing a video surveillance system using open cv and various motion detection methods .
![image](https://user-images.githubusercontent.com/63008519/142032854-e203b412-d9c9-4ccd-b2cf-d8b9e6221410.png)
## Introduction:
The demands on video surveillance systems are rapidly increasing in the present day. In the past, security systems had to be monitored by a guard who was locked away in a room all day watching the monitors to make sure that nothing would happen. The other option was to come back and review the footage but damage could have happened.To avoid this we need a robust and cheap system that performs effectively for surveillance.
<br/>
Therefore, new innovative technology revolves around affordability of a product in terms of its cost and ease of implementation. The Raspberry Pi crosses both criteria in that it is a cheap, effective computer which can be interfaced with other modules to realize systems with immense functionality.The various objectives of the system are to detect an intruder, take an image of the intruder and also convey an alert message to the facility owner. In doing so it thus allows for remote monitoring of homes from anywhere in the world.
## Need of Image processing and Background subtraction algorithms:
Analysis of human motion is one of the most recent and popular research topics in digital image processing. In which the movement of human is the important part of human detection and motion analysis, the aim is to detect the motions of human from the background image in a video sequence.
## Objective:
This project will design and implement a security system based on Raspberry Pi microcomputer. The system should be able to detect motion (intruder), activate a camera to take frames of video after motion is sensed and then send an alert to the facility owner through electronic mail plus an image attachment. 
### Prerequisites:
Raspberry pi with installed Open Cv libraries and Packages and a camera module.
### Motion Detection Algorithm :
Motion detection, which is the fundamental step in video surveillance, aims to detect regions corresponding to moving objects. The resultant information often forms the basis for higher-level operations that require well-segmented results, such as object classification and action or activity recognition. However, motion detection suffers from problems caused by source noise, complex backgrounds, variations in scene illumination, and the shadows of static and moving objects. Various methods have been proposed to overcome these problems by retaining only the moving object of interest. These methods are classified into three major categories:
<br/>
• background subtraction
<br/>
• temporal differencing
<br/>
• optical flow
<br/>
Temporal differencing is highly adaptive to dynamic environments; however, it generally exhibits poor performance in extracting all relevant feature pixels. Therefore, techniques such as morphological operations and hole filling are applied to effectively extract the shape of a moving object.
This includes Frame differencing and Three frame differencing.
<br/>
Background subtraction provides the most complete feature data, but is extremely sensitive to dynamic scene changes due to lighting and extraneous events. Several background modelling methods have been proposed to overcome these problems.
This includes methods like Background estimation,Adaptive Background subtraction,
Gaussian Mixture Model, Running Gaussian average etc.

