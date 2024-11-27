# CREATED USING TENSOR FLOW 

# SETUP 
 1.) Download Repo 
 
 2.) Cd into project directory

 3.) Start the server:  npx http-server  


This project is using the TensorFlow MoveNet model to detect human poses combined with the COCO SSD model to detect objects. 
When a person is detected, movenet shows the data points of the person detected while other object detection remains unchanged. 

The index page identifies humans (colin) and bottles. This is a simple sample skelton to demonstrate how to train your own model and use it in a real-world application. It was trained using Teachable Machine.

https://teachablemachine.withgoogle.com/

To navigate to other pages, simply put the file name at the end; i.e. http://localhost:8080/movenetcoco.html

