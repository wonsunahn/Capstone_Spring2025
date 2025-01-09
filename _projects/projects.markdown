---
layout: page
permalink: /projects/
---

# Capstone Project List
Below is a list of the projects for the Fall 2024 semester. 

# Industry Capstone Projects

## CGI 
**Will require signing an NDA/IP release**

### CGI Member Management System
CGI members work on different projects for clients. As a project approaches conclusion there is a period where members are seeking their next project. Currently, members who are seeking their next project receive via emails and gain access to an Excel spreadsheet that is updated daily with project opportunities.  This excel contains numerous columns (26) on all the details of the opening. The member then sorts through the positions to find something that fits their qualifications and desires. Members then send an email to the Workforce Manager of a list of openings they are interested in with some of the necessary data to apply for the opening, along with some other documents with required information about the member. The Workforce Manager relays this information to the hiring managers of that opening to onboard the member. During this entire process, CGI members have a Member Manager who can also assist members with finding and applying to open positions. 

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

<!-- POC: Anastasia Mokhon (anastasia.mokhon@cgi.com) -->

### GenAI-powered Customer 360° View
In modern businesses, understanding the customer holistically is critical for delivering personalized experiences, improving customer satisfaction, and driving business growth. However, customer data is often fragmented across multiple systems and departments, making it challenging to obtain a unified view. This project aims to develop a GenAI-powered solution that consolidates customer data from various sources to create a comprehensive Customer 360° View & insights/recommendations.

The solution will leverage Large Language Models (LLMs) to analyze and synthesize customer data, providing insights into customer behavior, preferences, sentiment, and more. The customer data will be stored in a vector database, allowing for efficient retrieval and similarity search. Based on user input, relevant data will be dynamically populated to provide a real-time, personalized customer view. The goal is to enable businesses to have a complete understanding of each customer, allowing for more targeted marketing, better customer service, and informed decision-making

Identified Personas:
- Marketing Manager: Uses Customer 360° View to segment customers and create personalized marketing campaigns.
- Customer Support Agent: Accesses detailed customer history and sentiment analysis to provide tailored support.
- Sales Representative: Utilizes insights from the Customer 360° View to identify upsell and cross-sell opportunities.
- Data Analyst: Analyzes aggregated customer data to identify trends and provide strategic recommendations.
Outcome for Students: 
- Learning about the integration of GenAI with customer data systems.
- Understanding the process of creating a unified data model from disparate sources.
- Gaining experience in developing AI models.
- Utilizing AI-driven analytics to extract actionable insights from customer data.

Technologies: 
- Python 
- GenAI concepts - LLM, RAG, Embeddings 
- FAISS – Vector database 
- VS Code/Jupiter Notebook 
- Angular

Team Size: 4-5 students

<!-- POC: Praveen Sone (praveen.sone@cgi.com) -->

<!-- ## Neuraville
Neuraville Inc. is a leading deep technology company headquartered in Pittsburgh, PA, specializing in artificial general intelligence (AGI) and robotics. Our mission is to make the development of safe, versatile, and functional AI systems accessible to everyone. We focus on creating AI that can process diverse sensory data and execute complex tasks requiring cognitive reasoning and decision-making.
At Neuraville, we embrace a novel approach rooted in nature-inspired methodologies, drawing insights from neuroscience, genetics, and developmental biology. This allows us to develop AI systems that mirror the complexity and adaptability of natural intelligence. We believe in democratizing AI, empowering individuals to innovate, create, and profit from their ideas. Our vision is to see, in the near future, robots extending a helping hand to humans in need—whether due to aging, sickness, disability, or simply as assistants to take on the burden of repetitive and mundane tasks—allowing us to focus on what we value most.

Each project revolves around our open-source platform, [FEAGI](https://github.com/feagi/feagi) or the Framework for Evolutionary Artificial General Intelligence. It is a groundbreaking platform that enables the creation of brain-inspired neural circuits. Our engineering team will be on hand to offer support throughout the course of these projects.

Importantly, all projects are fully open-source, so students are not required to sign NDAs or any IP ownership agreements. This allows them the freedom to publish their work and potentially continue contributing to the project thereafter.

### Integrating MuJoCo Physics Simulator with FEAGI for Real-Time Neuromorphic Control of Simulated Robots
Objective:

The primary objective of this project is to develop an integration between MuJoCo and FEAGI to demonstrate simple neuromorphic control of a simulated humanoid, focusing on maintaining its balance. As a stretch goal, implementing a walking mechanism will also be considered. This project involves developing a Python module that will interface with both MuJoCo’s Python SDK to interact with the simulated robot and FEAGI’s SDK and API to connect with the FEAGI platform. Sensory information will be captured from the simulator via the MuJoCo SDK, translated into neuronal activities using existing FEAGI modules, and transmitted to FEAGI. Additionally, motor commands generated by FEAGI will be converted into corresponding actions and sent to MuJoCo to control the simulated model. To demonstrate the functionality, a basic neural pathway will be created within the FEAGI platform to stabilize the model in an upright position. This pathway can later be extended to enable walking.


Background:
MuJoCo (Multi-Joint dynamics with Contact) is a powerful and widely-used physics simulator known for its ability to accurately model the dynamics of rigid bodies, making it ideal for robotics research. FEAGI, on the other hand, is an open-source framework designed to simulate artificial brains modeled after the human brain's structure and function. By integrating these two systems, this project aims to create a platform where neuromorphic AI can be tested and developed in realistic simulated environments, bridging the gap between brain-inspired AI research and practical robotics applications.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Integrating FEAGI with Webots for Advanced Neuromorphic Robot Simulations

Objective:

The primary objective of this project is to develop an integration between Webots and FEAGI to demonstrate simple neuromorphic control of a simulated robot arm, focusing on basic arm movements such as reaching and positioning. As a stretch goal, implementing more complex tasks, such as object manipulation, will also be considered. This project involves developing a Python module that will interface with both Webots' API to interact with the simulated robot arm and FEAGI’s SDK and API to connect with the FEAGI platform. Sensory information will be captured from the Webots simulation via its API, translated into neuronal activities using existing FEAGI modules, and transmitted to FEAGI. Additionally, motor commands generated by FEAGI will be converted into corresponding movements and sent to Webots to control the simulated robot arm. To demonstrate the functionality, a basic neural pathway will be created within the FEAGI platform to enable the robot arm to perform simple movements, such as reaching or positioning an object. This pathway can later be extended to handle more complex tasks, such as grasping, object manipulation, or executing a series of coordinated movements.

Background:

Webots is a versatile and widely-used open-source robot simulation platform that enables detailed modeling and control of robots in 3D environments. It supports various robot models and sensors, making it an essential tool for research, education, and development in robotics. Webots allows for realistic simulations of robotic systems, offering a safe and flexible environment to test and refine robotic behaviors before deploying them in the real world. This project integrates Webots with FEAGI, an open-source platform for simulating brain-inspired AI, to control a simulated robot arm using neuromorphic principles.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing a simple 3D TurtleBot Simulation with Swappable Maze Scenes and FEAGI Playground Integration in Godot Game Engine

Objective:

The goal of this project is to design and develop a 3D simulation of a TurtleBot robot that can navigate in a maze to reach a target. The bot will be equipped with distance sensors enabling it to detect its distance from walls. Integration with FEAGI will enable the simulated bot to navigate the maze based on motor commands received from FEAGI as a direct result of sensory data collected by the bot. The maze scenes should be swappable so the bot can be trained in mazes with various difficulty levels. As a stretch goal, the team will develop an AI model in the form of a neural pathway in FEAGI that can solve the maze.

Background:

TurtleBot is a popular platform used in education and research for exploring robot navigation and control. FEAGI (Framework for Evolutionary Artificial General Intelligence) is an open-source project designed to simulate brain-inspired AI models. The Godot game engine is an open-source, cross-platform game development tool known for its flexibility and ease of use. It supports both 2D and 3D game development, making it a popular choice for indie developers and hobbyists.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing an AI Model for Gesture Recognition Using FEAGI

Objective:

The objective of this capstone project is to design, develop, and train an artificial intelligence (AI) model within the FEAGI (Framework for Evolutionary Artificial General Intelligence) platform that can recognize and interpret simple human hand gestures in real-time. The project will focus on integrating sensory data (such as visual input from cameras) and using FEAGI’s neuromorphic architecture to detect and classify a set of predefined gestures to control game characters. Game integration is outside the scope of this project and will be provided to the team. As a stretch goal of this project, the team can attempt to recognize more complex hand gestures such as the ones used in ASL (American Sign Language).

Background:

Gesture recognition is a critical technology in human-computer interaction, enabling systems to interpret human motions as input. FEAGI, with its brain-inspired AI architecture, provides a unique platform to explore the neuromorphic approach to gesture recognition. By leveraging evolutionary learning techniques and the brain-inspired structure of FEAGI, this project will create a gesture recognition model capable of understanding human hand or body movements.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com)

### Developing a Neuromorphic Model for Imitation Learning Using FEAGI
Objective:

The objective of this capstone project is to design and develop a neuromorphic AI model using a deep Spiking Neural Network within the FEAGI platform to perform imitation learning. The focus will be on creating a brain-inspired model capable of observing and replicating actions performed by a human or a human-controlled game character and associating these actions with the embodiment connected to the model. The successful model will reliably imitate simple directional movements and effectively use these movements to learn how to play a 2D game leveraging Hebbian learning. 

Background:

Imitation learning is a powerful concept in artificial intelligence where an agent learns to perform tasks by observing the behavior of another agent or human. This method is particularly effective in scenarios where explicit programming is challenging or impractical. Neuromorphic computing, which mimics the structure and function of biological neural networks, offers a promising approach to developing AI systems that can naturally learn and adapt through imitation. FEAGI provides a flexible and scalable platform for implementing these neuromorphic models.

Team Size: 3-4 students

POC: Mohammad Nadji (nadji@neuraville.com) -->

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

<!-- ## Brad Hays 
### Wood Veneer Marquetry Artwork Generation
I'm a woodworker in my spare time, and for a while now I've been tossing around the idea of how photo mosaic-creating software could be used to create next-level marquetry artwork. Marquetry is a millennia-old image-creating process whereby thin veneers of wood are meticulously shaped to interconnect with each other and, when laid down like strokes from a paintbrush, assemble into an image whose realism and authenticity depends on the quality of the movements within each veneer piece, as well as the skill of the artisan.  Given the various color movements that occur in high-grade veneers, one should be able to cut many hundreds (thousands actually) of small wood squares and use them as 'pixels,' if you will, to create a larger 'target' image.  And because I have about as much artistic ability as a doorknob, I need some help getting this done, which is where the idea of a software-aided process comes into play.   

Project Goals: 
- Develop a software tool that can take a target image and a library of veneer images and generate a marquetry piece that can be cut out by a laser with fixed shapes and sizes.
- Develop a software tool to assist in the assembly of the marquetry piece by indicating where each piece should be placed in the final image.
- Develop a software tool that can generate arbitrary shapes based on a target need and library of available veneer.


Team Size: 4 students

POC: Brad Hays (bradleyheathhays@gmail.com) -->

# Computer Science Faculty Projects
## Daniel Mosse 
### StudentPaths and Concept Progression Maps Deployment
Intro: StudentPaths and Concept Progression Maps are data analytics tools designed to assist undergraduate academic advisors by finding trends in historical student data, matching current students to those historical trends, and exposing finer granularity detail for grades.  These tasks allow advisors to talk more in-depth with their students about their undergraduate careers and course content.

Currently, an MVP (minimum viable product, not most valuable player) for both tools have been developed and they're ready for deployment; students will:

1. Understand the previously written code, using existing documentation, and fill in any knowledge gaps in that documentation (ie, follow documentation, but write down what's missing/misleading)
2. Fix any bugs that are still outstanding to be able to run these tools on your own machine (ie, deploy local copy)
3. Deploy onto the cloud: must know or want to learn how to work with Microsoft Azure, and  Single Sign-On at Pitt (ie, deploy services on Azure and enable PittID authentication)
4. Work with PittIT to attach a data warehouse containing anonymized transcript information to use in StudentPaths (ie, hook up to a database)
5. Integrate the system with Canvas, by being able to extract course, assignment and grade data to use in the Concept Progression Maps system (ie, learn the Canvas API to get data for CPMs)
6. Test both systems to ensure they are working as intended
7. Create documentation to help future developers operate and maintain the code.
8. Time Permitting: Create documentation to help non-experts (i.e., advisors) run the system on their machine(s)

Students will be expected to work as a team to fulfill these requirements and meet with the clients on a weekly basis to ensure adequate progress is being made.

If you have any questions, please contact Nathan Ong (nro5@pitt.edu) or Daniel Mosse (mosse@pitt.edu).  Nathan is a post-doc at Pitt's LRDC+UCTL, Daniel is a faculty member in CS.  We will have weekly meetings.

Team Size: 2-3 students

POC: Nathan Ong (nro5@pitt.edu), Daniel Mosse (mosse@pitt.edu)

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
### Web-Configurable Bot for Discord
This project involves the development of a custom Discord bot and its accompanying management website, aimed at enhancing course communications. The bot will be designed for configurable commands and integration with educational platforms such as Canvas, enabling tailored interactions for students. Key tasks include developing the bot, establishing a web-based interface for configuration and control, and creating specific commands that certain students can invoke based on course integration. This project presents a unique opportunity for students interested in web development, backend programming, and interactive system design, offering a practical application in a real-world educational setting.
 

This work is on going from the last two semesters, so you will be working on an existing codebase. We will be working on some buggy behaviours, and enhancing its functionality!
  

Skills Required: Web development experience. No specific languages or frameworks enforced; current work using Python backend and JavaScript frontend. We can change!

Team size: 3–4 students

POC: Luís Oliveira (loliveira@pitt.edu)


### RF-based Ranging for Relative Localization
The focus of this project is to develop an application utilizing RF-based ranging technology for relative localization. The task involves working with Qorvo DWM3001CDK development kits, which are equipped with hardware capable of measuring distances based on wireless signals between devices. The primary challenge is to understand and utilize the manufacturer’s implementation examples to create a standalone application running on these boards. This application will not only measure distances between devices but also estimate their relative positions using a known technique for converting distances into positions.

Skills Required: Comfort with C programming and an interest in embedded systems; prior experience in this area is beneficial but not required.

Team size: 3–4 students

POC: Luís Oliveira (loliveira@pitt.edu)

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

Time Size: 2 students

POC: Nils Murrugarra-Llerena (nem177@pitt.edu)

## Scott Jordan
### Autonomous Driving from Human feedback for RC Cars
I have two remote controllable RC cars with cameras and Nvidia Jetson GPUs. I would like to develop a system for them that can be used to teach the cars to drive around various areas and race each other. The software for these systems needs work is simple and I would like to build out tooling that will allow for it to easily record user controlled demonstrations, run the cars autonomously, and be able to give feedback to the car on how well it is doing. I also need functionality developed to do some learning from demonstration to create a model that can be used to drive the car autonomously. There is lots of room for innovation in this project and to do both AI work and software engineering. If you are interested in AI, autonomous systems, or edge devices this could be a great project for you.

Team Size: 3-4 students

POC: Scott Jordan (scott.jordan@pitt.edu)


