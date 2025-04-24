# Team 5 Tableau Project

Members:
- Lucas Kopelman [@LUCASKOPELMAN](https://github.com/LUCASKOPELMAN)
-  Amanda Nolan [@atn10636](https://github.com/atn10636)
-  Allie Rose [@ajr29445](https://github.com/allierose923/MIST-461-Group-Project1)
-  Aarav Patel [@aarav04423](https://github.com/aarav04423)
-  Saianagha Attili [@sa85600](https://github.com/LUCASKOPELMAN/4610-project)

## Dataset Description

Our dataset contains information about motor vehicle collisions in New York City. It was obtained from a NPYD's public records and includes 371,270 rows and 8 columns. The dataset attributes consist of crash time, crash date, the borough the crash occured in, the contributing factor behind the crash, the latitude and longitude of the crash, the vehicle type code and the number of persons injured or killed in the crash. 

## Question 1: Are there more collisions involving buses during school start and end times in New York City?

Justification: This analysis allows us to determine if there are irregular spikes in collisions depending on the specified vehicle type.  This has implications for student safety and urban traffic planning. By identifying any patterns in bus-related incidents, especially during morning drop-offs and afternoon pick-ups, city officials can determine if more oversight or traffic calming is needed near schools. We created a line plot of collisions (y-axis) and time (x-axis). We differentiated the lines based on whether the vehicle type involved in the crash was a bus or something else.


<img width="763" alt="Screenshot 2025-04-21 at 9 30 29 AM" src="https://github.com/user-attachments/assets/89e16c85-7f8e-4ea2-929e-e969848e5c13" />

## Question 1 Analysis 

 We observed distinct peaks in bus-related collisions:

- Morning spike around 7:00–9:00 AM, aligning with typical school start hours, suggests high traffic volume and bus activity during student dropoff.

- Midday Lull from 9:00 AM–2:00 PM, noticeable drop in bus crashes following the morning peak, indicates reduced risk during this window, likely due to fewer buses in operation and lighter traffic compared to peak hours


- Afternoon spike between 2:00–4:00 PM, corresponding with school dismissal hours, indicates increased collision risk during student pickup.

The data clearly shows two distinct spikes in bus-related crashes, during morning and afternoon school commute windows, which supports the shows that bus collisions are more frequent during school start/end times.
Overall, this suggests that bus-involved collisions are more likely to occur during periods when buses are transporting students, reinforcing the need for traffic safety measures during these windows.

This question and analysis are important for many reasons, including:

- Student Safety: Spikes in NYC bus collisions during school hours may pose an added risk to children walking to and from school

- Traffic Planning: Time-based trends can help the New York City Department of Transportation better deploy crossing guards, traffic officers, or signal timing

- Transit Policy: If school buses crash more often during peak times, it may prompt changes to routes, schedules, or driver protocols

- Targeted Solutions: NYC-specific collision patterns support focused, data-driven safety improvements in high-risk areas




## Question 2: Is there a trend in the number of alcohol-related collisions on days of the week over time?

Justification: The NYPD may want to determine whether they need increased presence (more officers, DUI checkpoints, etc.) on certain days of the week. We filtered the dataset to include only collisions where alcohol involvement was listed as a contributing factor. We then plotted days of the week (x-axis) and percentage of total alcohol-related collisions (y-axis). This was compared across time using different bar chart views. 

<img width="687" alt="Screenshot 2025-04-21 at 9 42 17 AM" src="https://github.com/user-attachments/assets/de0baf4c-40b7-498b-a9dc-6b38908e9b60" />

<img width="704" alt="Screenshot 2025-04-21 at 9 42 29 AM" src="https://github.com/user-attachments/assets/0d6569b3-bfbc-4cb3-9d38-476f24e855d4" />

## Question 2 Analysis:

The results showed:

- Friday and Saturday consistently have the highest percentage of alcohol-related collisions, with a noticeable drop on Sundays and weekdays.
- Clear spikes on Saturday (~25%) and Sunday (~23%), indicating weekends are much more prone to alcohol-involved crashes.
- Lowest percentages on Tuesday and Wednesday (below 10%), showing these are the least risky days for alcohol-related collisions.

- This trend suggests a strong correlation between weekend social activity and impaired driving accidents. The pattern shows a strong weekend concentration of risk, tied to social drinking patterns.

These insights provide clear support for targeted DUI enforcement on Fridays and Saturdays. Law enforcement agencies could strategically allocate DUI checkpoints or late-night patrols on weekends when the risk is highest. Public safety campaigns might also focus on discouraging weekend drinking and driving.

This question and analysis are important for many reasons, including:

- NYPD Resource Allocation: Identifying day-of-week trends in alcohol-related crashes helps the NYPD plan patrols, checkpoints, and staffing

- Public Safety: Spotting high-risk days can support targeted efforts to prevent DUI-related injuries and fatalities

- Policy & Prevention: Clear trends may justify awareness campaigns, stricter enforcement, or legislative action for certain days

- Data-Driven Action: Weekly patterns over time provide evidence for proactive strategies across NYC neighborhoods




## Manipulations Applied to Data

We began by cleaning the data. The orginial data contained many null attributes. There were also many columns with repetitve data, which we consolidated.

Original data:

<img width="744" alt="Screenshot 2025-04-23 at 10 24 58 AM" src="https://github.com/user-attachments/assets/a21f5a1b-3f7a-46bd-b65e-5d10531cecf5" />

Cleaned data:

<img width="769" alt="Screenshot 2025-04-23 at 10 26 27 AM" src="https://github.com/user-attachments/assets/cba9a6b3-c23c-4677-b245-8388ae5af58c" />


Addtionally, we created and used three calculated fields to better manipulate and display the data. 

- For our first question, we created a calculated field to separate buses from other vehicle types in order to visualize collisions with buses versus collions with other vehicles (SUV, sedan, pick-up truck, box truck, convertible, motorcycle, tractor truck, taxi, etc):

 <img width="604" alt="Screenshot 2025-04-22 at 12 30 24 PM" src="https://github.com/user-attachments/assets/7bbf5eca-9223-4317-9ada-786e575079ec" />

- For our second question, we created a calculated field to separate data into days of the week because the data was originally stored in date form (MM/DD/YYYY):

 <img width="606" alt="Screenshot 2025-04-22 at 12 31 13 PM" src="https://github.com/user-attachments/assets/f7bca304-91f4-44ba-9dae-db2db9f44f69" />

- We also created a calculated field to express percentages of collisions by day of week, which appears on the y-axis of the graphs for our second question:

<img width="591" alt="Screenshot 2025-04-22 at 12 33 15 PM" src="https://github.com/user-attachments/assets/49a6c66e-1a72-47df-9aae-d51b6286ea7e" />


## Analysis and Results

Analyzing New York City traffic accident patterns is essential for improving safety and keeping the city running efficiently. Our findings show that bus collisions significantly increase during school commute hours, raising concerns about student safety and highlighting the need for better traffic control near schools. We also discovered that alcohol-related crashes peak on weekends, especially Fridays and Saturdays, indicating a need for stronger DUI enforcement and public education. These insights give agencies like the New York police Department and the NYC Department of Transportation the tools to make informed decisions that enhance public safety, improve traffic flow, and help reduce preventable accidents.



