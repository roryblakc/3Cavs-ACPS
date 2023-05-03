# Effects of the COVID-19 Pandemic on Adolescents in Albemarle County Public Schools
Funded by 3Cavaliers, University of Virginia (2021-2023)

Tara Hofkens, Ph.D. (Education and Human Development)  
Brian Wright, Ph.D. (School of Data Science)  
Richard Stevenson, M.D. (School of Medicine)  

## Project Overview

This project uses education and medical data to examine how behavior, achievement, learning problems, and mental health changed during the period of remote instruction (2020-2021) and return to in-person instruction (2021-2022), compared to the school year before the pandemic (2018-2019) among Albemarle County Public middle and high school students. The long-term goal of the project is to lay the foundation to apply for external funding to develop the [Virginia Child Data Core (VCDC)](https://github.com/roryblakc/3Cavs-ACPS/edit/main/README.md#future-work-virginia-child-data-core-vcdc), a relational database that integrates education and medical record data in order to better capture the state of children and adolescents’ well-being in communities, and to intervene more effectively to optimize their learning, development, and mental health. 

### School Closures during the COVID-19 Pandemic

During the 2020-2021 school year, adolescents’ social interactions with people outside of their households was limited. Closing schools not only isolated students from their friends and extra-curricular activities, it also removed 55 million children and teenagers from being able to access support provided by teachers and staff.

### Partnership with Albemarle County Public Schools (ACPS)

Since Fall 2020, we have been working with partners at ACPS to better understand how remote schooling has impacted students’ well-being and mental health. Through interviews and surveys completed during remote instruction, they learned that 83% of parents, 73% of students, and 100% of teachers felt concerned about students' social and emotional well-being and mental health.  Students reported that they were worrying more, felt isolated from teachers and peers, and felt an increased sense of burnout from school. Adolescents of different ages may be differentially impacted, as they have different developmental needs and skills. Also, adolescents from low-income families and/or families who are marginalized may be particularly impacted; they are more likely to have experienced trauma, suffer from depression or anxiety, and may have fewer resources and support to manage the challenges of remote schooling.  

The aim of our project was to leverage education and medical data to better track and study trends across the pandemic, and to examine differences among students of different ages and from different socioeconomic and racial/ethnic backgrounds.  

### Interdisciplinary Team

**School of Education and Human Development.** The School of Education and Human Development is internationally known for field-leading research in the role of the school environment on child and adolescent development. Dr. Tara Hofkens, a professor in the Center for the Advanced Study of Teaching and Learning, applied her expertise in applied development and learning science to operationalize behavioral and learning challenges in the education data, and to connect the education and medical record data to support a database that captures these challenges across contexts.  

**School of Medicine.** The Department of Developmental Pediatrics are experts in research, assessment, and clinical care for children and adolescents experiencing learning, behavior, or mental health challenges. Dr. Richard Stevenson worked with a medical fellow, Dr. Joshua Reyes, to operationalize the potential behavioral, learning, and mental health challenges that adolescents have been facing, and to contextualize these challenges in their clinical observations of families seeking treatment for their children.  

**School of Data Science.** Faculty and students in the School of Data Science have extensive expertise in analyzing complex and longitudinal data. Dr. Brian Wright led a team of graduate students to build databases and integrate and analyze the education and health data.  


## Data & Analysis

### Education Data

We received 4 years of administrative record data that encompassed data from all secondary (middle and high) school students for the school year before the pandemic (2018-2019, Epoch 1), the school year during which the pandemic started (2019-2020), the period of remote instruction (2020-2021, Epoch 2), and year in which students returned to in-person instruction (2021-2022, Epoch 3). To maintain student confidentiality, the outcome data was shared in separate files (course grades, attendance in all class periods, and disciplinary records). Each data set included the same set of descriptive variables that would enable us to examine  differences of interest (e.g., student age/grade, race/ethnicity) and control for relevant student characteristics (e.g., special education status, achievement history), without identifying specific students.  

In total, we received data on 11,520 ACPS middle and high school students. We worked with ACPS data staff to understand the data and to review any relevant policies or procedures that changed or were eliminated or introduced over the 4 years of data that they collected. Understandably, a number of changes took place during the academic year that the pandemic began (2019-2020) that would make interpreting the data in comparison to the other years difficult. For this reason, we did not include that year in the the analyses and instead focus on differences from before the pandemic (Epoch 1), the period of remote instruction (Epoch 2), and the year returning to school (Epoch 3). Click here to be directed to our preliminary results.  

### Medical Record Data

Using a combination of systematic and strategic data extraction, we gathered records for children and adolescents, age 11-19, living in Albemarle County who had records in the EPIC medical record system over similar periods of time (9/2018-7/2022). Specifically, we systematically pulled all encounters, diagnoses, and medications that relate to internalizing and externalizing mental health challenges (e.g., anxiety, depression, OCD, PTSD) and learning problems (e.g., ADHD), and then completed chart reviews and pulled relevant referral and treatment notes. The resulting database includes records from 2,705 individuals who live in the county and who are in the appropriate age-band for attending middle or high school in the county public schools.  

Future analyses will examine the use and prevalence of health services for mental health problems and learning difficulties across the COVID epochs, and differences by age, race/ethnicity, and medicaid eligibility (socioeconomic status indicator). We also plan to aggregate and integrate both sets of data at the age/grade level to examine patterns in both types of data.  

## Future Work: Virginia Child Data Core (VCDC)

Education and health care systems capture critical information about children and adolescents’ functioning in multiple contexts. Integrating education and medical record data can enable us to better capture the state of children’s well-being in communities, and to intervene more effectively to optimize individual children’s development. Furthermore, partnering with districts and health care providers to identify and assess the needs of children in these systems can contribute to effective innovation and translational research to optimize health and the well-being throughout the Commonwealth.  

Virginia Child Data Core (VCDC) will be a relational database that integrates education and medical record data in order to: (1) examine student mental health and other indicators of psychological well-being across school and medical contexts; (2) examine patterns and predictors of children and adolescents accessing the health system for mental health, behavioral, and learning problems.  

The Virginia Child Data Core (VCDC) will build on the collaboration between EHD, SDS, and SOM to develop a longitudinal relational database that connects education and medical record data of children and adolescents in the state. We are discussing expanding the project into a long-term partnership with the district, and have been approached about doing similar work with Fairfax County Public Schools (FCPS)- the largest school district in the state. Other projects that are supported by the initiative include:

* Identifying indicators of well-being in health and education data (Hofkens, PhD, EHD)
* Tracking education trajectories of adolescents with ADHD (Josh Reyes, MD, SOM)
* Re-entry to school after hospitalization (Lora Henderson, PhD, EHD)

## Project Team

### Faculty
[Tara Hofkens](https://education.virginia.edu/about/directory/tara-hofkens), Ph.D. (Education and Human Development)  
[Brian Wright](https://datascience.virginia.edu/people/brian-wright), Ph.D. (School of Data Science)  
[Richard Stevenson](https://healthybrain.virginia.edu/collaborators/richard-stevenson), M.D. (School of Medicine)  

### Data Science Graduate Students

<img align="left" width="150" src="https://github.com/roryblakc/3Cavs-ACPS/blob/main/Headshots/Rory.jpeg?raw=true"> 
<strong>Rory Black.</strong> Rory Black is a current graduate student at the University School of Data Science in the M.S. in Data Science program expected to graduate in May 2023. She received a bachelor’s degree in mathematics from the University of Mary Washington in Fredericksburg, VA. Her involvement in the ACPS Student Wellbeing project began in October 2022. She is intrigued by the data storytelling process through the use of visualizations and hopes to use that in her professional work post-graduation.
<br clear="left"/>

<img align="right" width="150" src="https://github.com/roryblakc/3Cavs-ACPS/blob/main/Headshots/Gargee.jpeg?raw=true"> 
<strong>Gargee Jagtap.</strong> Gargee Jagtap is a graduate student at the University of Virginia earning her masters in the Data Science program. She graduated from the University of Illinois Urbana-Champaign with bachelor’s in both math and statistics. She has been involved with the ACPS Student Wellbeing project since September 2022, and is excited to continue learning about building predictive models for forecasting after graduation.  
<br clear="right"/>


<img align="left" width="150" src="https://github.com/roryblakc/3Cavs-ACPS/blob/main/Headshots/Ali.jpeg?raw=true">  
<strong>Ali Rivera.</strong> Ali Rivera is a Graduate student in the 2023 MS in Data Science program at UVA. She holds a BA in Chemistry and a BA in Education: Subject Matter Teaching from Rowan University in her home state of New Jersey. Her experience teaching 10th-grade Chemistry in northern New Jersey made her passionate about using data to support student success and address inequities, especially for sensitive populations. She has been involved with the ACPS Student Wellbeing project since June 2022 and looks forward to continuing her career in the intersection of Data Science and Education.  
<br clear="left"/>

<img align="right" width="150" src="https://github.com/roryblakc/3Cavs-ACPS/blob/main/Headshots/David.jpeg?raw=true"> 
<strong>David Siamon.</strong> David Siamon is currently finishing his MS in Data Science at the University of Virginia (UVA). He studied at UVA for his undergraduate degrees as well, double-majoring in mathematics and computer science. After graduating, he will be working at Optiver in their Amsterdam office as a Quantitative Trader.  
<br clear="right"/>

### UVA Partners

[Joshua Reyes, M.D.](https://med.virginia.edu/pediatrics/divisions/developmental-behavioral-pediatrics/fellowship-program/our-fellows/), Fellow, School of Medicine  

[Supporting Transformative Autism Research](https://education.virginia.edu/research-initiatives/research-centers-labs/supporting-transformative-autism-research), School of Education and Human Development  
* [Rose Nevill](https://education.virginia.edu/about/directory/rose-nevill), Research Assistant Professor  
* Emily Furhman, Research Associate  

[Lora Henderson](https://education.virginia.edu/about/directory/lora-henderson-smith), Assistant Professor, School of Education and Human Development



