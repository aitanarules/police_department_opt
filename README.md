# Chicago police department

This corresponds to the 1st optimization project of the Optimization subject in the Data science program.

# Scenario

In this section we will describe in detail both the problem to be solved, as well as some particularities about the organization that you have recently joined.


## Introduction

You have recently been hired as analysts for the analytics department of the City of Chicago Police Department. Chicago is a vibrant and culturally rich city located in the state of Illinois on the shores of Lake Michigan. It is famous for its modern architecture, world-class museums such as the Art Institute of Chicago, and its influence in music, especially jazz and blues. Also known as *the Windy City*, Chicago is also known for its crime challenges, especially gun violence in some areas of the city. Although most of Chicago's neighborhoods are safe and prosperous, certain areas have experienced high rates of homicide and violent crime. The causes of these problems include factors such as poverty, lack of economic opportunity, and gang activity. Despite these challenges, the city and its authorities have implemented various strategies to improve safety and reduce violence, with mixed results over the years.

<center>
<img src="https://gitlab.com/drvicsana/crime-milp-project/-/raw/main/images/CPD_Logo.png" width="60%"/>
</center>

The Chicago Police Department (CPD) is one of the largest municipal police forces in the United States and has a long history dating back to 1837. The CPD is responsible for maintaining public order, preventing and combating crime, and ensuring the safety of Chicago residents and visitors.

The city currently has 23 police stations. The following interactive map shows the location of each of the city's police stations.



Each of the police stations has an area of influence and/or associated action, which defines which areas are patrolled by the station as well as which areas are called upon in case of emergency. Each of these areas of influence defines what is known as a police district. Currently, the city is divided into 23 **police districts**, each led by a commander and responsible for servicing the area that corresponds to their district.  

In turn, Chicago's police districts are organized into **police areas** that group several police districts under broader supervision. Currently, the Chicago Police Department is divided into five areas, each of which includes several police districts. These areas allow for more efficient administration and better coordination among the districts to address safety issues that may cross the boundaries of a single district.  Each area has an Area Chief responsible for overall oversight, including operations and implementation of strategies to reduce crime and improve security in the districts under his or her command. In addition, these areas facilitate the distribution of resources and allow for better coordination among the different districts to address common problems more effectively.

The City of Chicago is administratively divided into Community Areas. These are geographic divisions designed to aid in the planning and analysis of the city. Chicago is divided into 77 such areas, which were established in the 1920s by sociologists at the University of Chicago. The idea behind these divisions was to create consistent units of study to better understand the social and economic structure of the city.

One of the main characteristics of Community Areas is their geographic stability. Unlike neighborhoods, whose boundaries can change over time and may be known by different names, Community Areas have maintained their boundaries virtually unchanged since their inception. This allows the demographic, economic and social data collected in these areas to be comparable over time, which is crucial for analyzing historical trends, such as changes in population, income levels or crime rates.

Each Community Area typically includes several smaller neighborhoods. For example, the Community Area known as Lakeview encompasses neighborhoods such as Wrigleyville and Boystown. Although most people tend to identify more with their specific neighborhood than with the larger Community Area, these Community Areas are essential to citywide planning and decision-making. They are used by government, researchers, and community organizations to design public policy, develop urban projects, and allocate resources more effectively.

The following interactive map shows the 77 Community Areas in the City of Chicago along with some interesting facts.


After applying different policies in order to tackle crime within the city, the CPD has come to the conclusion that perhaps its structure and organization is outdated according to how crime in the city has evolved (in type and quantity) in recent years. It is for this reason that **the CPD has given you the task of reorganizing its structure of police districts and areas in an effective and efficient manner**. Therefore, your task will be to determine how to structure the 23 districts and the corresponding 5 areas on the basis of objective criteria.


## Some aspects to consider for the optimization

Although the CPD has given you some leeway to establish the criteria governing the reorganization, as long as they are objective, during the meetings they have given certain guidelines that should be taken into account.

The department has expressed an interest in maintaining exactly 23 police districts whose base of operations will be each of the 23 police stations. In other words, no new stations will be added and none of the existing ones will be eliminated, but rather the available police stations will be used. As for the number of police areas, it is also desired to maintain the current number of areas.

The definition of a police district determines which areas of the city the available police officers will patrol, as well as which areas of the city the available officers will go to when incidents occur. Therefore, the definition of the district will indirectly determine the area of coverage of the police station as well as the possible patrol route(s) that will be carried out.

Police areas have the objective of coordinating the personnel of various police districts that, due to their proximity, must face similar threats and mobile crime. The complexity of coordinating these areas is related to the number of associated police districts as well as their characteristics.

The police unions have mentioned on more than one occasion that one of the main causes of officer desertion from the force is the excessive workload they are subjected to in certain districts. The union has expressed its interest in being involved in the new solution proposed and will press for it if they feel it is not appropriate.





