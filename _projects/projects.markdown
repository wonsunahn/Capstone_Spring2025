---
layout: page
permalink: /projects/
title: Capstone Projects
---

# Capstone Project List
Below is a list of the projects for the Spring 2025 semester. 

# Industry Capstone Projects

## Wolfe
### Integrating Generative AI Into the Software Development Life Cycle
Integrating Generative AI into the Software Development Lifecycle (SDLC) enhances efficiency and accuracy and by consolidating data from all SDLC stages into a knowledge graph. Team to provide context for AI models using existing Wolfe tools (Jira, Confluence, etc.) and insightful analytics to identify anomalies and ensure optimal utilization of AI in the knowledge graph.

**Leverage AI for Maintenance and Support Assistance**
- Ticket / Issue Summarization
- Real-Time Ticket Resolution Assistance
- Real-Time Code Fix Suggestions
- Issue -> Requirement -> Code Traceability

**Impact**: 30%+ increase in productivity

**Major Services**: AWS, Jira/Confluence, GitHub/Bitbucket, Graph Database, Terraform, AI (hosted)

Team Size: 3-4 students

### Application Monitoring Dashboard
Create a standard application monitoring dashboard solution that can be created automatically to visualize, monitor, and alert key functional for an eCommerce system. Leverage cloud technologies, 3rd party integration, and infrastructure-as-code tooling to make a flexible, customizable, re-useable monitoring and alerting framework. 

**Impact**: 25%+ increase in monitoring efficiency; automated default dashboard

**Major Services**: AWS, Terraform, Datadog, BGC site

Team Size: 3-4 students

### Anomaly Detection System for Gift Card Package Weights
**Objective**: Develop a system to detect anomalies and errors in package weights by comparing actual scale-reported weights with projected weights based on expected package contents. The goal is to enhance quality control and identify discrepancies in real time during production.

**Scope**:
- Analyze production and packaging data to calculate expected package weights based on gift card types, affixed items, and packaging materials.
- Integrate scale-reported weights into the system for comparison.
- Design and implement software that allows input of expected weight parameters and flags anomalies in real-time.
- Connect the solution to Wolfe Companies’ production systems for automated data exchange and real-time detection.
- Understand the different combinations of packaging and order types to accurately predict the weight of a given package.
- Be hands on with the packaging to arrive at the correct values for expected weights.
- Deliver a service-oriented architecture proposal for the anomaly detection system.

**Impact**:
This project will help Wolfe Companies improve operational efficiency and reduce errors in gift card packaging, ensuring higher accuracy in shipments and minimizing potential losses. It aligns with the company’s focus on precision in production and quality assurance.

**Collaboration Details**:
Wolfe Companies will provide access to production and packaging data, as well as guidance on industry-specific requirements. The project is expected to last one semester, with interdisciplinary teams in software engineering, data analysis, and systems integration preferred.

**Additional Information**:
Wolfe Companies operates a gift card printing facility where cards are packaged in various formats:
- Cards can be affixed to trifold paper sheets or greeting cards.
- Some cards include stickered labels.
- Packaged cards are often shipped in bulk, with some being enclosed in envelopes and others shipped without.
- Bulk shipments are weighed by FedEx upon pickup, and this weight is used to validate packaging accuracy.

Understanding these variables will be critical to building a system that accounts for different carrier types, packaging materials, and bulk shipment methods to ensure accurate anomaly detection.

Team Size: 3-4 students


### eCommerce Machine-Learning Fraud Tool  
  
Developing a Machine Learning-Based Fraud Detection Tool for E-Commerce Transactions  
  
  
**Objective**: The primary objective of this project is to design and implement a scalable, accurate, and efficient fraud detection tool tailored for e-commerce platforms, specifically for the gift card industry. The tool should leverage machine learning algorithms and real-time data analysis to identify potentially fraudulent transactions while minimizing false positives, ensuring enhanced security and a seamless user experience.  
  
**Project Scope**:   
- Analyze historical e-commerce transaction data to identify fraud patterns.  
- Build a predictive model to classify transactions as fraudulent or legitimate.  
- Ensure the solution integrates seamlessly into existing workflows and scales with transaction volume.  
- Incorporate mechanisms for continuous learning and adaptation to new fraud tactics.  
  
**Expected Outcomes**:  
- A fully functional fraud detection tool capable of identifying fraudulent transactions with an accuracy of over 95%.  
- Reduction in chargebacks to less than 50 bps.  
- Reduction in fraud rate to less than 50 bps.  
- Reduction in false positive rate.  
- Enhanced customer trust through minimized disruptions caused by false positives.  
- Take into consideration the following fraud data points:  
- Average time to detect fraud  
- Decline rate  
- Repeat offender rate  
- Transaction velocity  
- Conversion rate impact  
  
**Key Deliverables**:  
- A trained and validated fraud detection model.  
- API-based tool for integration with e-commerce platforms.  
- Detailed project documentation, including data insights, model architecture, and implementation guidelines.  
- Monitoring dashboard for real-time fraud analytics.  

Team Size: 3-4 students

## CGI 
**Will require signing an NDA/IP release**

### CGI Web Application
CGI members work on different projects for clients. As a project approaches conclusion there is a period where members are seeking their next project. Currently, members who are seeking their next project receive via emails and gain access to an Excel spreadsheet that is updated daily with project opportunities. This excel contains numerous columns (26) on all the details of the opening. The member then sorts through the positions to find something that fits their qualifications and desires. Members then send an email to the Workforce Manager of a list of openings they are interested in with some of the necessary data to apply for the opening, along with some other documents with required information about the member. The Workforce Manager relays this information to the hiring managers of that opening to onboard the member. During this entire process, CGI members have a Member Manager who can also assist members with finding and applying to open positions. 

The goal of this project is to develop a web application to streamline this process. The application will contain the data from the Excel spreadsheet that members can see and look for openings that match their role and qualifications. Members can apply for the role directly from the web application, and the Workforce Manager can see the candidates and who have applied for the opening to send to hiring managers. Member Managers will also have a view of the web application to be able to assist members with finding openings.

Identified Personas:
- Workforce Manager: The admin of the web application that uploads daily CGI Openings
- Hiring Managers: The managers who have the opening on the list
- Member Managers: Manage the CGI member who is IBA
- Available CGI Member: The member that is looking for an opening of a project/role/position

Outcome for Students: 
- Learning SDLC while using Agile Methodologies 
- Utilizing 2-week sprints and introductions to agile ceremonies 
- Using project management software to track progress of work through the semester 
- Implementing business logic for Applications to job openings
- Separating application flows depending on user access

Technologies: 
- Git
- Maven
- Spring Boot, Java
- Node.js, NPM
- Angular
- MySQL


Team Size: 4-6 students

POC: Anastasia Mokhon (anastasia.mokhon@cgi.com)

### CGI ML Pipeline
This Capstone focuses on developing a sub-second inference pipeline with AI models at its core. It provides hands on experience in using Python for model development, integrating AI/ML models with APIs, and implemented a framework for distributed processing. 

Team Size: 4-5 students

<!-- POC: Praveen Sone (praveen.sone@cgi.com) -->

## Neuraville
### Developing a FEAGI Connector for CARLA
The objective of this project is to develop a Python-based connector that integrates the CARLA simulator with FEAGI. The connector will enable the bidirectional exchange of data, allowing sensory information from a simulated vehicle in CARLA to be passed to FEAGI and motor commands from FEAGI to be relayed back to CARLA. This integration will establish a foundational framework for future development of neuromorphic autonomous vehicle solutions.

Key Features and Deliverables:
1. Data Integration:
    - **Sensory Data Transmission**: Extract sensor data from CARLA (e.g., camera feeds, LiDAR, vehicle state information) and format it for FEAGI’s input modules.
    - **Motor Command Handling**: Receive motor commands (e.g., throttle, brake, steering) from FEAGI and translate them into CARLA-compatible vehicle controls.
2. Communication Framework:
    - Establish a bi-directional communication channel between CARLA and FEAGI using a suitable protocol (e.g., websocket, or ZMQ).

    - Implement message serialization and parsing to ensure seamless data exchange.
3. Testing and Validation:
    - Develop a basic test scenario in CARLA where sensory data is transmitted to FEAGI, and simple motor commands (e.g., forward, stop, turn) from FEAGI are applied to the simulated vehicle.
    - Validate that the connector supports real-time interaction between CARLA and FEAGI.

**Background**:
CARLA is an open-source simulator specifically designed for autonomous driving research, providing realistic urban environments, diverse vehicle models, and rich sensor data. FEAGI is an open-source neuromorphic AI platform designed to emulate brain-inspired control systems using spiking neural networks.

This project focuses on building the infrastructure to enable CARLA to act as the embodiment (sensory input and motor output system) while FEAGI functions as the "brain." The connector will serve as the foundation for developing more complex autonomous neuromorphic solutions in future projects.

**Scope**:
This project is intentionally limited to establishing a functional connection between CARLA and FEAGI, focusing solely on:

1. Extracting sensory data from CARLA.
2. Sending this data to FEAGI.
3. Receiving motor commands from FEAGI.
4. Applying these commands to the CARLA simulation.

Advanced features such as neural pathway development, autonomous behaviors, and complex scenarios will be out of scope for this phase.

**Technical Stack**:
- Programming Language: Python.
- APIs and Protocols: CARLA API, FEAGI SDK, websocket and ZMQ for communication.

**Deliverables**:
1. A Python-based connector that links CARLA and FEAGI.
2. Documentation outlining the setup process and API usage for the connector.
3. A basic neural network demonstrating bidirectional data flow between CARLA and FEAGI. ( In the form of FEAGI genome)
4. A technical blog as final report

This connector will lay the groundwork for integrating neuromorphic computing with autonomous vehicle simulations, enabling researchers and developers to explore innovative AI-driven control systems in future projects.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)


### Developing a FEAGI for Webots
The objective of this project is to develop a Python-based connector to integrate the Webots robot simulation platform with FEAGI. The connector will enable bi-directional communication between Webots and FEAGI, allowing sensory information from simulated robots in Webots to be transmitted to FEAGI, and motor commands generated by FEAGI to control the robots in Webots. This integration will provide the foundation for future development of neuromorphic robotic solutions.

**Key Features and Deliverables**:

1. Data Integration:
    - Sensory Data Transmission: Collect sensor data from Webots (e.g., joint positions, proximity sensors, cameras) and convert it into neuronal activity for FEAGI.
    - Motor Command Handling: Translate FEAGI-generated motor commands into Webots-compatible control signals (e.g., joint angles, velocity commands).
2. Communication Framework:
    - Implement a robust communication layer using websocket/ZMQ to facilitate real-time data exchange between Webots and FEAGI.
    - Ensure low-latency and reliable bidirectional communication.

3. **Testing and Validation**:
    - Design a test scenario where a simulated robotic arm in Webots transmits sensory data to FEAGI, and simple motor commands (e.g., reach, move, rotate) from FEAGI control the arm.
    - Validate basic functionality and establish real-time closed-loop control.

**Background**:
Webots is an open-source robot simulation platform widely used for modeling and controlling robots in realistic 3D environments. It supports a diverse range of robot models and sensors, making it ideal for robotics research and education.

FEAGI is an open-source neuromorphic AI platform designed to simulate spiking neural networks for controlling embodied systems. Integrating Webots with FEAGI will enable researchers and developers to explore neuromorphic control principles in a highly customizable and realistic simulation environment.

This project focuses on building the foundational framework for interfacing Webots with FEAGI, creating opportunities for future exploration of neuromorphic robotic behaviors.

**Technical Stack**:
- Programming Language: Python.
- APIs and Protocols: Webots API, FEAGI SDK, websockets, ZMQ

**Deliverables**:
1. A Python-based connector linking Webots and FEAGI.
Documentation detailing setup, configuration, and usage of the connector.
2. A basic neural network demonstrating bidirectional data flow between Webots and FEAGI. ( In the form of FEAGI genome)
3. A technical blog as final report

**Impact**:
This project will establish a foundational integration between Webots and FEAGI, enabling neuromorphic AI to control simulated robots in a realistic environment. The connector will serve as a valuable tool for exploring biologically inspired control systems and advancing robotics research.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing a FEAGI for Genesis
The objective of this project is to develop a Python-based connector that integrates the Genesis framework with FEAGI. The connector will establish bi-directional communication between Genesis and FEAGI, allowing sensory data from Genesis environments to be processed by FEAGI’s spiking neural networks and motor commands generated by FEAGI to control virtual agents in Genesis. This foundational integration will enable future exploration of neuromorphic approaches to embodied AI systems.

Key Features and Deliverables:
1. Data Integration:
    - Sensory Data Transmission: Extract sensory inputs (e.g., visual, tactile, and proprioceptive data) from Genesis environments and convert them into FEAGI-compatible neuronal activity.
    - Motor Command Handling: Translate FEAGI-generated motor commands into Genesis-compatible actions to control virtual agents.

2. Communication Framework:
    - Establish a bi-directional communication channel using websocket to facilitate data exchange between Genesis and FEAGI.
    - Ensure real-time interaction with minimal latency for smooth control and feedback loops.

3. Testing and Validation:
    - Create a basic test scenario in Genesis where an agent navigates an environment or interacts with objects based on FEAGI-driven commands.
    - Validate the integration through successful data exchange and agent control in the simulation.

**Background**:
Genesis is an open-source framework designed for embodied AI research, supporting highly detailed virtual environments, modular agent architectures, and realistic physics simulations.

FEAGI is an open-source neuromorphic AI platform focused on emulating brain-inspired control systems through spiking neural networks. Integrating Genesis with FEAGI will enable researchers and developers to explore the potential of neuromorphic control in dynamic and diverse virtual environments, paving the way for advanced embodied AI systems.

**Technical Stack**:
- Programming Language: Python.
- APIs and Protocols: Genesis API, FEAGI SDK, websocket, ZMQ.

**Deliverables**:
1. A Python-based connector facilitating data exchange between Genesis and FEAGI.
2. Documentation outlining setup, configuration, and usage of the connector.
3. A basic neural network demonstrating bidirectional data flow between Genesis and FEAGI. ( In the form of FEAGI genome)
4. A technical blog as final report

**Impact**:
This project will enable the integration of Genesis with FEAGI, combining the strengths of Genesis' virtual simulation capabilities and FEAGI’s neuromorphic AI. The connector will serve as a foundational tool for embodied AI research, offering a platform to study spiking neural network-driven control in realistic and dynamic virtual environments.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing a FEAGI Connector for Blender to enable Neuromorphic Control of 3D Models
The goal of this project is to create a Python-based connector that integrates Blender with FEAGI, allowing FEAGI’s neuromorphic AI to control and animate 3D models in Blender. This integration will enable spiking neural networks to drive real-time animations, simulate sensory feedback, and perform complex behaviors such as navigation, manipulation, or interaction with the 3D environment.

The project will include:
1. Data Exchange Mechanism:

    - Develop a bi-directional communication channel between Blender and FEAGI using websocket.
    - Transmit sensory data (e.g., collisions, proximity readings, camera views) from Blender to FEAGI.
    - Receive motor commands from FEAGI and apply them to control object transformations, armatures, or animations in Blender.

2. Mapping and Configuration:
    - Create a mapping system to associate FEAGI's neuron groups with Blender's model attributes (e.g., joints, bones, or other animatable properties).

3. Real-Time Control:
    - Implement real-time updates to reflect FEAGI's outputs in Blender’s viewport, including object movements and animations.
    - Support real-time physics-driven behaviors influenced by FEAGI.

**Background**:
Blender is a powerful open-source tool for 3D modeling, animation, and simulation, equipped with a comprehensive Python API. 

FEAGI is an open-source platform designed for brain-inspired AI using spiking neural networks. Combining these platforms can enable the creation of dynamic, lifelike 3D simulations where virtual characters and objects are controlled by biologically inspired neural networks. This connector will open new possibilities for interactive simulations, neuromorphic animation, and educational demonstrations of embodied AI.

**Technical Stack**:
- Programming Language: Python.
- APIs and Protocols: Blender Python API, FEAGI SDK, and communication protocols (e.g., socket or MQTT).
- Visualization Libraries: Leverage Blender’s native rendering and Python scripting for neural activity visualization.

**Deliverables**:

1. A Python script or add-on for Blender that serves as the FEAGI connector.
2. Configuration templates for sensory and motor mappings.
3. Documentation and tutorials for setting up and using the connector.
4. Demonstration files showcasing integration with FEAGI for various use cases.

By enabling FEAGI to control 3D models in Blender, this project will provide a powerful platform for developing and showcasing neuromorphic AI in visually engaging and interactive ways.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing a Mobile Remote Controller App for FEAGI
The objective of this project is to develop a mobile application that acts as a remote controller for FEAGI. The app, built using React Native and the Godot game engine, will enable the transmission of sensory data from the smartphone—such as accelerometer, gyroscope, and camera feeds as well as user inputs—to FEAGI for neuromorphic control of robots. The app will also include a user-friendly interface for configuring and tuning the input/output interfaces between the mobile device and FEAGI. This foundational project will enable the integration of smartphone sensors into neuromorphic control systems, with potential for future expansion into advanced features.

**Key Features and Deliverables**:
1. Data Integration:
    - Sensory Data Transmission: Collect sensor data from the smartphone (e.g., accelerometer, gyroscope, and camera) and transmit it to FEAGI.

2. User Interface:
    - Design an intuitive React Native-based interface for users to interact with the application
    - Include toggles and sliders for activating neurons in a given brain region
    - Include toggles and sliders for adjusting visual input parameters

3. Real-Time Processing and Visualization:
    - Use Godot to preview real-time brain visualization (read-only)

4. Communication Framework:
    - Establish bi-directional communication using websocket for real-time data exchange between the app and FEAGI.

5. Testing and Validation:
    - Demonstrate the app’s ability to collect and transmit sensory data to FEAGI for controlling simple robotic systems.
    - Demonstrate neuronal activities are displayed on the app.

**Background**:
React Native is a popular framework for cross-platform mobile application development, enabling a single codebase to work on both Android and iOS.

Godot is an open-source game engine that excels in real-time rendering and simulation, offering dynamic visualization and feedback capabilities.

FEAGI is an open-source neuromorphic AI platform that processes sensory data through spiking neural networks for controlling robots. Integrating smartphone sensors into FEAGI will empower users to experiment with neuromorphic control, bridging the gap between mobile technology and robotics.

**Technical Stack**:
- Programming Languages: JavaScript (React Native), GDScript (Godot), Python (FEAGI integration).
- APIs and Protocols: React Native Sensor APIs, Godot Engine API, FEAGI SDK, websocket for communication.

**Deliverables**:
1. A cross-platform mobile app with real-time data exchange capabilities between the smartphone and FEAGI.
Documentation outlining the app’s setup, configuration, and use.
2. A basic demonstration showcasing neuromorphic control of a robot using smartphone sensors. ( In the form of FEAGI genome)
3. A technical blog as final report

**Impact**:
This project will enable the integration of smartphone sensors with FEAGI, creating a portable and intuitive platform for neuromorphic experimentation. By leveraging the accessibility of mobile devices, researchers and developers will be empowered to explore new possibilities in neuromorphic robotics, combining mobility, sensory versatility, and spiking neural networks to push the boundaries of embodied AI systems.


Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing an XML Parser and visualizer for Generating FEAGI Configuration Files
The primary goal of this project is to create a Python script that parses Simulation Description Format (SDF) files from the Gazebo simulator and automatically generates configuration files for FEAGI. This integration will facilitate seamless communication between Gazebo (as the embodiment) and FEAGI (as the neuromorphic controller) by mapping the sensory data and motor control mechanisms described in the SDF file to FEAGI-compatible configurations.

**Key Features and Deliverables**:

1. SDF Parsing and Analysis:
    - Extract critical elements from SDF files, including:
        - Robot models: links, joints, and actuators.
        - Sensor configurations: cameras, LiDAR, IMUs, etc.
        - Environmental features.
2. Mapping to FEAGI Configurations:
    - Translate SDF elements into FEAGI neuron groups, sensory input channels, and motor outputs.
    - Ensure compatibility with FEAGI’s sensory and motor interface specifications.
3. Configuration File Generation:
    - Create a FEAGI-compatible configuration file that:
        - Defines sensory inputs for Gazebo’s simulated sensors.
        - Maps motor commands to Gazebo’s actuators.
4. Configuration visualization:
    - Utilizing Gdot game engine’s node graph, visualize the configuration objects and enable user to edit mappings and properties. 
5. Testing and Validation:
    - Test the script using example SDF files to verify the accuracy of sensory-motor mappings and overall integration.

**Background**:
Gazebo’s Simulation Description Format (SDF) provides a standardized way to define robots, sensors, and environments in simulations. By parsing SDF files, developers can gain structured insights into simulation components.

Godot is an open-source game engine that excels in real-time rendering and simulation, offering dynamic visualization and feedback capabilities.

FEAGI is an open-source neuromorphic platform that uses spiking neural networks for brain-inspired AI. Integrating Gazebo with FEAGI requires a configuration layer that translates SDF-described attributes into FEAGI’s neuron-based framework for seamless interaction.

**Technical Stack**:
- Programming Languages: GDScript
- APIs and Libraries: Gazebo SDF Parser libraries, FEAGI SDK, WebSocket and ZMQ communication protocols.

**Deliverables**:
1. A GD script capable of parsing SDF files and generating FEAGI configuration files.
2. A very simple UI enabling user to edit the configuration file properties
3. Documentation on usage, including examples and test cases.
4. A demonstration of Gazebo-FEAGI integration using a sample SDF file. ( In the form of FEAGI genome and configuration file)
5. A technical blog as final report

**Impact**:
This project simplifies the process of connecting Gazebo simulations with FEAGI, enabling researchers and developers to experiment with neuromorphic AI in realistic robotic simulations. Automating the generation of FEAGI configurations from SDF files reduces development time, minimizes errors, and promotes the use of neuromorphic computing for robotics research and innovation.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

# Community and Other Organizations

## Pittsburgh Street Medicine 
### Street Medicine at Pitt “Prime Delivery” Service Web Application

**Objective**: The objective of this capstone project is to develop a multimodal accessible website application for individuals served by Street Medicine at Pitt, including those at the Second Avenue Commons Clinic. The project's focus is to allow individuals to request/order necessities, including food, beverages, clothing, toiletries, basic medical supplies, and other supplies as needed, in addition to Street Medicine at Pitt’s weekly Wednesday evening “street rounds,” and make modifications as appropriate based on client feedback.

**Background**: Street Medicine at Pitt is a student-run interdisciplinary organization dedicated to providing healthcare and social support to the rough-sleeping and unhoused communities in Pittsburgh. The organization is affiliated with the University of Pittsburgh School of Medicine, which recently established the Center for Street Medicine. Street Medicine at Pitt partners with the Second Avenue Commons Clinic, which provides shelter access, medical services, and engagement centers for adults experiencing homelessness in Pittsburgh.

More information: https://www.streetmedatpitt.org/home

**Project Goals**:

Priority Areas:
- Develop a website application that allows clients and Street Medicine at Pitt volunteers to submit supply requests/orders at any time
- Develop a tracking system to accurately collect clients' location details for efficient delivery management
- Develop a data tracking tool to track data such as the number of deliveries per week, the number of items requested per week, the number of individuals making requests per week, and the types of items requested
- Attend 2-3 Wednesday weekly evening (6:30-9 PM) “street rounds” with the Street Medicine at Pitt team

Secondary Areas:
- Develop a traffic analysis tool to track the performance, moderation, and utility of the website application
- Develop a scheduling software for Street Medicine at Pitt volunteers to schedule item deliveries

Team Size: 4 students

POC: Stella Ross (sfr12@pitt.edu) and Victoria Bacchi (vmb35@pitt.edu), please CC Dr. Anna Marie White (whitea3@upmc.edu), Dr. Max Hurwitz (mbh39@pitt.edu), and Sam Ding (ding.sam@medstudent.pitt.edu) on all communications.

## NOAA
### Machine Learning Based Predictive Modeling of Bacterial Pathogens with Stony Coral Tissue Loss Disease
In 2014, Stony Coral Tissue Loss Disease (SCTLD) was first observed in Virginia Key, Florida (Miller et al., 2016; Precht et al., 2016; Walton et al., 2018). The disease spread swiftly through Florida and is now in the Caribbean, making it one of the longest-lasting coral disease outbreaks. To date, SCTLD impacts at least 23 species of reef-building corals, significantly reducing coral diversity in an already vulnerable ecosystem (Precht et al., 2016; Walton et al., 2018). 

As with many coral diseases, the cause of SCTLD remains unclear. Preliminary research suggests that antibiotics may be effective in halting lesion progression (Aeby et al., 2019). This points to the possibility that the pathogen could be bacterial, or that secondary bacterial infections might significantly contribute to lesion development.  Studies to date have not identified bacteria consistently present across coral species (Rosales et al., 2023, Meyer et al., 2019).
To identify bacteria linked to disease, scientists often use differential abundance analysis to determine which bacteria are more prevalent in treated samples compared to controls. However, this method has faced criticism (Quinn et al., 2021). In the proposed project, students will explore alternative approaches to characterize the causative agent(s) of SCTLD. Instead of relying on differential abundance analysis, students will employ machine learning techniques on previously analyzed microbiome data (Rosales et al., 2023). They will use various machine learning classifiers to develop a predictive model aimed at identifying both primary and secondary bacterial pathogens associated with SCTLD.

Team Size: 2 students

POC: Stephanie Rosales (Stephanie.Rosales@noaa.gov)

## Pittsburgh Radio Rosary and Consecration
### Pittsburgh Radio Rosary and Consecration Interactive Prayer Service
The Pittsburgh Radio Rosary and Consecration, Inc. provides a daily 7 pm scriptural Rosary and Sacred Heart prayer of Consecration radio broadcast on WKHB at 620 am and transmit on 92.3, 94.1, and 102.1 FM. This broadcast, a tradition for over 50 years in the Pittsburgh region, has been a source of spiritual connection and unity.  In April 2022, PITTRRC assumed the ministry's rights and responsibility; now, we are ready to continue taking it to new heights.  A new audio production was created in July 2022.  In January 2023, development began with a corresponding website.  This website is unconventional in that it has four distinct pages: a live broadcast radio station, interactive prayers for the Rosary and Sacred Heart, Catholic resources, and a regional social media page for spiritual events and faithful expressions. The website is nearly complete, with just another revision update coming soon and some content pages added. www.pittrrc.org There has been a good response so far, with the site being ranked first for searching “Pittsburgh Rosary” with Bing but, unfortunately, on page 5 with Google, so there is still some work needed to get the website out to the masses, and I need your help.  

This project involves developing an app from the website that functions on Android and iOS. I will also need to work on search engine optimization (SEO) and some programming ability to correct any possible website issues ensuring compatibility between the app and the site. 
- APP Development for Android and iOS
- SEO Development: Optimize the Search Engine Results Page (SERP), Find keyword indicators, determine all browsers available, and optimize each for maximum results. Use coding and software abilities to grow and provide analytics. 
- With the incorporated SEO development, create and track a YouTube channel for PITTRRC that will have interactive prayers for the Rosary mysteries and the Sacred Heart.  
- Ensure responsive design on the App and with the web browsers.

Various sprints will be involved, and you will need to function independently, as I have no background as a developer for each.  Must be willing to find the means to learn new abilities and consider this project as working in a real work experience.  Our first meeting will be in person one evening.  A weekly Zoom meeting will follow in the evening when it is convenient for the team to meet.  The meeting will review the week's accomplishments and goals for the next task sprint. 

Team Size: 2-3 students

POC: John DePasquale (jbdepasquale@msn.com)

# Computer Science Faculty Projects
## Daniel Mosse 
### BeyondTranscripts, Predicting Student Grades to Help Advising
Student grade prediction is a popular task for learning analytics, given grades are the traditional form of measuring student performance. In many previous machine learning models, previous grades and instructor features are considered as the main features.

In this project, the team will understand the existing code and continue to develop, refine, and create new models to improve performance.  After understanding the code, every week the team will try and propose new features, study and analyze the results using graphs that are automatically generated, present them using PPT or similar, and discuss with mentors the performance and next week's experiments.

Students interested in this project should have completed at least a machine learning or data science course.  If you have any questions about this project, please contact Nathan Ong at nro5@pitt.edu or Daniel Mosse at mosse@pitt.edu. Nathan is a post-doc at Pitt’s LRDC+UCTL, Daniel is a faculty member in CS. We will have weekly meetings for discussing results of past week, and setting goals for the following week; we will take turns taking notes (or use JIRA and github) to keep track of project progress.


Team Size: 2-3 students

POC: Nathan Ong (nro5@pitt.edu), Daniel Mosse (mosse@pitt.edu)

### Sensing the Built Environment: Data Collection and Analysis for Sennott Square 
This project will create an easy-to-use and cost-conscious infrastructure to collect data in Pitt buildings.  We will collect data in Sennott Square, targeting the 5th and 6th floors, using temperature and humidity sensors, specifically the Govee Thermo-Hygrometer device.  The data collected will help Pitt’s Facilities Management (FM) improve building energy optimization and temperature/humidity comfort.  For example, FM has “occupied” and “unoccupied” schedules, with different temperature/humidity setpoints; we will detect these schedules and let them know. 

Initial data collection revealed no significant temperature differences between weekends and weekdays, suggesting a lack of HVAC optimization based on occupancy or schedules. This project aims to expand upon these findings by conducting more extensive data collection in Sennott Square (which will serve as an exemplar for other buildings). 

The student is expected to: 
- Become familiar with the functionality of Govee sensors+hubs, the current initial deployment, and develop an understanding of designing a sensor communication network.  Technology used: Govee, Raspberry Pi, Bluetooth, and Wi-Fi. 
- Design a data monitoring and collection plan to deploy a sensor network that collects representative data from various rooms. Show that the deployment has small error (<1%) throughout the data collection.  This process should be automated, that is, no human intervention aside from placing sensors in the right locations. 
- Create a software infrastructure to export the data to a repository (perhaps reverse engineer the communication protocol), analyze the data (see next item), and produce daily summary reports, for example how much data was collected, alert users if number of samples is lower than expected (i.e., the system is not working as intended), etc. This process should be automated. 
- Process and analyze the collected data to identify patterns and reverse engineer HVAC schedules (i.e., determine whether heating and cooling schedules are programmed based on seasonal variations, weekends, working days, or working hours). This process should be automated, that is, no human intervention aside from placing sensors in the right locations. 

Team Size: 2 students 

POC: Daniel Mosse (mosse@pitt.edu) and Ousmane Dieng (oud5@pitt.edu)

### Occupancy Sensing and Data Collection in the Built Environment Using LoRa Networks 
This project aims to **enhance and stabilize** the existing deployment of occupancy sensors in Sennott Square rooms using LoRa networks; we will also explore innovative solutions to collect accurate data on room occupancy and occupant count. The project will focus on addressing the issues currently observed in the existing system (a sensor platform built in house, not commercial) and extending the capability of the LoRa-based infrastructure to provide reliable occupancy data for building energy optimization and improved space utilization in Pitt buildings. 

An initial deployment platform uses Passive Infrared (PIR) sensors for occupancy detection and is already in place in two rooms. However, challenges have been identified, such as inconsistent readings, communication stability, and potential inaccuracies in detecting occupancy patterns. Building on this foundation, this project will address these challenges, stabilize the system, and introduce improvements to achieve high accuracy and reliability in occupancy data collection. 
 
The students are expected to: 
1. Understand existing infrastructure: 
    - Study the current deployment of PIR sensors and LoRa communication network. 

    - Investigate the root causes of observed issues (such as inconsistent readings, communication instability, and sensor errors) through extensive experimentation and data analysis. 

2. Stabilize the existing system:
    - Develop solutions to address issues in sensor performance and communication stability. 

    - Place the sensor where it reduces the observed issues. 

    - Write code in the device to calibrate the sensors to improve accuracy and reliability. 

3. Enhance occupancy data collection: 

    - Propose and implement innovative sensing solutions to supplement PIR sensors for detecting occupancy and occupant count. Possible solutions could include integrating complementary sensor types (e.g., CO₂, ultrasonic, or camera-based systems) and/or creating an app (or a qualtrics survey/webpage) that collects the comfort level of the room occupants. 

    - Explore methods to detect occupant activity (e.g., active, passive, or away states) using advanced data processing techniques, additional sensors, and/or thru the “app” in the previous item 

4. Develop data analysis and automation: 
    - Automate the data collection and processing pipeline, eliminating human intervention beyond deployment (except for handling hardware errors). 

    - Analyze collected data to derive insights such as occupancy patterns and occupant count. 

    - Correlate occupancy data with HVAC operation schedules (from a different project) to identify optimization opportunities. 

5. Evaluate and demonstrate system performance: 
    - Develop a plan to demonstrate that the improved system has small error (<1%) in occupancy detection and provides consistent, actionable data. 

Technology used: 
- Sensors (no previous knowledge needed): PIR sensors, LoRaWAN-compatible devices, and additional sensors for activity detection (as needed). 
- Network infrastructure (no previous knowledge needed): LoRaWAN gateways, Raspberry Pi or similar for data aggregation. 
- Data processing: Python for data analysis and visualization, IoT platforms for data integration. 

Team Size: 2 students 

POC: Daniel Mosse (mosse@pitt.edu) and Ousmane Dieng (oud5@pitt.edu)

## Sustainability in buildings: using cheap InfraRed cameras to detect leaks in windows  

A large portion of the built environment in US are not properly sealed and are prone to thermal leaks/anomalies. This often affects the low-income households, which spend a large portion of their income on heating and cooling.  These inefficiencies might be due to factors like improperly sealed windows and doors, missing insulation, inefficient HVAC equipment, etc. 

Small air leaks are invisible to the naked eye and an RGB image cannot give us enough information to detect them. But thermal images (temperature map of the area of interest) obtained with InfraRed cameras can enable us to detect the anomalies on and around windows (and doors). We are aiming to detect leaks in windows (and doors, time permitting) so that we can, in the future, provide repair/upgrade solutions/options to the homeowner or occupant. 

By the end of the semester, the students are expected to: 
- Contribute infrared/thermal and RGB/regular images towards a dataset of thermal images of windows 
- Annotate the images with leaks to create a dataset with ground truth. Annotations may involve categories and bounding boxes for leaks. 
- Evaluate different Machine Learning / Computer Vision models to determine the most precise one for this task. 
- Contribute to a software pipeline that aims to make it easier to load new data (RGB/IR images of windows) and executes algorithm on the dataset to classify the windows as leaky or not. 

 
Team Size: 2 students 

POC: Daniel Mosse (mosse@pitt.edu) Nils Murrugarra Llerena <nem177@pitt.edu> and Dilip Teja Polamarasetty <DIP67@pitt.edu> 

## Aakash Gautam
### Digital Literacy for Returning Community Members
We are working with a non-profit organization that supports formerly incarcerated individuals  (who we call "returning community members") in their reentry journey. A part of the organization's program involves promoting digital literacy as a way to support empowered reentry. We have been working with the organization to develop a web application that they will use to provide digital literacy lessons.  We are seeking help in building a new feature to support envisioning future goals and connecting them with local resources.

A key issue shared by the returning community members is that they struggle to figure out what resources are available near them. This is a structural problem. We do not have a well-curated list of local resources, and most of the lists that have been created are seldom verified. More critically, these resources are not presented in a way that informs people how they can use them for the goals that matter to them. To attend to this issue, we want to build a system that enables people to establish goals and find resources that would assist them in meeting those goals.

We have a prototype of the tool here: https://clester31.github.io/PR-MindMap-React/. As you can see, we are working on supporting people to establish goals across eight different values. They can seek out role models to identify attributes and skills they would like to develop. There are issues in the prototype that we need to work on this semester. It includes the following:
1. Support user accounts (login/logout).
2. Integrate a way to support people to reflect on their strengths and add those in the vision board.
3. Make the graph more interactive (e.g., easy dragging and dropping; change image size).
4. Add a note taking feature to support reflection.
5. Most critically, integrate resources from  findhelp.org such that they can connect some of the local resources that can support their goal(s).

Technical skills required: Basic HTML/CSS/JS; React
Team Size: 3-5 students

POC: Aakash Gautam (AAKASH@pitt.edu)

## Luís Oliveira

### Simulated Virtual GPS
In this project we're going to simulate a GPS using a flying drone. The scenario I have in mind is a team of cooperating robots that move on the ground. They don't have GPS, but can measure the distance between them using RF techniques (special purpose hardware). In the air, one or more drones have GPS localization, and can measure the distance to the robots on the ground. Having all those measurements, I want to calculate the global coordinates of the robots using the distance between them and the drones; and the GPS localization of the drones. The whole application will be simulated and using a very popular middleware for robotic applications ROS 2.


Tools: 
- ROS 2: Robot Application Middleware
- Gazebo simulator

Knowledge:
- C++ preferred, Python also ok (sad).
- Previous expecience with the tools being used is good, not required.

Team size: 3–4 students

POC: Luís Oliveira (loliveira@pitt.edu)

### Programming a linux kernel module to control network traffic

This project involves developing a Time Division Multiple Access (TDMA) network-traffic scheduler within the Linux kernel. You are taking a kernel module developed in a previous semester, and work on the configuration from user space. We'll build a simple demo application using it, and measure the overheads using extended Berkley Packet Filter. It's part of the project learn about eBPF and how to use it to instrument the Linux kernel calls.


Prerequisite: Must have taken CS1550.

Team size: 3–4 students

POC: Luís Oliveira (loliveira@pitt.edu)

### Interactive Web App 

Using Angular to build an interactive application like logisim. You tool CS447, I want a similar tool on a web browser. The initial goal is the GUI design, create a set of logical gates, drag them around, connect them. The first couple of weeks of work will be focused on researching tools that can help with the implementation. No need to build everything from scratch. Having the tools, we'll create the basic gates, and the tooling to connect the circuits. Then we'll design ports and the creation of subcircuits. Once this is done, if there is enough time left, we'll look into the simulation of those circuits.


Tools:
- Angular and plugins from initial research.

Languages:
- Java/Typescript.

Team size: 3–4 students

POC: Luís Oliveira (loliveira@pitt.edu)

## Alex Labrinidis
### CEC Check-in Kiosk and Database
 
The University of Pittsburgh has multiple Community Engagement Centers (CECs) and is looking for a technology solution to help them better understand community engagement with their programs. Towards this, they want to have a check-in “kiosk” at the entrance of the centers that will allow visitors to tap/scan their Pitt/CEC ID cards and pick the event they are coming to participate in (out of those happening that day). In addition to recording check-ins, the project should recognize visitors who come often and provide a web front-end for visualizing the check-in data to CEC staff.
 
There are at least four different components to this project:
1. Visitor-facing UI through a native app running on a tablet (currently considering iPad, so Swift) – there is already a reader that connects as a keyboard to read the IDs
2. Backend database (PostgreSQL) and integration with Pitt databases (for example, to associate a name with the ID read)
3. Web front-end for check-in data querying/visualizations (Python/Flask)
4. Testing of UI and web front-end (Selenium)
 
A very rudimentary prototype is already in place since the work started in the Fall 2024 term, but this is meant as a simple proof of concept. We are looking to deploy the project using the Heroku cloud platform but will probably migrate to Pitt servers sooner rather than later.
 
Skills required for everybody:
- experience with GitHub is necessary for all team members
 
Skills required (not everybody will have all of these):
- web development experience (Python/flask)
- database development experience (PostgreSQL)
- data visualization experience (Python viz libraries)
- utilizing external APIs and parsing/generating JSON files
 
Skills you will learn if you don’t already have (not everybody will need all of these):
- UI design (Swift or Flutter)
- UI testing (Selenium)
- Cloud deployment (Heroku – this is the easiest of all)
 
The specific technologies are not set in stone; I am open to suggestions, especially in the UI design/native app space.
 
Team size: 3-4 students, depending on your role in the project, different skills will be needed.
 
POC: Alex Labrinidis (labrinid@cs.pitt.edu)

## Adam Lee and Prsaad Chalasani
### AI Policy Assistant
 
This Capstone Project aims to harness the power of generative AI to enhance the accessibility of university policies and guidelines. This project will focus on creating a unified platform where program and academic administrators, advisors, and students can easily navigate and comprehend the myriad regulations currently dispersed across University and School Catalogs, Office of the Provost guidelines, and formal University Policy documents. By leveraging AI tools like PittGPT or Langroid, the system will enable users to quickly answer fundamental questions about policies and academic program requirements, discover connections between related policies, and identify additional resources for deeper policy-related research. This initiative, suitable for a team of three students, aims to simplify the policy exploration process, making it more intuitive and user-friendly, ultimately improving compliance and knowledge dissemination.
 
Students participating in this project will face several key responsibilities and challenges. They will need to collaborate with stakeholders to understand common inquiries and identify the most pertinent types of questions. Additionally, students must explore methods to detect ambiguities and resolve conflicts among multiple policies/guidelines that may provide differing information relevant to the same inquiry. Balancing the need to deliver complete and authoritative answers with the necessity of guiding users towards further reading within the source documentation will be crucial, particularly in situations where the relevant policies and guidelines are nuanced. By tackling these challenges, students will not only enhance their technical skills but also develop a deeper understanding of policy management and user-centered design.

Team Size: 3 students

POC: Adam Lee (adamlee@pitt.edu), Prasad Chalasani (pchalasani@pitt.edu)

## Nadine von Frankenberg
### Treefficiency 
"Treefficiency" focuses on the gamification of learning about energy efficiency at home, specifically targeting appliances and energy-saving options available to home owners and renters. By integrating interactive, game-based elements, the project aims to educate homeowners and renters on effective strategies to reduce their carbon footprint, energy consumption, and costs. You will be extending the project with some fun features. Be creative! Features could be: an interactive forest that grows based on trivia points, using OCR to process energy bills, defining scripts to analyze user data,... The project currently comprises mobile Flutter apps but could also be extended by a web version to monitor the state of the application and database.

Skills:
- Some knowledge in Flutter / Dart Desirable but not required

Team Size: 3-4 students

POC: Nadine von Frankenberg (vonfrankenberg@pitt.edu)

### TeachTech Toolkit
"TeachTech Toolkit" aims to enhance teaching and learning workflows by integrating tools, including Canvas and Gradescope, along with the setup of GitHub projects. It aims to create a cohesive workflow that facilitates efficient assignment distribution, grading, and feedback, while also incorporating practical aspects of software development, such as version control, test case development, and API interaction. You will be defining workflows and implement small applications throughout the project.

Team Size: 2 students

POC: Nadine von Frankenberg (vonfrankenberg@pitt.edu)


## Prasad Chalasani
### Project: HackerMind --  Answer questions based on HackerNews

Inspired by: https://hackersearch.net/

Summary:

HackerNews (HN) is a rich source of in-depth community discussions on a vast variety of topics, such as AI (LLMs), gadgets, technology, software, events, politics, etc.  The project aims to build a CLI tool leveraging LLMs (Large Language Models) to answer questions based on HN discussions, using the Langroid open-source LLM framework (the POC is the lead architect and developer).

Background:

HN discussions often containing diverse perspectives and go down rabbit-holes leading to useful links similar to or relevant to the main article being discussed. E.g. see this discussion about OpenAI's new O3 LLM: https://news.ycombinator.com/item?id=42473321

When we want to learn about a topic , tapping into the "collective wisdom" of HN can help us understand:
- what the latest thinking is about a topic
- pro and con arguments/sentiments, praise, skepticism, etc 
- other resources that can help get deeper knowledge and insights about the topic.

Normally, to do this you would have to:
- find the relevant HN articles,
- read them in detail, 
- identify main themes, 
- find pro (praise) and con (skeptical) arguments,  
- find useful articles/sites linked in the discussions, and 
- synthesize a coherent report with several sections 

Large Language Models (LLMs) offer the ability to automate the process leading to the final report, but you need a good programming framework to accomplish this; i.e. one that abstracts away low-level LLM API details and lets you work at a higher level. Langroid is an Open-source Agent-oriented Python framework that does just that -- You can define Agents, assign them tasks (in this case find HN articles, find main themes etc) and organize them into a workflow that accomplishes a task (in this case produce the final report). 

In this project you will use Langroid to build a CLI (Command-line Interface) tool that takes a user's question and produces a final report containing the various elements outlined above.

Requirements: 
1. Strong Python coding skills (no need for raw ML skills as no model-training is involved)
2. very strong interest in learning how to work with LLMs and build agent-oriented systems

Have a look at langroid here: https://github.com/langroid/langroid and quick tour here: https://langroid.github.io/langroid/tutorials/langroid-tour/

POC: Prasad Chalasani, Adjunct Professor, Pitt/SCI and CMU/Tepper. Co-founder of Langroid

## Nils Murrugarra-Llerena
### Understanding Psychological Test with visualizations
**Motivation scenario**

Psychologists understand human nature using psychological tests. For example, they may be interested in studying different personality traits using questionnaires, or study multiple intelligences in a similar fashion. These tests already have some output categories. We aim to find if there are relations between the human intuition output and a data-driven approach.

**Objective**

Develop a tool to visualize questions of relevant tests such as personality, multiple intelligences, and others. We aim to see if human intuitions correlate with data-driven visualizations.

**Approach**

Our approach will consist of the following steps: 
- Look for psychological tests to evaluate different human aspects. For example, the test of Holland for personality (realistic, intellectual, social, conventional, entrepreneur, artistic); test of Gardner for multiple intelligences (linguistic, mathematical, spatial, interpersonal, intra personal, naturist, etc); among others.
- Visualize questions for each of those tests: 
    - Compute a Bert Embedding for each ot the questions
    - Visualize questions per test with color using t-SNE or Umap
    - Interpret visualization: how questions are grouped? Are they related to the outcomes of the tests? (e.g. personality or multiple intelligences)
- Depending on results, we may need to train a new BERT model with psychological textbooks, and or apply metric learning for more accurate representations.

**Experimental evaluation**
We will compare different Textual embeddings (e.g. BERT) to compare questions from psychological tests. We expect that these embeddings capture similar questions under a certain outcome (e.g. personality or multiple intelligences).

Team Size: 2 students

POC: Nils Murrugarra-Llerena (nem177@pitt.edu)

## Jacob Biehl and the Surreality Lab
### Cross-Platform Object Tracking and Streaming Package for Mixed Reality with Unity
The Surreality Lab (https://surreality.pitt.edu) is a joint medical-computer science research lab studying mixed reality (MR)/spatial computing and its applications to surgery. Many applications of mixed reality, especially in the medical field, require accurate tracking of physical objects in the real world so that virtual artifacts can be aligned with them. Wireless low-latency video streaming is another component of many medical mixed reality applications. For instance, a surgeon may want to stream an endoscopic feed to view in mixed reality.

The Surreality Lab is seeking a student team to develop a cross-platform Unity package that allows for near-real time (<300ms latency) object tracking (with or without fiducial markers) and low-latency (<=100ms) video streaming for MR applications on the Microsoft HoloLens 2 and Apple Vision Pro. So far, we have developed working code that allows for video streaming with MJPEG at around 100ms of latency on the Microsoft HoloLens 2. To port this code to the Apple Vision Pro, the libjpegturbo library will need to be compiled for visionOS (it has previously been compiled for iOS), and the native libraries will need to be changed in Unity. Possible approaches for object tracking include using the native object and image tracking libraries on the HoloLens and Vision Pro (ARMarkerManager and ARKit respectively) or building a native plugin using OpenCV (this technique will require use of the enterprise camera API on visionOS, which we have been granted access to).

We can provide equipment (Microsoft HoloLens 2s, Apple Vision Pros, development machines) to assist with the development of the package. This project, if successful, would greatly improve the efficiency of developing MR software for the Surreality Lab and hopefully lead to future innovation in medical MR and medicine at large.
 
**Skills Required**: Unity, C#, Swift, Linear Algebra, C/C++/Objective-C, possibly OpenCV/camera calibration

Team Size: 3-4 students

POC: Griffin J. Hurt (griffhurt@pitt.edu), Jacob Biehl (biehl@pitt.edu)


## Scott Jordan
### Autonomous Driving from Human feedback for RC Cars
I have two remote controllable RC cars with cameras and Nvidia Jetson GPUs. I would like to develop a system for them that can be used to teach the cars to drive around various areas and race each other. The software for these systems needs work is simple and I would like to build out tooling that will allow for it to easily record user controlled demonstrations, run the cars autonomously, and be able to give feedback to the car on how well it is doing. I also need functionality developed to do some learning from demonstration to create a model that can be used to drive the car autonomously. There is lots of room for innovation in this project and to do both AI work and software engineering. If you are interested in AI, autonomous systems, or edge devices this could be a great project for you.

Team Size: 3-4 students

POC: Scott Jordan (scott.jordan@pitt.edu)


