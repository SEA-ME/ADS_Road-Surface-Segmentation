# ADS Project - Road Surface Segmentation using PiRacer
## Watch out for the bumpy road!   
</br>


# Index
#### [Introduction](#introduction-1)
#### [Background Information](#background-information-1)
#### [Project Goals & Objectives](#project-goals--objectives-1)
#### [Technical Requirements](#technical-requirements-1)
#### [System Architecture](#system-architecture-1)
#### [Software Design](#software-design-1)
#### [Implementation](#implementation-1)
#### [Project Timeline](#project-timeline-1)
#### [Collaboration and Teamwork](#collaboration-and-teamwork-1)
#### [Mentorship and Support](#mentorship-and-support-1)
#### [Reflection and Self-Assessment](#reflection-and-self-assessment-1)
#### [Submission](#submission-1)
#### [References](#references-1)
</br>


# Introduction

Road Surface Segmentation is a crucial task in the development of autonomous vehicles. Accurate road surface segmentation is essential for maintaining the stability and safety of self-driving vehicles by providing a clear understanding of the available driving space in real-time. In this peer-peer educational project, participants will develop an algorithm for road surface segmentation using the Piracer platform.

The objective of this project is to create an algorithm that can accurately segment the road surface in real-time video streams captured from a moving vehicle. The algorithm will be evaluated based on its ability to segment the road surface in various lighting and weather conditions, its computational efficiency, and its accuracy in the presence of complex objects, such as trees, buildings, and other vehicles.

Participants will use a combination of computer vision techniques and deep learning to develop their solution. They can use open-source tools and libraries, such as OpenCV, TensorFlow, and PyTorch, to implement their algorithm. The project will provide participants with hands-on experience in developing real-world computer vision applications, and it will help them build their skills in image processing, deep learning, and software development.

Upon completion of the project, participants will submit their solution as a GitHub repository that includes the source code, documentation, and sample results. They will also provide a video demonstrating their solution in action. This project provides an exciting and practical learning experience for students interested in computer vision and autonomous vehicles, and it will help prepare them for careers in these exciting and rapidly growing fields.  
</br>


# Background Information

The development of autonomous vehicles has been one of the most significant technological advancements of the 21st century. Over the past few decades, significant progress has been made in the fields of computer vision, robotics, and machine learning, making it possible to develop autonomous vehicles that can drive safely and efficiently without human intervention.

One of the key challenges in developing autonomous vehicles is the ability to accurately perceive and understand the environment in real-time. This requires the ability to detect and classify objects in the environment, such as road markings, other vehicles, and pedestrians, as well as to determine the road surface and free space available for driving.

Road Surface Segmentation is a crucial aspect of this perception development. Accurate road surface segmentation is essential for ensuring the stability and safety of autonomous vehicles, as it provides the vehicle with a clear understanding of the available driving space and the boundaries of the road.

The earliest approaches to road surface segmentation were based on traditional computer vision techniques, such as edge detection and thresholding. In recent years, however, there has been a growing interest in using deep learning-based approaches to road surface segmentation. These methods have been shown to provide improved accuracy and robustness in challenging conditions, such as low light and adverse weather.

The use of the Piracer platform in this project provides an exciting opportunity for participants to develop their own road surface segmentation solution and to contribute to the development of autonomous vehicles. This project is a great opportunity for students and professionals interested in computer vision, robotics, and machine learning to gain hands-on experience in developing real-world computer vision applications.  
</br>


# Project Goals & Objectives

The goals and objectives of the Road Surface Segmentation using Piracer peer-peer educational project are as follows:

1. To develop an algorithm that can accurately segment the road surface in real-time video streams captured from a moving vehicle.
2. To evaluate the performance of the algorithm in various lighting and weather conditions and its ability to accurately segment the road surface in the presence of complex objects, such as trees, buildings, and other vehicles.
3. To develop an efficient algorithm that can run in real-time on the Piracer platform.
4. To provide participants with hands-on experience in developing real-world computer vision applications and building their skills in image processing, deep learning, and software development.
5. To enable participants to contribute to the development of autonomous vehicles and to be part of a community of experts in the field.
6. To provide a platform for participants to share their solutions and learn from each other's experiences.
7. To foster collaboration and teamwork among participants and to provide an opportunity for students and professionals to network and develop their professional skills.

The end result of this project will be a GitHub repository that includes the source code, documentation, and sample results of the road surface segmentation algorithm. Participants will also provide a video demonstrating their solution in action, showcasing the accuracy and robustness of their algorithm in a real-world scenario.  
</br>


# Technical Requirements

The technical requirements for the Road Surface Segmentation using Piracer peer-peer educational project are as follows:

1. Hardware: Participants will need access to a Piracer vehicle equipped with an onboard camera. The camera should have a resolution of at least 720p, and it should be able to provide a video stream at a frame rate of at least 30 frames per second.
2. Software: Participants will need to use a programming language such as Python or C++, along with libraries such as OpenCV, TensorFlow, or PyTorch, to implement the road surface segmentation algorithm. The development environment should also include tools for image processing, such as image editing software, image compression software, and image analysis software.
3. Algorithm Requirements: Participants will need to implement an algorithm that is capable of accurately and efficiently segmenting the road surface from the background. The algorithm should be able to handle various road conditions, including roads with different colors and textures, roads with obstacles, and roads with curves and slopes.
4. Performance Requirements: Participants should aim to achieve real-time performance, with a focus on minimizing latency and maximizing accuracy. The road surface segmentation algorithm should be able to process video streams in real-time, with a latency of less than 200 milliseconds. The accuracy of the algorithm should be evaluated using metrics such as the Intersection over Union (IoU) and the precision, recall, and F1 score.
5. Documentation Requirements: Participants should provide well-documented code, along with a detailed project report that includes a description of the solution, the results of testing and validation efforts, and any future directions or improvements they would like to see in the project. The report should also include a discussion of the technical challenges faced during the project, along with the solutions that were implemented to address these challenges.
6. Source Code Requirements: Participants should provide the source code for the road surface segmentation algorithm, along with sample input data and sample results. The source code should be well-structured, easy to understand, and well-commented, with clear and concise documentation. The source code should also be compatible with the development environment and should be suitable for use in future projects or real-world applications.

By meeting these technical requirements, participants will be able to develop a robust and scalable road surface segmentation algorithm that is capable of processing video streams from the Piracer vehicle and accurately segmenting the road surface in real-time.  
</br>


# System Architecture

The system architecture of the Road Surface Segmentation using Piracer peer-peer educational project can be divided into three main components:

1. Image Acquisition: The first component of the system is the image acquisition module. This module captures video streams from the onboard camera of the Piracer vehicle. The video streams are then processed and passed to the next component of the system.
2. Image Processing: The image processing module is responsible for pre-processing the video streams and preparing the data for road surface segmentation. This may involve operations such as image resizing, color space conversion, and noise reduction.
3. Road Surface Segmentation: The road surface segmentation module is the core of the system. It takes the processed image data as input and uses an algorithm to segment the road surface and produce a binary mask indicating the road surface and the non-road surface pixels.

The road surface segmentation algorithm can be based on traditional computer vision techniques or on deep learning approaches. Participants are free to choose the approach that they prefer, as long as it meets the performance requirements and runs efficiently on the Piracer platform.

Once the road surface has been segmented, the resulting binary mask can be used to extract relevant information about the road surface and driving space, such as the road boundaries, the width of the driving lane, and the presence of obstacles. This information can then be used by the autonomous driving system to make decisions about how to navigate the road safely and efficiently.

The system architecture is designed to be flexible and scalable, allowing participants to build upon the existing components or to develop their own solutions from scratch. The goal is to provide participants with a platform for creativity and innovation and to encourage them to push the boundaries of what is possible with road surface segmentation.  
</br>


# Software Design

The software design of the Road Surface Segmentation using Piracer peer-peer educational project is centered around the following key elements:

1. Image Acquisition: The image acquisition module is responsible for capturing video streams from the onboard camera of the Piracer vehicle. The video streams are stored in a buffer and passed to the next component of the system for processing.
2. Image Pre-processing: The image pre-processing module is responsible for preparing the video streams for road surface segmentation. This may involve operations such as image resizing, color space conversion, and noise reduction. The pre-processed data is then passed to the road surface segmentation module.
3. Road Surface Segmentation: The road surface segmentation module is responsible for the core functionality of the system. It takes the pre-processed data as input and uses an algorithm to segment the road surface and produce a binary mask indicating the road surface and the non-road surface pixels.
4. Output: The output module is responsible for visualizing the results of the road surface segmentation. This may involve overlaying the binary mask on the original video stream to show the segmented road surface, or it may involve displaying relevant information about the road surface and driving space, such as the road boundaries, the width of the driving lane, and the presence of obstacles.

The software design is modular, allowing participants to replace or enhance individual components as needed. This allows for flexibility and scalability, enabling participants to build upon the existing components or to develop their own solutions from scratch. The goal is to provide participants with a platform for creativity and innovation and to encourage them to push the boundaries of what is possible with road surface segmentation.

The software design should be implemented in a high-level programming language such as Python or C++ and should be compatible with the PiRacer platform. The source code should be well-documented and easy to understand, allowing other participants to build upon the existing components or to use the code as a starting point for their own solutions. The end result of this project will be a GitHub repository that includes the source code, documentation, and sample results of the road surface segmentation algorithm.  
</br>


# Implementation

The implementation of the Road Surface Segmentation using PiRacer project involves several steps:

1. Data Collection: Participants will need to collect a dataset of video footage from the PiRacer vehicle, as it travels on different roads. The dataset should include a variety of road conditions, including roads with different colors, textures, slopes, and curves. Participants should also collect corresponding ground truth data, which will be used to evaluate the accuracy of the road surface segmentation algorithm.
2. Algorithm Design: Participants will need to design an algorithm that is capable of accurately segmenting the road surface from the background. The algorithm should be able to handle the various road conditions present in the dataset. Participants should consider various image processing techniques, such as color-based segmentation, edge detection, and object recognition, when designing the algorithm.
3. Algorithm Implementation: Participants will need to implement the algorithm in a programming language such as Python or C++, using libraries such as OpenCV, TensorFlow, or PyTorch. The implementation should be optimized for real-time performance, with a focus on minimizing latency and maximizing accuracy.
4. Testing and Validation: Participants will need to test the road surface segmentation algorithm on the collected dataset. They should evaluate the accuracy of the algorithm using metrics such as the Intersection over Union (IoU) and the precision, recall, and F1 score. Participants should also perform a thorough evaluation of the algorithm's performance, including tests for robustness and scalability, to ensure that it is capable of handling a wide range of road conditions.
5. Deployment: Participants will need to deploy the road surface segmentation algorithm on the PiRacer vehicle, and test it in real-world conditions. They should evaluate the algorithm's performance in terms of accuracy, latency, and robustness, and make any necessary modifications to improve its performance.
6. Documentation and Submission: Participants should provide well-documented code, along with a detailed project report that includes a description of the solution, the results of testing and validation efforts, and any future directions or improvements they would like to see in the project. The report should also include a discussion of the technical challenges faced during the project, along with the solutions that were implemented to address these challenges. The source code and project report should be submitted to the peer-peer educational platform for evaluation.

By following these steps, participants will be able to develop a robust and scalable road surface segmentation algorithm that is capable of processing video streams from the PiRacer vehicle and accurately segmenting the road surface in real-time.  
</br>


# Project Timeline

Here is a sample project timeline for the Road Surface Segmentation using PiRacer project:

1. Week 1: Introduction to the project, review of background material, and dataset collection. Participants should begin collecting the video footage and ground truth data required for the project.
2. Week 2-4: Algorithm design and implementation. Participants should use this time to design their road surface segmentation algorithms and begin implementing them in a programming language such as Python or C++.
3. Week 5-6: Testing and validation. Participants should use this time to test their algorithms on the collected dataset, evaluating the accuracy and performance of the algorithms.
4. Week 7-8: Deployment and real-world testing. Participants should use this time to deploy their algorithms on the PiRacer vehicle and test them in real-world conditions.
5. Week 9-10: Final preparations and submission. Participants should use this time to finalize their project reports, document their code, and prepare their submissions. The final project submissions are due at the end of week 10.

This timeline is just a sample, and the exact timeline may vary depending on the needs and requirements of the participants. Participants should be prepared to be flexible and adjust the timeline as needed, based on their progress and the specific requirements of their projects.  
</br>


# Collaboration and Teamwork

Students will be working in teams of maximum six to complete this project. Each team member will be assigned specific tasks and responsibilities, and will be expected to contribute to the overall success of the project. Teams will be required to submit regular progress reports and to meet with the instructor for check-ins and feedback.  
</br>


# Mentorship and Support

Students will be provided with mentorship and support from the instructor throughout the project. The instructor will be available for questions and guidance, and will hold regular check-ins and progress reports to provide feedback and support.  
</br>


# Reflection and Self-Assessment

Students will be encouraged to reflect on their own learning and progress throughout the project. This will be done through self-assessment exercises and through feedback from the instructor and other team members.  
</br>


# Submission

For the Road Surface Segmentation using PiRacer project, participants are expected to submit their project on GitHub. The final submission should include the following components:

1. Code: The participants should upload the source code of their road surface segmentation algorithm on GitHub. The code should be well-documented, readable, and well-organized.
2. Project report: Participants should submit a comprehensive project report that describes their approach, results, and conclusions. The report should also include a discussion of the challenges faced during the project and how they were addressed.
3. Datasets: Participants should also upload the dataset used for training and testing the algorithm on GitHub. The datasets should be well-documented and include the ground truth data.
4. Presentation: Participants should also submit a slide deck or video presentation that summarizes their project and results. The presentation should be accessible and understandable to a non-technical audience.

The final submission should be well-organized, complete, and clearly demonstrate the participants' mastery of the subject matter. The participants should be prepared to present their projects and defend their results during the final review and evaluation.  
</br>


# References

Here are some open source references and descriptions that could be used in the Road Surface Segmentation using PiRacer project:

1. OpenCV: OpenCV is a popular open-source computer vision library that provides a wide range of tools and algorithms for image and video processing. Participants could use OpenCV for pre-processing the video footage, extracting features, and implementing the road surface segmentation algorithm.
    Link: [https://opencv.org/](https://opencv.org/)

2. TensorFlow: TensorFlow is an open-source machine learning framework that provides a wide range of tools for training deep neural networks. Participants could use TensorFlow for training a deep neural network for road surface segmentation.
    Link: https://www.tensorflow.org/

3. ROS (Robot Operating System): ROS is an open-source software framework for robotics that provides a wide range of tools and libraries for building robotic systems. Participants could use ROS for integrating the road surface segmentation algorithm into the PiRacer vehicle and for testing and validating the algorithm in real-world conditions.
    Link: https://www.ros.org/

4. Udacity Self-Driving Car Simulator: Udacity provides a self-driving car simulator that can be used for testing and validating autonomous driving algorithms. Participants could use the simulator to test and validate their road surface segmentation algorithms.
    Link: https://github.com/udacity/self-driving-car-sim


These references are just examples and participants are encouraged to explore other open-source tools and resources that may be more suitable for their specific needs and requirements. Participants should be prepared to research and evaluate different open-source tools and resources, and to make informed decisions about which tools and resources to use for their projects.




Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
