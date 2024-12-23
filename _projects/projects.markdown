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

Team Size: 3-4 students

POC: Anastasia Mokhon (anastasia.mokhon@cgi.com)

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

Team Size: 3-4 students

POC: Praveen Sone (praveen.sone@cgi.com)

## Neuraville
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

POC: Mohammad Nadji (nadji@neuraville.com)

# Community and Other Organizations

## NOAA
### Machine Learning Based Predictive Modeling of Bacterial Pathogens with Stony Coral Tissue Loss Disease
In 2014, Stony Coral Tissue Loss Disease (SCTLD) was first observed in Virginia Key, Florida (Miller et al., 2016; Precht et al., 2016; Walton et al., 2018). The disease spread swiftly through Florida and is now in the Caribbean, making it one of the longest-lasting coral disease outbreaks. To date, SCTLD impacts at least 23 species of reef-building corals, significantly reducing coral diversity in an already vulnerable ecosystem (Precht et al., 2016; Walton et al., 2018). 

As with many coral diseases, the cause of SCTLD remains unclear. Preliminary research suggests that antibiotics may be effective in halting lesion progression (Aeby et al., 2019). This points to the possibility that the pathogen could be bacterial, or that secondary bacterial infections might significantly contribute to lesion development.  Studies to date have not identified bacteria consistently present across coral species (Rosales et al., 2023, Meyer et al., 2019).
To identify bacteria linked to disease, scientists often use differential abundance analysis to determine which bacteria are more prevalent in treated samples compared to controls. However, this method has faced criticism (Quinn et al., 2021). In the proposed project, students will explore alternative approaches to characterize the causative agent(s) of SCTLD. Instead of relying on differential abundance analysis, students will employ machine learning techniques on previously analyzed microbiome data (Rosales et al., 2023). They will use various machine learning classifiers to develop a predictive model aimed at identifying both primary and secondary bacterial pathogens associated with SCTLD.

Team Size: 2 students

POC: Stephanie Rosales (Stephanie.Rosales@noaa.gov)

## Pittsburgh Radio Rosary and Consecration
### Pittsburgh Radio Rosary and Consecration Interactive Prayer Service
The Pittsburgh Radio Rosary and Consecration (PITTRRC), Inc. provides a daily 7 pm scriptural Rosary and Sacred Heart prayer of Consecration radio broadcast on WKHB at 620 am and transmits on 92.3, 94.1, and 102.1 FM. This broadcast, a tradition for over 50 years in the Pittsburgh region, has been a source of spiritual connection and unity. In April 2022, PITTRRC assumed the ministry's rights and responsibility; now, we are ready to take it to new heights. PITTRRC created a new audio production in July 2022, and we want to enhance the ministry with a unique prayer-based interactive website and YouTube channel. This technological capability with the website will allow anyone to pray together or independently, educate, and communicate with one another in faith. This website would be unconventional by design, offer interactive prayer, and go beyond a standard text-only WordPress site.

[More information]({{site.baseurl}}/projects/pdfs/PITTRRC_F2024.pdf)

Team Size: 3-4 students

POC: John DePasquale (jbdepasquale@msn.com)

## Midwife Sally
### Facebook educational tool for pregnant women in Ghana
The [Midwife Sally organization](http://mymidwifesally.com/) offers pregnancy-related educational content to over 200,000 [followers](https://www.facebook.com/MidwifeSallygh/); mostly pregnant/trying to conceive women. Though the founder, Ruth Sally Kodam, is based in Ghana, her reach has now extended to Nigeria, Zambia, the UK and the United States. After taking some of Sally’s private classes, several women will post about how Sally’s course helped them during labor (see attached example). These women often leave a “digital trail” on Sally’s facebook page. 

We would like to: 
1. quantify these testimonials using NLP or ML. So the references are usually “midwife sally, your class taught me….xyz”
2. Create a midwife sally intake and outtake form, where participants can review the course and tell us the knowledge gained. The form, if designed to collect longitudinal data, will be great! The data can be analyzed in the future too, to evaluate maternal/infant/birth outcomes.
3. Develop a "geo location" tool that pregnant clients can use to search for the nearest hospital and associated reviews. 


Team Size: 3 students

POC: Martina Anto-Ocrah (MAA509@pitt.edu)

## Brad Hays 
### Wood Veneer Marquetry Artwork Generation
I'm a woodworker in my spare time, and for a while now I've been tossing around the idea of how photo mosaic-creating software could be used to create next-level marquetry artwork. Marquetry is a millennia-old image-creating process whereby thin veneers of wood are meticulously shaped to interconnect with each other and, when laid down like strokes from a paintbrush, assemble into an image whose realism and authenticity depends on the quality of the movements within each veneer piece, as well as the skill of the artisan.  Given the various color movements that occur in high-grade veneers, one should be able to cut many hundreds (thousands actually) of small wood squares and use them as 'pixels,' if you will, to create a larger 'target' image.  And because I have about as much artistic ability as a doorknob, I need some help getting this done, which is where the idea of a software-aided process comes into play.   

Project Goals: 
- Develop a software tool that can take a target image and a library of veneer images and generate a marquetry piece that can be cut out by a laser with fixed shapes and sizes.
- Develop a software tool to assist in the assembly of the marquetry piece by indicating where each piece should be placed in the final image.
- Develop a software tool that can generate arbitrary shapes based on a target need and library of available veneer.


Team Size: 4 students

POC: Brad Hays (bradleyheathhays@gmail.com)

# Computer Science Faculty Projects
## Daniel Mosse 
### Cutting-edge research in NLP
The project will be focused on extracting course concepts from course presentations using a state-of-the-art tool called DS-MOCE. The students are expected to gain experience in the following:

Annotation of Data for Model Training (this is the input to the NLP model) (25% effort)
Read the documentation and papers describing DS-MOCE, a state-of-the-art Course Concept extraction tool, to understand how the tool works, what inputs are needed, how to run it, expected results, etc. (10% effort)
Work with, modify as needed, install packages needed by the tool, and run the (research) code to benchmark its performance on a variety of inputs. (50% effort)
Analyze the results, and draw conclusions. (15% effort)

The project will be supervised by Prof Daniel Mosse and PhD student Raja (RJ) Krishnaswamy.

Team Size: 2 students

POC: Daniel Mosse (mosse@pitt.edu)

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

A key issue shared by the returning community members is that they struggle to figure out what resources are available near them. This is a structural problem. We do not have a well-curated list of local resources, and most of the lists that have been created are seldom verified. More critically, these resources are not presented in a way that informs people how they can use them for the goals that matter to them. To attend to this issue, we want to build a system that enables people to do the following:
1. They draw out (using public images and videos) a vision of a successful future (say, 3 years or 5 years from now).
2. They reflect on where they stand right now.
3.  Following the reflection, they chart an action plan detailing what they may need to do to realize those goals.
4. Using [findhelp.org](http://findhelp.org/), they connect to some of the local resources they can access as part of their action plan.

This project is new. We are beginning this project from scratch. This means that you will wireframe design ideas, iterate on them, and finally implement a prototype on React.


Technology requirements:

Since the main website is built using React, students need to have some proficiency in Javascript and React. In addition, students will need to work on Figma so it will help if they already are familiar with or are willing to learn Figma.

Team Size: 3-4 students

POC: Aakash Gautam (AAKASH@pitt.edu)

## Luís Oliveira
Note: Only one of these projects will be picked.

### Web-Configurable Bot for Discord
This project involves the development of a custom Discord bot and its accompanying management website, aimed at enhancing course communications. The bot will be designed for configurable commands and integration with educational platforms such as Canvas, enabling tailored interactions for students. Key tasks include developing the bot, establishing a web-based interface for configuration and control, and creating specific commands that certain students can invoke based on course integration. This project presents a unique opportunity for students interested in web development, backend programming, and interactive system design, offering a practical application in a real-world educational setting.
 

This work started last semester, so you will be working on an existing codebase. We will be working on some buggy behaviours, and enhancing its functionality!
  

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

Team Size: 3 students

POC: Nadine von Frankenberg (vonfrankenberg@pitt.edu)

### TeachTech Toolkit
"TeachTech Toolkit" aims to enhance teaching and learning workflows by integrating tools, including Canvas and Gradescope, along with the setup of GitHub projects. It aims to create a cohesive workflow that facilitates efficient assignment distribution, grading, and feedback, while also incorporating practical aspects of software development, such as version control, test case development, and API interaction. You will be defining workflows and implement small applications throughout the project.

Team Size: 2 students

POC: Nadine von Frankenberg (vonfrankenberg@pitt.edu)
