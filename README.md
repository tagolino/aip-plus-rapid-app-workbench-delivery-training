# AIP+ Introductory Training <!-- omit from toc -->

## Resource reference <!-- omit from toc -->
TODO

## Table of Contents <!-- omit from toc -->
- [General Training](#general-training)
- [Rapid Application Workbench Delivery](#rapid-application-workbench-delivery)

# General Training
1. TODO

# Rapid Application Workbench Delivery
- #### Courses
  - ##### AIP+ Onboarding Deck
    - This course is an overview of AIP+ processes, access requests, training, and helpful tips.
    - AIP means Applied Intelligence Platform +
    - Key KPI is "Speed to insight"
    - Mission: To curate the IP (Intelligence Platform?) of our partners and make that IP consumable
  - ##### Introduction to AIP+
    - This training will provide a high-level overview of the AIP+ Execution Engine and AIP+ Rapid Application Workbench, including basic fundamentals and key benefits of AIP+.
    - GDPR: General Data Protection Regulation
    - CDP: Client/Customer Data Protection
    - What is AIP+ Rapid Application Workbench? AIP+ Rapid Application Workbench is our accelerator to rapidly develop industry relevant applications to deliver outcomes. It is an application development environment with page definition framework that makes it easy to create applications around predictive and forecasting analytical models.
    - Why AIP+ Rapid Application Workbench? The AIP+ Rapid Application Workbench reduces development complexity and speeds up time-to-market by re-using pre-built code-fragments, graphical widgets, data and analytic models for common business scenarios. AIP+ Rapid Application Workbench delivers more than 50 pre-built applications for various industries and domains and draws on Accenture's industry expertise and vertical solutions.
  - ##### AIP+ Technical Architecture
    - This course is an overview of AIP+ Technical Architecture.
  - ##### AIP+ Support
    - This course is an overview of Engineering, Enablement, and Support (L1, L2, L3).
  - ##### Annual Client Data Protection Training 2021
    - The Annual Client Data Protection Training course provides guidance on various topics such as creating a strong CDP plan with controls that mitigate risk, keeping client information safe and role specific responsibilities.
  - ##### AIP+ Security Compliance
    - This course is an overview of AIP+ Security, HITRUST, FedRAMP, and other AIP+ certifications.
  - ##### Data Management in AIP+ Rapid Application Workbench
    - This self-study AIP+ Rapid Application Workbench course will introduce the data management capabilities of AIP+ Rapid Application Workbench. Through presentations, video demonstrations and hands-on exercises using the Rapid Application Workbench platform, course participants will learn the necessary skills to map the data model based on business requirements and configure the data model within the AIP+ Rapid Application Workbench framework.
    - Entities
      - Like tables, models, business objects etc.,
    - Relations
      - Connections
      - Cardinality
    - Attributes
      - Fields
    - Modules:
        1. Case Study Introduction
            - Telco International
        2. Data Model Configuration
            - Configuration files
            - 2 options for exporting/downloading configuration files
              1. Configuration templates
                  - Blank importer templates
              2. Current configuration
                  - Pre populated with current configs
        3. Instance Data Management
            - Loading of data
            - 2 steps to load data:
                1. Loading main entity instance data
                2. Loading relation entity instance data to establish relations between main entity instances.
        4. Key points:
            - Once the ACN team has determined the client's needs and mapped the data model, the team will begin creating an app by configuring the data moedl in Tapod Application Workbench.
            - To configure the data model, developers first create entities, of which there are three types:
                1. Main
                2. Component
                3. Relation
            - Main entities, which are created first, represent business objects (real or abstract) involved in a business process.
            - Entities establish the framework for a business process. Later, the creation of instances will allow users to enter data for analysis.
            - Relation entities represent the connection or logical link that connects other entities.
            - When defining a relation entity type, developers will define the source and target entities as well as cardinality.
            - In order to store data within each entity, developers must create attributes.
            - Each attribute has a defined set of properties that define how the data for that attribute will be entered, tracked and displayed. These properties can be set using the attributes tab of the EntityType importer template.
            - Loading instance data brings your app to life by materializing the entities, relations, and attributes that you created when you configured the data model.
            - You download an instance importer template through the Instance Management activity on an entity page.
            - Rapid Application Workbench will dynamically generate an importer template that contains field headers for each attribute that you have previously defined for the relevant main entity. You will add instance data by completing this template and importing it back into Rapid Application Workbeanch.
            - Similarly, the importer template for relation entity instance data is downloaded through the Instance Management activity, which is accessed from the page of the main entity that is the source of the relation.
            - For each relation instance, you will define an ID, Name, Description, The IDs of the source and target main entity isntances you want to link, and any additional attributes you have defined for the relation entity type.
  - ##### App Design & Development in AIP+ Rapid Application Workbench Editor
    - This 8.5 hour self-study course will bring you up to speed on AIP+ Rapid Application Workbench’s basic functionality and configuration options.
  - ##### Code Development in AIP+ Rapid Application Workbench Editor
    - This self-study AIP+ Rapid Application Workbench course will introduce the basic code development functions and features available in Rapid Application Workbench Editor. Through presentations, video demonstrations and hands-on exercises using the Rapid Application Workbench platform, course participants will learn the necessary skills to create and edit code to reflect desired business logic for an app in Rapid Application Workbench Editor.
  - ##### AIP+ Rapid Application Workbench Functional Design
    - This course on app development and delivery will allow you to understand the steps required to properly develop and deliver an app from a functional perspective.
  - ##### AIP+ Rapid Application Workbench Predictive and Forecasting Applications
    - TODO
  - ##### Architectural Design
    - At the end of the course, you will be able to ask the necessary questions to build a proper AIP+ Rapid Application Workbench architecture and related sizing estimate.
  - ##### Visual Modeler
    - At the end of the course, you will be able to demonstrate the basic features of Visual Modeler.
