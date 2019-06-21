
                                           Izmir University of Economics
                                                 2018-2019 Fall
                                     SE 360 Project Report İNAN EVİN - ALPER ÖZER
The Course Analyzer at it’s first stages, functions as a management application for university courses. It provides a basic user interface where the end user is able to register and edit number of courses, along with their syllabus data and exams. Course Analyzer also provides a number of tools to observe the result of attendance and exam data about a particular course. Some of the significant functions of Course Analyzer is given below.
- Provides interfaces for adding, removing, duplicating courses, along with their relative data. These data includes course and section information.
- Provides interfaces for editing the syllabus of a given course. The user is able to determine the start and end dates of the syllabus, that will automatically be converted into weeks. These weeks are editable by the user in the means of selecting the corresponding learning outcomes and related topics.
- Provides an interface in order to load student data from an Excel sheet in .xlsx format. This data is later used for attendance metrics.
- Provides interface for editing exams. The user is able to add different types of exams; midterm, final, quiz, lab or other. The exam date can be specified if the user wants to report data about attendance & exam relationship.
- Provides interface for loading a bulk of exam questions with their results, including the student information. This data again is loaded using Excel sheet, and question information, along with their max points & points per student are automatically added.
- Provides a reporting interface in which user can see attendance, topic success, grade and exam related data.

 The backend system of Course Analyzer is highly correlated with its front-end. It has a central UI manager that is responsible for calling the shots as well as receiving results and updating itself to show relevant data. The whole structure mainly revolves this central UI system and another manager which is responsible for managing the instances and all the included data for the courses.
For most of the data storage, basic data types along with ArrayLists and LinkedHashMaps are used. There are a lot of objects and their data that needs to be saved for file save and load, so most of the classes implement Serializable interface.
We had used several libraries to handle some tasks. Most relevant ones are Apache POI, to handle .xlsx reading and Xcharts to show related information as charts.
