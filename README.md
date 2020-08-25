<!-- Since GitHub Pages adds title and description from the _config.yml
## Girish Patil
[http://gmpatil.github.io](http://gmpatil.github.io) 
-->

Java - Java EE - Node.js - Python - Agile/Scrum Development


### Open Source and GitHub Projects
2020:
* [Cloud Developer Nanodegree Projects](https://github.com/gmpatil/cloud-dev-nd-monolith2microsvcs): Projects done as part of Udacity's [Cloud Developer Nanodegree](https://confirm.udacity.com/4P7DRVDQ), mainly using TypeScript, Node.js, Docker, Kubernetese, and Serverless framework. Used Travis CI/CD to trigger build for GitHub repository changes and publish built docker images directly to Docker Hub and then deploy to AWS EKS cluster.
    - [Monolith to Microservices](https://github.com/gmpatil/cloud-dev-nd-monolith2microsvcs) Refactored monolith web app into front-end and two back-end REST API based microservices. Travis CI/CD build is triggered on Github changes, docker images are built for all microservices and published to DockerHub, and images are deployed to AWS EKS cluster.  
    - [Todo List - Serverless App](https://github.com/gmpatil/cloud-dev-nd-serverless) Todo App back-end entirely built using Node.js Lambda functions and [Serverless framework](https://www.serverless.com/). Dynamodb, and S3 Buckets are used in this project.
    - [U Cart - Serverless App](https://github.com/gmpatil/cloud-dev-u-cart) Online multi-tenent Stores back-end REST services implemented using Node.js Lambda functions and Serverless framework. Auth0 is used Authenticate and manage user's Roles. 

* [Data Streaming Nanodegree Projects](https://github.com/gmpatil/DataStreamingND/): Projects done as part of Udacity's [Data Streaming Nanodegree](https://confirm.udacity.com/RPGH6956), mainly using Apache Kafka, and Apache Spark.
    - [Optimizing Public Transport](https://github.com/gmpatil/DataStreamingND/tree/master/Optimizing%20Public%20Transportation): Update in real-time status of metro trains across lines along with upto date passenger entry count at each station stops/turnstiles. APIs,components used are Kafka REST-Proxy for sendng weather updates, Kafka Connect to get lines and stations details, Faust and KSQL for Stream processing.
    - [Sanfransisco Crime Statistics](https://github.com/gmpatil/DataStreamingND/tree/master/SF%20Crime%20Statistics): Get crime report data stream from Kafka Topic and gather real-time crime stats with Apache Sparck SQL using Windowing and Watermark query features.

2018:
* [Self Driving Car Engineer Nanodegree Projects](https://github.com/gmpatil/sdcnd/): Projects done as part of Udacity's [Self Driving Car Engineer Nanodegree](https://confirm.udacity.com/PZWHTMAX), mainly using Python, Jupyter Notebook, Tensorflow, C++, and RoS.
    - [Finding Lane Lines on the Road](https://github.com/gmpatil/sdcnd/blob/master/term1/p01_laneLines/P1.ipynb): Detects lane lines in a image of a road. Python CV (Computer Vision), NumPy and Matplot libraries are used. Hough Lines and Canny Edge detection alogorithms (cv2 functions) are used.
    - [Traffic Sign Recognition Classifier](https://github.com/gmpatil/sdcnd/blob/master/term1/p02_trafficSign/Traffic_Sign_Classifier.ipynb): Train Deep Neural Network to detect traffic signs. LeNet model is used as base. Implemented using Tensorflow.
    - [Behavior Cloning](https://github.com/gmpatil/sdcnd/tree/master/term1/p03_behavioralCloning): Build and train convolution neural network (CNN) using good driving behavior data collected from the simulator, so that model drives the car around the track in the simulator. NVIDIA's CNN model is used as base and implemented using Keras APIs on top of Tensorflow.
    - [Advanced Lane Finding](https://github.com/gmpatil/sdcnd/tree/master/term1/p04_advLaneFinding): Computes camera calibration matrix and distortion coefficients, and applies distortion correction to raw images. Applies perspective transform to rectify binary image ("birds-eye view"). Detects lane pixels and find the lane boundary. Implemented usinf Python CV library.
    - [Vehice Detection](https://github.com/gmpatil/sdcnd/blob/master/term1/p05_vehicleDetection/writeup_report.md): HOG feature extraction and training of Linear SVM classifier model to detect vehicles. Implemented using SKLearn Python library.
    - [Extended Kalman Filter](https://github.com/gmpatil/sdcnd/tree/master/term2/p06_ekf):  Extended Kalman Filter is used to estimate the state of a moving object of interest with noisy lidar and radar measurements.
    - [Unscented Kalman Filter](https://github.com/gmpatil/sdcnd/tree/master/term2/p07_ukf): Unscented Kalman Filter is used to estimate the state of a moving object of interest with noisy lidar and radar measurements. 
    - [Particle Filter/Kidnapped Vehicle](https://github.com/gmpatil/sdcnd/tree/master/term2/p08_kv): Implements a 2 dimensional particle filter in C++ to predict location on the robot or Kidnapped Vehicle given initial location GPS estimation, noisy sensor and control data.
    - [Proportional Integral Derivative (PID) Controller](https://github.com/gmpatil/sdcnd/blob/master/term2/p09_pid/README_PIDC.md): Implement PID controller in C++ to drive vehicle around the track in the Unity simulator environment.
    - [Model Predictive Control (MPC) Controller](https://github.com/gmpatil/sdcnd/tree/master/term2/p10_mpc): Implement MPC controller in C++ to drive vehicle around the track in the Unity simulator environment.
    - [Path Planning](https://github.com/gmpatil/sdcnd/tree/master/term3/p11_pp): Safely navigate around a virtual highway with other traffic that is driving +/-10 MPH of the 50 MPH speed limit by changing lanes as appropriate without collision and jerks. Implemented in C++.
    - [Semantic Segmentation](https://github.com/gmpatil/sdcnd/tree/master/term3/p12_ss): Label the pixels of a road in images using a Fully Convolutional Network (FCN).
    - [Programming a Real Self-Driving Car (RoS)](https://github.com/gmpatil/sdcnd/tree/master/term3/p13_capstone): Program self-driving car to drive around provided track in Unity simulator as well make Carla, Udacity's self-driving car drive on real test track.

2006-2010:
* Open ESB Components: The open-esb.java.net and wiki.open-esb.java.net sites are no longer maintained after Sun Microsystems' acquisition by Oracle. Below I have provided links to the forks maintained by other companies I have come across.  [Open ESB](https://en.wikipedia.org/wiki/OpenESB) is Java based JBI (Java Business Integration, JSR 208/312) compliant enterprise application integration platform.
    - POJO SE: A Service Engine component, which allows messages to be processed using Java language.
     [Code, ](https://bitbucket.org/openesb/openesb-components/src/b3db40087362/ojc-core/pojose/) [Doc, ](https://docs.oracle.com/cd/E21454_01/html/821-2618/pojoservengug_intro.html#scrolltoc)[Wiki.](http://www.logicoy.com/wikilogicoy/Wiki.jsp@page=POJOServiceEngineUserGuide.html)
    - JAXB Wizard: A Netbeans module to help in importing XSD schema into Netbeans Projects, generating, compiling JAXB classes. And also short cuts to generate template code marshall and unmarshall JAXB objects. This module is part of Netbeans Java and Java EE bundle supporting Java SE, WAR and EAR project types. 
    [Doc, ](https://docs.oracle.com/cd/E19509-01/821-0451/jbidevpallette_intro/index.html) [Wiki.](http://wiki.netbeans.org/JAXBWizard) [Demo](https://www.youtube.com/watch?v=FGJ1bMH1f8A) by other contributor.