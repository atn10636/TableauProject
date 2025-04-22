# Team 5 TableauProject

Members:
- Lucas Kopelman [@LUCASKOPELMAN](https://github.com/LUCASKOPELMAN)
-  Amanda Nolan [@atn10636](https://github.com/atn10636)
-  Allie Rose [@ajr29445](https://github.com/allierose923/MIST-461-Group-Project1)
-  Aarav Patel [@aarav04423](https://github.com/aarav04423/MIST4610PROJECT1)
-  Saianagha Attili[@sa85600](https://github.com/LUCASKOPELMAN/4610-project)

## Dataset Description

Our dataset contains information about motor vehicle collisions in New York City. It was obtained from a NPYD's public records and includes 371,270 rows and 8 columns. The dataset attributes consist of crash time, crash date, the borough the crash occured in, the contributing factor behind the crash, the latitude and longitude of the crash, the vehicle type code and the number of persons injured or killed in the crash. 

## Question 1: Are there more collisons involving buses during school start and end times in New York City?

Justification: This analysis allows us to determine if there are irregular spikes in collisions depending on the specified vehicle type.  This has implications for student safety and urban traffic planning. By identifying any patterns in bus-related incidents, especially during morning drop-offs and afternoon pick-ups, city officials can determine if more oversight or traffic calming is needed near schools. We created a line plot of collisions (y-axis) and time (x-axis). We differntiated the lines based on if the vehicle type involved in the crash was a bus or other.


<img width="763" alt="Screenshot 2025-04-21 at 9 30 29 AM" src="https://github.com/user-attachments/assets/89e16c85-7f8e-4ea2-929e-e969848e5c13" />

## Question 1 Analysis 

 We observed distinct peaks in bus-related collisions:

- Morning spike around 7:00–9:00 AM, aligning with typical school start hours.

- Afternoon spike between 2:00–4:00 PM, corresponding with school dismissal hours.

These findings suggest that bus-involved collisions are more likely to occur during periods when buses are transporting students, reinforcing the need for traffic safety measures during these windows.



## Question 2: Is there a trend in the number of alcohol-related collisions on days of the week over time?

Justification: The NYPD may want to determine whether they need increased presence (more officers, DUI checkpoints, etc.) on certain days of the week. We filtered the dataset to include only collisions where alcohol involvement was listed as a contributing factor. We then plotted days of the week (x-axis) and percentage of total alcohol-related collisions (y-axis). This was compared accross time using different bar chart views. 

<img width="687" alt="Screenshot 2025-04-21 at 9 42 17 AM" src="https://github.com/user-attachments/assets/de0baf4c-40b7-498b-a9dc-6b38908e9b60" />

<img width="704" alt="Screenshot 2025-04-21 at 9 42 29 AM" src="https://github.com/user-attachments/assets/0d6569b3-bfbc-4cb3-9d38-476f24e855d4" />

## Question 2 Analysis:

The results showed:

- Friday and Saturday consistently have the highest percentage of alcohol-related collisions, with a noticeable drop on Sundays and weekdays.

- This trend suggests a strong correlation between weekend social activity and impaired driving accidents.

These insights provide clear support for targeted DUI enforcement on Fridays and Saturdays. Law enforcement agencies could strategically allocate DUI checkpoints or late-night patrols on weekends when the risk is highest. Public safety campaigns might also focus on discouraging weekend drinking and driving.


## Manipulations Applied to Data

For our first question, we created a calculated field to seperate data 

For our second question, we created a calculated field to seperate data into days of the week because the data was originally stored in date form (MM/DD/YYYY).

![image](https://github.com/user-attachments/assets/cf3479f6-2430-4bde-9c90-62d3e1774e31)



## Analysis and Results




