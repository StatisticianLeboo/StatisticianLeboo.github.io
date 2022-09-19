---
layout: post
title: "INDUSTRIAL ATTACHMENT SURVEY 2021"
subtitle: "A Survey carried out on the /18 cohort of Moi University School of Sciences and Aerospace Studies"
background: '/img/posts/IA Survey/school1.jpg'
---
In this project, I collaborated with my partners to come evaluate the overall experience of the industrial attachment of the /18 cohort of Moi University School of Sciences and Aerospace Studies. This was among the very first projects I involved myself in and I appreciate the efforts put in place by everyone to bring it to success. My partners are;

• Yunus Mire Mohamed

• Erick Odhiambo

• Paul Wafula

• Alexander Ethekon

# ABSTRACT
Industrial attachment is a program that allows students to gain industry-based skills while they are yet to graduate. Tertiary institutions organize these programs at the end of third year or fourth year studies. In this study, a survey was designed to investigate the experience of the students of /18 students of the school of sciences and Aerospace Sciences of Moi University. These students undertook their industrial attachment in 2021. The population was clustered by the 7 majors offered at the campus. A sample size of 164 was selected randomly and allocated using probability proportional to size. A questionnaire with 14 questions was sent to the students via google forms. The data collected was analyzed quantitatively by use of summary statistics and visualizations in R and Tableau. The overall response rate was 52%. No imputations were made for missing data but rather, they were all dropped. 53% of the students reported to have experienced difficulty in securing an industrial attachment. Covid-19 was the greatest hinderance when it came to securing attachment while the time allocated for industrial attachment in 2021 was also detrimental for the students. 85.88% of the students were able to apply the knowledge they gained from classwork at the organizations they were attached while 97.53% of the students reported to have gained skills in relation of their majors. Financial challenges were the main challenges faced by students during their industrial attachment in 2021. The study recommended restructure of the school calendar to ensure that students are ready for industrial attachments by January, May or September as it align with most organizations’ schedules. Future studies should seek to investigate the various associations between parameters.

# ACKNOWLEDGEMENTS
Works in this survey were accomplished thanks to the efforts of the following individuals; Mr. Charles Mutai, Senior lecturer at the department of Mathematics Physics and Computing whose technical expertise were crucial in sampling and data analysis. Class representatives of the /18 cohorts of the School of Sciences and Aerospace Studies including; Erick Odhiambo (Applied Statistics), Steve Panyako (Actuarial Science), Kinama (Computer Science), Malika (Biochemistry) and Edwin (Microbiology). 

Robert Kiage a consultant who works with various non-governmental organizations to install and manage monitoring and evaluation systems. His insights were significant in the drafting of the survey questionnaire. 

Further acknowledgements to Priscilla Njaguri for her editorial to the final report and Nelson Vundi for his review on the final documentation of the report.

# METHODOLOGY

## The Population
The population consisted of 407 individuals. These are /18 students of the School of Science and Aerospace Science. The population is then divided into 7 groups; programs offered within the faculty. These are as shown in table1 below: 
![Population Distribution of the /18 Cohort.](/img/posts/IA Survey/population.jpg)

The population was homogeneous within the group and therefore stratified and cluster sampling were good techniques to be used. However, we settled on cluster sampling due to the following reasons; 
1. There was no reliable sampling frame of all individuals in the population. 
2. Of the available sample frame, some of the members could not be reached.

Of the 7 initial clusters, 6 of them had a good list available and accessible. For this reason, we decided to drop the BSC cluster from the population and recalculated the sample size from a new population of 244 individuals. Another reason the BSC group was dropped was because most of the students in this cohort did not undergo industrial attachment and would have skewed the data.

## Sample Size Derivation

The sample size for the survey was computed using the Cochran’s Formula.
![Cochran’s Formula for Sample Size Determination.](/img/posts/IA Survey/samplesize.jpg)

Adjustments for small population sizes is made using the formula below
![](/img/posts/IA Survey/adj.jpg) 
*Where N is the total population size*

Using the formula above, the sample size were computed as shown below
![](/img/posts/IA Survey/size.jpg)

The samples were allocated to the clusters using proportional allocation as shown in table 2 below.
![Sample Distribution by Cluster](/img/posts/IA Survey/distr.jpg)

The final sample per cluster was generated randomly using Ms. Excel where each individual was assigned a unique key. Random numbers of the given sample size were generated within the cluster size and samples whose keys matched the random numbers were selected.

## Data Collection Techniques

Data collection was done by use of a questionnaire. The questionnaire consisted of 11 questions that took approximately 5-10 mins to be filled. The questionnaire was created on Google forms and therefore data collected needed less coding thus saved a lot of time.

## Data Analysis

Data analysis was majorly exploratory data analysis. Visualizations and summary statistics were generated using R and Tableau. No imputations were made for the missing data, rather they were all dropped irrespective of the question.

# RESULTS AND DISCUSSION

In this section the survey results are discussed as per the objectives.

## Sample Distribution

86 respondents participated in the survey. This was a 52% response rate. 28 were female while 58 were male. AST had the highest response rate with 30 which was 88.23% of the sample units generated for that cluster while BSE cluster had the lowest response rate with 17 (23.94%). The figure below displays the distribution of respondents 
![Respondents Distribution](/img/posts/IA Survey/Sample%20Distribution.png)

## The Attachment Program

95.4% of the students underwent their attachment within the stipulated time. This is a positive result since it indicates that majority of the students did not have to pay additional for insurance. The school undertakes an insurance cover for all students who undergo attachment within the stipulated period. However, if a student fails to undergo industrial attachment within that period, he or she has to take a personal cover as required by the organization. Of all the clusters, only Biochemistry reported students not undergoing attachment within the stipulated time with 4 students as shown in the figure below. 83.2% of the students had at least 3 months of industrial attachment experience.
![Students who underwent attachment filled by course](/img/posts/IA Survey/did.png)

85 students offered responses on their assessment time by the school-based supervisor. The recommended time for assessment is at week 8. However, on some occasions some adjustments are made to cater for students who had shorter attachment periods. 75.29% of the students reported to have been assessed on time. Some of the reasons stated for late assessment were Covid-19 and fixed timelines of the university supervisors. AST, ACS and BCM cohorts had students who were not assessedwithin the stipulated time as shown in the figure below.
![Assessment](/img/posts/IA Survey/assessed.png)

On application of classwork in the industrial attachment, 85.88% of the students reported to have been able to apply most of what they learnt in class. This implies that thestudents who find industrial attachment places within their academic niche is above the 85th percentile. It further means that the respective departments in the school of Sciences and Aerospace Sciences have done a good job in designing their curriculums in line with what is required in the job market. 
![Duration,Classwork Application and Ratio for the /18 Students who Underwent their Industrial Attachment.](/img/posts/IA Survey/ov.png)

## Students Views on the Overall Attachment Experience
### Overall Attachment Experience

43 students had a good experience, 14 had a fair experience and 27 had an excellent attachment experience. 
### Securing the attachment 
20 students found it difficult to secure an industrial attachment. 24 found
it very difficult. Only 1 respondent found it easy and was from the BSE
cluster as shown in the figure below.
 ![Difficulty in Securing Attachment](/img/posts/IA Survey/diff.png)
BSE students usually have their attachments as teaching practice where they get placed into secondary schools by the university. On average, the students do not have to toil to secure attachment as displayed in the figure above.
BSE cluster are distributed between the levels fair, easy and very easy. Some of the reasons that caused the majority (58.66%) to find it difficult to secure an attachment were; 

• Covid-19. With the pandemic at the its 3rd wave, most companies were having their staff work from home while other were cutting down their human resource and therefore was difficult to accommodate students. 

• The period that was prescribed. Most attachment opportunities are open in January, May or September yet the school sent students on attachment on the end of June

## Skills Gained with Respect to Course

On the level of skills gained with respect to what the students gained during their attachment experience, 97.53% of the students reported to have gained skills in relation of what they study. 22 found it totally related, 31 found it somehow related, 26 found it average and 4 gained minimal skills. Some of the skills gained by the students were; professionalism, communication skills, public relations, customer service, computer skills, leadership, presentation and management skills. AST, ACS and COM cohorts on the majority gained skills on data analysis. 

COM students gained skills on data recovery and networking while ACS students majorly gained skills in financial management and insurance. BCM and MIC students gained skills in laboratory test procedures and industrial procedures. BSE students reported to have gained skills in curriculum development and behavioural psychology.
![Attachment experience among the students.](/img/posts/IA Survey/sum.png)

## Challenges Experienced

1.20% of the students reported to have a really challenging experience, 18.07% found it somewhat challenging, 26.51% found it challenging, 48.19% had an average experience while 6.02% did not find it challenging at all. 

Of the challenges and problems experienced by students, _Finance and Covid-19_ were the most prevalent. Industrial Attachees are rarely receive stipends to help them manage their experience yet most of them get attached in completely new environments. Covid-19 made it difficult for most students to secure an attachment and even when they got one, working from home limited the level of skills one could get. Accommodation and transport problems were also prevalent among most students. 

Perhaps the most peculiar challenge was *Ingratitude*. Some students reported that they were being unappreciated yet they were tasked with huge workloads. Additionally, students reported to be mistreated by staffs and especially 
BSE students who were being disregarded by TSC employed teachers. Some students reported to be homesick since they were far from family and friends. BSE students further reported cases of indiscipline among high school students to the extent of them being bullied due to their inexperience. 

Organizational protocols were seemed as a challenge among some students more so for ACS, COM and AST cohorts. These protocols restricted the staff handing over access to equipment and workloads to students. 

Weather and environmental conditions of some locations were too severe for some students. Some students reported that they were in work environments that did not align with their passions or even their academic majors and therefore struggled to adapt. Gender discrimination was also reported as a challenge among some students. 

The figure below is a word cloud illustrating some of the challenges the students faced 
![Challenges experienced by the students](/img/posts/IA Survey/Challenges.png)

Read the detailed report from the link below.

[2021 INDUSTRIAL ATTACTHMENT REPORT]{{/download/2021 IA REPORT.pdf}}
