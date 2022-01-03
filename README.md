# Quantitative-Story-Telling-with-Shiny-Gender-Bias-in-Syllabi

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

![image](https://user-images.githubusercontent.com/26252963/147923524-f046a925-0173-4f23-b6a7-7213a4c3167c.png)


Introduction
==================

    The first plot displays the raw count of publications by female authors included in a reading list by publication year:

Within this dataset, we see that works by female authors are more likely to be included as time passes. This is hardly surprising, as prior to 1960's academic authorship was more or less exclusively a male enterprise. However, when plotted side by side with male authors, we find that the trend is universal:

![image](https://user-images.githubusercontent.com/26252963/147923497-555323f1-39ee-45b6-9985-a7f51095d891.png)



Time-Series
================
    This interactive time-series chart of author gender by year shows both genders in the same graph with percentages:
    
  ![image](https://user-images.githubusercontent.com/26252963/147923798-7e7f2429-4f88-47c9-a268-cd35743f4383.png)

    


Course Breakdown
===================
    We visualise all 43 courses (18 Undergraduate-level, 23 Master's-level, and 2 PhD-level) included in the dataset. We cluster all courses under five overarching categories: Security/Statecraft Studies, Regional Studies, International Political Economy, Theory, and International Organisations/Law. Hovering over a course displays additional information such as course convener rank, gender, and the total number of publications from that course:
    
 ![image](https://user-images.githubusercontent.com/26252963/147923744-03c1a0e7-1665-43e5-a795-0dbc202a442f.png)
Publication Pathways
=======================
    In order to better understand the pathways leading to reading list inclusion, we create and plot sequences involving at least one female author. The sequences follow the order Decade > Article/Book > Top/Other Publisher > Single/Co-Authored > Female/Male Co-Author. The numbers inside the dial report the count and overall percentage of the current selection:
    
   ![image](https://user-images.githubusercontent.com/26252963/147923861-5a325ac3-085c-4116-ab97-14b72eec68ce.png)



Co-Authorship
================
    Next, we visualise co-authorship patters using three parameters: maximum number of authors, maximum number of female authors, ad maximum number of male authors. The bubbles are recalculated each time a slider is updated and it can be animated. The radii are calculated using square root to offset the male single-author dominance:
    
  ![image](https://user-images.githubusercontent.com/26252963/147923916-95c169f3-16d5-4a3e-853b-43c71b503dfe.png)



Logistic Link
================
    Finally, this graph calculates a logistic function based on selected parameters: female author percentage and starting year. The first setting sets the threshold for creating a dummy variable and the latter subsets the data. For example, the default settings display which publication-years since 1960 has at least 20% female authors:
    
 ![image](https://user-images.githubusercontent.com/26252963/147923985-48d95d31-f730-4f2f-8e7f-a0aee98d35a9.png)



Publisher Info
===============
    This interactive dataframe allows for searching for specific publishers as well filtering on female author ratio and the total number of publications:
![image](https://user-images.githubusercontent.com/26252963/147923275-00edaf8a-cd05-4262-9018-0f8fc1377cd2.png)

