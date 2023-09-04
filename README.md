# MODEL-BASED-LIFE-CYCLE-WITH-MATLAB-SIMULINK
# **WELCOME!**

The following material is aimed at engineering lecturers who want to teach skills about Life Cycle management of energy systems using Model-based Systems Engineering. This material was developed by [Mondragon University]([https://www.mondragon.edu/en/home](https://www.mondragon.edu/en/-/estudiantes-docentes-master-sistemas-inteligentes-energia-mathworks-material-didactico)) in collaboration with MathWorks for the [MSC in Smart Energy Systems](https://www.mondragon.edu/en/master-degree-smart-energy-systems).

This master curriculum has been designed based on the development of an electric scooter on which the students have worked during their previous degree in Energy Engineering. Taking advantage of their knowledge about the scooter, students can work on new skills related to requirements, architecture and validation of complex systems. Material in this repository covers 30 hours of classroom work plus 20 hours of homework.

<img src="https://github.com/MU-MATHWORKS/MODEL-BASED-LIFE-CYCLE-WITH-MATLAB-SIMULINK/assets/109138609/77087dc5-6dfe-4f8a-92df-740dab71ac7b" width=50% height=50%>

If you want to see what it's all about at a glance, read this [presentation](https://github.com/MU-MATHWORKS/MODEL-BASED-LIFE-CYCLE-WITH-MATLAB-SIMULINK/blob/main/Miscellaneous/Subject%20introduction%20and%20description%20for%20teachers.pptx) or watch our presentation video.

https://github.com/MU-MATHWORKS/MODEL-BASED-LIFE-CYCLE-WITH-MATLAB-SIMULINK/assets/109138609/df6985d6-7669-474d-bc22-99de98604dab

# **TABLE OF CONTENTS**
- [How to use this repository](#how-to-use-this-repository)
- [Tools](#tools)
- [Learning outcomes](#learning-outcomes)
- [Resources](#resources)
  - [Academic Material](#academic-material)
  - [Miscellaneous Material](#miscellaneous-material)
- [Notes](#notes)
 
# **HOW TO USE THIS REPOSITORY**

This repository was created from a MATLAB project. Therefore, **the complete repository must be downloaded so that all the files are still linked.**

The project is opened in MATLAB double-clicking MODELBASEDLIFECYCLEWITHMATLABSIMULINK.prj.

# **TOOLS**
This material was created with MATLAB R2022a and the [Campus-Wide License](https://www.mathworks.com/products/matlab-campus.html) of MATLAB & Simulink.

Minimum requirements: MATLAB, Simulink, Requirements Toolbox, Simulink Test, System Composer.

The module related to [validation](#phase-9-validation) includes material and a coursework about Hardware-in-the-Loop (HIL) testing. Students build a HIL platform using two Texas Instruments Launchpad f28379d boards. This part of the curriculum requires additionally: Embedded Coder, Matlab Coder, Stateflow, Embedded Coder Support Package for Texas Instruments C2000 Processors.

# **LEARNING OUTCOMES**
The learning outcomes for this curriculum are:
  - Managing the life cycle with the V-model and model-based techniques, and recognising the MBSE’s ability to facilitate traceability.
  - Writing and managing requirements with MATLAB Requirements Editor.
  - Composing system architectures and organising system components with System Composer.
  - Arranging verification and validation tests against system requirements with test harnesses and test suites.
  - Developing and validating Hardware-in-the-loop testing platforms.

This material may be included in the following courses:
- Modelling and simulation of electronic, robotic, mechactronic and energy systems.
- Control engineering.
- Rapid prototyping, testing and validation.
- Application specific courses such as electric drives, electric energy generation and distribution, electromobility...
        
# **RESOURCES**

## **Academic Material**

This repository contains educational material with explanations of Life Cycle Management and Model-based Systems Engineering (MBSE)
of energy systems using MATLAB & Simulink.

The folders are organised following the V-model for Life Cycle management (in phases). Moreover, all files and folders are organised in a MALTAB project.

![figures](https://github.com/MU-MATHWORKS/MODEL-BASED-LIFE-CYCLE-WITH-MATLAB-SIMULINK/assets/109138609/6f1f1897-a605-4e12-be16-4723e0da5cb5)

### **Introduction**
Introduction to the subject. The content includes a document describing the key concepts about MBSE, V-model and simulation environments. From this document, a presentation was created to explain these main concepts in class.

### **PHASE 3 Requirements**
Module about requirements writing and management. The goal of this module is to explain the importance of requirements in the development of complex systems. Students will be introduced to different types of requirements and the characteristics of a good requirement will be explained. Lecturers can practice on writing requirements.

In the practical part, students work on writing and organizing requirements in Simulink Requirements. For this purpose, a brief manual on the most important aspects of this tool has been developed. As a final task, the students have to write the requirements for the scooter motor, organize them in the Requirements Manager and submit them.

This module contains:
- docs: Presentations to use in class about requirements writing and requirements management in MATLAB.
- motorRequirementsExercis: Requirements exercise.
- requirementFiles: Requirement sets in MATLAB.
  
### **PHASE 4 Architecture**
Module about architecture management. Material has been developed to analyze what an architecture is, when it is necessary to use it and what types of views exist. In the MATLAB & Simulink environment architectures are designed in System Composer, so the most important features have been summarized in a presentation. 

Moreover, the material for a coursework about architecture design of the electric scooter has been developed. Starting from a requirements document given by the lecturer, students have to design an arquitecture that meets the requirements and link them to the System Composer architecture model. Apart from that, they have to link the [behavioural model](phase-5-design) to the architecture model.

The repository includes two example architectures for the scooter linked to requirements and behavioural models.

Specifically, this folder contains:
- docs: Presentations to use in class about architecture management and System Composer in MATLAB. Architecture coursework material.
- architectureModels: Architecture models in System Composer.
- stereotypes: Stereotype sets.

### **PHASE 5 Design**
Electric scooter controller design model. This folder contains a behavioural model for designing the scooter's traction control. This model has been given to the students, since it is not the objective of the curriculum to work on the detailed design of the system. They have to link the behavioural model to requirements and the arquitecture.

This folder contains:
- docs: Scooter routes to test in simulate scooter's traction system.
- behaviouralmodels: Controller Simulink simulation models.
- scripts: Control initialization scritps.
- results: Route simulation results.
  
### **PHASE 9 Validation**
Module about verification and validation. It contains:
- docs: Presentations to use in class about Simulink test and Hardware-in-the-Loop platform development exercise.
- realTimeModels: Real time models in Simulink for HIL platform implementation.
- scripts: HIL platform initialization scripts.

This module has two main parts. On the one hand, presentations and examples have been created to work on the use of Simulink Test. The way to validate using the V-model is presented. On the other hand, material for a coursework about Hardware-in-the-loop testing has been created. Students build a HIL platform using two Texas Instruments Launchpad f28379d boards to test the controller of the scooter in real time. They have to adapt the simulation behavioural model for real time execution and compare Model-in-the-loop results with the HIL results.
  
## **Miscellaneous Material**
Miscellaneous material includes:
- Summary presentation about this curriculum.
- An article published at [SAEEI23](https://www.saaei.org/ediciones/edicion2023/) conference.
- Exercise solutions.
- Evaluation rubrics and student submissions.

## *Notes*
The repository was created from a Matlab Project. Apart from the aforementioned folders, additional files and folders can be found. All are needed for the correct execution of the project:
- work: The project stores automatically in this folder all the information generated during the execution of Simulink models.
- resources: This folder includes files for the definition of the project in XML files whose format is subject to change.
- shutdown.m: scripted executed when the project is closed. Workspace cleaning tasks.

# **Mondragon University in collaboration with MathWorks**
https://www.mondragon.edu/en/-/estudiantes-docentes-master-sistemas-inteligentes-energia-mathworks-material-didactico
