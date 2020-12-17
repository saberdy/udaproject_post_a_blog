

### Table of Contents

[Here is the link to the blog post](https://saberdy.github.io/projects/stackoverflow-trend-analysis/)

## [Libraries](#lib)

## [Motivation](#motiv)

## [Files](#fil)

## [Summary of the Results](#summary)

 - [Question 1](#q1)
 - [Question 2](#q2)
 - [Question 3](#q3)
 - [Question 4](#q4)
 
 ## [Legal](#leg)

## [Acknowledgements](#ack)

## Libraries <a name="lib"></a>

Python 3.8 Libraries used in this project are:  

- pandas
- numpy 
- matplotlib 


## Motivation <a name="motiv"></a>

Coding and developemnet is so dynamic and evolving rapidly. New languages are emerging and new tools are developed. It may not be easy to interprete where it is heading without having a feedback. This project is analysing the current and recent years trends. For this purpose, [Stack Overflow](https://insights.stackoverflow.com/survey) survey data is used. The results could provide a glance on fascinating tools used by developers with varying expertie level. It could be used as guidance for newbies or hobbiests too. The results demonstrate uprising technologies in programming languages, databases, frameworks and platforms.

## Files<a name="fil"></a>

Download [Stack Overflow Annual Developer Survey](https://insights.stackoverflow.com/survey) data. Locate __survey_results_public.csv__ files from each survery from year 2017 till 2020 in __Data__ directory.<br/>
The main file that has all python code is **_'main.ipynb'_** which is found in root directory.<br/>

The final path in data directory (2017 survey for instance) would be as follows:<br/>
_'./data/2017/survey_results_public.csv'_<br/>


## Summary of the Results <a name="summary"></a>

**Q1.** What type of developers are among top trends of recents years? How has it been varying year by year since 2017?
<a name="q1"></a>

__2017: Web, Desktop applications, Mobile Developer__

__2018: Back-End, Full-Stack, Front-End Developer__

__2019: Full-Stack, Back-End, Front-End Developer__

__2020: Back-End, Full-Stack, Front-End Developer__


**Q2.** Which programming languages have been most popular according to last 4 years' survey?
<a name="q2"></a>

|2017        |  2018     | 2019     | 2020     |
|:----------:|:---------:|:--------:|:--------:|
| JavaScript |JavaScript |JavaScript|JavaScript|
| SQL        |HTML       |HTML/CSS  |HTML/CSS  |
| Java       |CSS        |SQL       |SQL       |
| C#         |SQL        |Python    |Python    |
| Python     |Java       |Java      |Java      |

**Q3.** What are the popular programming languages for Linux, Mac and Windows operating system users on 2020?
<a name="q3"></a>

| LanguageWorkedWith    |   Linux |
|:----------------------|--------:|
| JavaScript            |    9408 |
| Python                |    8727 |
| HTML/CSS              |    8520 |
| SQL                   |    7469 |
| Bash/Shell/PowerShell |    6575 |


| LanguageWorkedWith   |   Windows |
|:---------------------|----------:|
| JavaScript           |     18077 |
| HTML/CSS             |     17844 |
| SQL                  |     16426 |
| C#                   |     13195 |
| Java                 |     10601 |


| LanguageWorkedWith   |   Mac |
|:---------------------|------:|
| JavaScript           | 10106 |
| HTML/CSS             |  8633 |
| SQL                  |  6562 |
| Python               |  5960 |
| Java                 |  5509 |

**Q4.** Is there any pattern in the way people prefer using a platform with a programming language, database, or a framework? What
   about a popular platform for a particular developer type?
<a name="q4"></a>
|                    | 2020                  | 2019                  | 2018               | 2017                      |      
|:-------------------|:----------------------|:----------------------|:-------------------|:--------------------------|      
| __Platform__       | Linux                 | Linux                 | Linux              | Amazon Web Services (AWS) |      
| __DevType__        | Developer, full-stack | Developer, full-stack | Back-end developer | Web developer             |      
| __Count__          | 12530                 | 19477                 | 15308              | 4204                      |      
                  
                                                                                             
                                                                                             
|                     | 2020    | 2019    | 2018    | 2017                      |            
|:--------------------|:--------|:--------|:--------|:--------------------------|            
| __Platform__        | Windows | Windows | Linux   | Amazon Web Services (AWS) |                  
| __Framework__       | jQuery  | jQuery  | Node.js | Node.js                   |                  
| __Count__           | 8957    | 15956   | 11593   | 2938                      |        
                                                                       
                                                                                             
|                    | 2020   | 2019   | 2018   | 2017            |                          
|:-------------------|:-------|:-------|:-------|:----------------|                          
| __Platform__       | Linux  | Linux  | Linux  | Windows Desktop |                                
| __Database__       | MySQL  | MySQL  | MySQL  | SQL Server      |                                
| __Count__          | 11686  | 18682  | 13920  | 3213            |                      
                                                                                             
                                                                                             
|                    | 2020       | 2019       | 2018       | 2017                      |    
|:-------------------|:-----------|:-----------|:-----------|:--------------------------|    
| __Platform__       | Linux      | Linux      | Linux      | Amazon Web Services (AWS) |          
| __Language__       | JavaScript | JavaScript | JavaScript | JavaScript                |          
| __Count__          | 15342      | 24558      | 17399      | 4204                      |    


## Legal <a name="leg"></a>

All atabases used in this project - The Public 2017 till 2020 Stack Overflow Developer Survey Results - is made available under the Open Database License (ODbL): http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/.

TLDR: You are free to share, adapt, and create derivative works from The Public 2020 Stack Overflow Developer Survey Results as long as you attribute Stack Overflow, keep the database open (if you redistribute it), and continue to share-alike any adapted database under the ODbl.

## Acknowledgements <a name="ack"></a>

[Stack Overflow](https://insights.stackoverflow.com/survey) has made data availble for public.

Massive, heartfelt thanks to all Stack Overflow contributors and lurking developers of the world who took part in the survey this year. We value your generous participation more than you know. <3
