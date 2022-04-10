
1.  To create a system that is a set of monitoring systems such as a webcam keeps track of the actions like face movements, object detection etc. of the candidate along with the system usage analysis.
2.  All these features are fed into a rule based system created which detects the occurrences of malicious activities that can happen. Thus it makes a decision on users’ actions.
3.  The main input modules includes the system compatibility check, video input processing, system analysis :
	-   **System compatibility check**: Checking the latest browser version, internet speed, webcam availability etc.
    
	-   **Video input processing**: AI based cheating detection system that includes all the recognition modules face, object detection like whether the face is within the boundary and visible throughout the examination, detection of multiple faces, cell phone, book detection etc.
    
	-   **System usage analysis**: Detecting various browser and system related usage like exiting full screen mode, opening multiple tabs, minimizing the window, alt key press etc.
	
The output will be the warning which will be displayed on the screen which will be considered as malicious practice. Hence, all the techniques mentioned above help the students to give their exams honestly as well as help the teachers to solve the issue of holding online examinations in a supervised manner.


**Architecture**

![](images/architecture.png)

**Workflow**

![](images/workflow.png)

**FEATURES**

***Student Side***

- Secure Login using Google Credentials API
- System Check
	- Operating System Check
	- Browser Check
	- Internet Speed Check
	- Webcam Check
- User  Validation through Image Capture
- Face Detection
- Multiple- Face Detection
- Cell Phone Detection
- Shortcut Keypress Detection
- Full Screen Compulsion
- Full Screen Escaping Detection
- Tab Change Detection
- Camera Blocking Detection
- Head-Pose Detection

***Admin Side***
- Restricted Access
- Assign Unique Customizable Exam Code
- Assign Any Google/Microsoft Form
- Assign Customized Time Duration
- Individual Exam Results
- Comprehensive Results
	- Name
	- Email ID
	- Cheat Scores
		- Key Press Detections
		- Face Detection
		- Full Screen Triggers
		- Tab Change Detections
		- Examinee's Photo 
		
**References**
 - https://github.com/AgnellusX1/GodsEye
 - https://github.com/tusharnankani/Aankh
 - https://github.com/vardanagarwal/Proctoring-AI
 - https://github.com/justadudewhohacks/face-api.js/
