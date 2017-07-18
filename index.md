## Welcome to Technology Fundamentals of Business Analytics
This page is designed to include the details of the semester. You should always look at the latest version here and not download this offline.  First here are a list of useful links:

- [Syllabus, Presentations, Notebooks, Docker Container for Data Science](https://github.com/AnalyticsDojo/materials) are located in the /AnalyticsDojo/Materials repository.
- [RPI LMS (Blackboard)](https://lms9.rpi.edu) should be used to submit all assignments. 
- [Piazza](http://piazza.com/rpi/fall2016/mgmt6963) should be used for problems with course assignment and communications with instructor.
- [Chat](https://gitter.im/AnalyticsDojo/rpi) with other students regarding analytics.
- [rpi.analyticsdojo.com](http://rpi.analyticsdojo.com) will be used for much of the content etc. 
- [Microsoft Azure Machine Learning](https://studio.azureml.net)

## Office Hours and Contact Information
Jason Kuruzovich (Instructor)    
- Email: kuruzj - at - rpi.edu [Prefer contact via Piazza](http://piazza.com/rpi/fall2016/mgmt6963)
- Office Hours:  Thursday 9:30 - 12:00 and by appointment *If office hours get crowded I'll be in SA lounge.*
- Office Location: Pittsburgh 4108 (Located in the Severino Center)

Sukruth Suresh (TA)
- Email: suress - at - rpi.edu  
- Office Hours: Tuesday 2:00 - 4:00 and by appointment
- Office Location: Pittsburgh 4304

Assignments from one class will be due the following Wednesday by 11:59 PM.  This allows for an time to ask about an assignment.  Per the syllabus: 

*After the add deadline, assignments up to 24 hours late will have their grade reduced by 25%; assignments up to one week late will have their grade reduced by 50%. After one week, late assignments will receive no credit. Please turn in your assignment early if there is any uncertainty about your ability to turn it in on time.*

**Pre-class Checklist**

1. Synchronize the /AnalyticsDojo/materials repository.  
2a. (Azure Option) If using Azure, upload the appropriate files for the class.  That way you will have quick access for the exercises.  
2b. (Docker/Anaconda) If using Docker or Anaconda make sure that that Docker or Anaconda are running and you can execute a Jupyter notebook.


|    | Date   | Topic                                    | Readings/Content/Assignments                                                                           |
|----|--------|------------------------------------------|------------------------------------------------------------------------------------|
| 1  | 29-Aug | The Rise of Analytics                    | [Click Here](https://gist.github.com/jkuruzovich/672945f488de09dee47010a6f3f343ba) |
|    | 5-Sep  | Labor Day                                |                                                                                    |
| 2  | 12-Sep | Intro to Python                          | [Click Here](https://gist.github.com/jkuruzovich/6cc69cda7778fa58c66ac3da0bd2ce39) |
| 3  | 19-Sep | Intro to Python (continued)              | [Click Here](https://gist.github.com/jkuruzovich/f55f10c4e8dee3e137fec4be06c58e91) |
| 4  | 26-Sep | Intro to R                               | [Click Here](https://gist.github.com/jkuruzovich/8190532832731f26252a43abd4a43d7d) |
| 5  | 3-Oct  | Intro to R (continued)                   | [Click Here](https://gist.github.com/jkuruzovich/aa5c5dbd1a8030f0795c6155427447a6) |
|    | 10-Oct | Columbus Day - No Class                  |                                                                                    |
| 6  | 11-Oct | Intro to Visualization                   | [Click Here](https://gist.github.com/jkuruzovich/6072f9b59cda03d5303e31b47553f360) |
| 7  | 17-Oct | Data Munging                             | [Click Here](https://gist.github.com/jkuruzovich/c2a8e97cd697abb0c61f34862a9c0a27) |
| 8  | 24-Oct | Midterm                                  | [Click Here](https://gist.github.com/jkuruzovich/b0455882989062c329f7d96124e5818e) |
| 9  | 31-Oct | Introduction to Modeling I               | [Click Here](https://gist.github.com/jkuruzovich/bedf36300cec584aec47d3873ec361f8) |
| 10 | 7-Nov  | Introduction to Modeling II              | [Click Here](https://gist.github.com/jkuruzovich/65268fc7d45519c828ec4a5ae0ae2a73) |
| 11 | 21-Nov | Systems Thinking and Analytics           | [Click Here](https://gist.github.com/jkuruzovich/9b6a0d89d9edb7bc0f8b243cb5143b84) |
| 12 | 21-Nov | Text Mining and Unstructured Data        | [Click Here](https://gist.github.com/jkuruzovich/a78ca939dea78fe0893e258178f6d96b) |
| 13 | 28-Nov | Introduction to Big Data with Spark      | [Click Here](https://gist.github.com/jkuruzovich/936d214689c6077bc11bb35e775afca5) |
| 14 | 5-Dec  | Presentations                            |                                                                                  |
| 15 | 19-Dec  | Final Exam (Comprehensive 6:00 - 9:00 PM)  |  [Click Here](https://gist.github.com/jkuruzovich/f8c5530da365a45678ea6dce9d863a38)                                                                                   |

<br>
## Project Assignment

###  Project Objective 
The overall goal is to undergo all stages of the data understanding, data munging, modelling, and further development of understanding.  

### Project Selection 
There are a tremendous number of potential [Kaggle](https://www.kaggle.com) projects available that would make excellent selections.  However, with this assignment, you can do something on your own like [teach a deep learning network to recognize brands on twitter](http://www.slideshare.net/ukaszCzarnecki/brand-recognition-in-reallife-photos-using-deep-learning-lukasz-czarnecki-pydata-berlin-2016) or work with an organization with a data oriented problem.  The proposed project should be described in a 1 page overview and approved by the instructor.  

The project must include these characteristics:
1. Problem context which is business focused.  As this course is a foundational course for the business analytics program, datasets related to pure science or toy problems like the Titanic should not be used.  
2. The dataset must be adequately complex to provide an interesting learning experience for the student and the class.
3. The dataset must have a predictive objective (not just visualization) that should be clear at the outset of the process.
 
### Deliverables
The overall deliverable will be a report which explains all of the relevant componets of the CRISP model for the identified dataset.  The report should have the sections below.  Where relevant, specific code should be shown in a blog-like fashion which describes the code used, its function, and where appropriate includes outcomes.   

1. *Introduction of problem and context.* This section should provide an overview of context as well as the nature of the prediction problem. 
2. *Data description and initial processing.* This section should provide a detailed overview of the data and provide initial characterization of basic staticstics, creation of simple visualizations, and describe any processes completed to clean/transform the data for processes.  
3. *Modeling.* Describe the techniques utilized to model the data, providing adequate background.  Several models should be tried (minimum of 3) so that they can be evaluated relative to one another.  
4. *Evaluation.* Results of modeling should be clearly presented in a table for evaluation. Evaluate the relative predictive outcome of each modeling effort using appropriate evaluation matrics.  
5. *Summary.* Provide a short summary of techniques learned.
6. *Appendix* Provide executable code in either R or Python.

### Project Evaluation Metrics.  
The description below descripes an ideal project.  Projects will be evaluated subjectively by the instructor according to this rubric.  
- *Formatting (10 points).* The student presented the report in a format that indicated professionalism and care in the organization, writing, and presentation of the overall report. 

- *Introduction of problem and context (15 points).*  The student was able to present the problem and context in a way that is rich and interesting, incorportating relevant outside resources with adequate citations. They demonstrated a great understanding of the problem context and of the specific modeling problem itself. 

- *Data description and initial processing.(15 points).* The student was able to clearly present an overall picture of the data.  This includes basic structure field by field descriptions as well as visualization and basic statistics. Where necessary they have adequately used techiques for cleaning the data. 

- *Modeling (15 points).* The paper indicates was able to generate different models which were described in a series of blog-like posts.  The predictive po, submitted to Kaggle, and compared. 

- *Evaluation and Summary (15 points).* The predictive characteristcs of the different models are clearly compared in a table with appropriate conclusions.  

- *Code (10 points).* The appendix contained well organized and documented code.  

- *Presentation (20 points).* The context, data, modeling, and conclusions are clearly described in a 5-7 minute presentation.  Slides are clear and readable.  Content is customized for slides not just copied from the report.  Presentation is clear and understandable.   

### Project Schedule 
1. *28-Sept (or before).* A 1 page proposal due. This should include a very short description of the context, data, and the goal of the modeling.  This is ungraded but can be incorporated into final report.
2. *26-Oct (or before).* Manditory 1st check-in with instructor/TA. 
3. *16-Nov (or before).* Manditory 2nd check-in with instructor/TA.
4. *5-Dec (or before).* Final project presentations.  
5. *7-Dec (or before).* Final reports. 

<br>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<br>
## Tutorial Assignment

There are so many different things to learn related to data science. For this assignment you are required to select some interesting component that can be presented clearly to the class in less than 5 minutes and using 1 Jupyter Notebook or blog post.  
