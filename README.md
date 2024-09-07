# Bike Sharing Analysis
Analyzing the bike sharing data from Kaggle Datasets

**Top Bike Routes**
---
![image](https://github.com/user-attachments/assets/01aa23b1-ea4b-4b1c-98c6-60767c0f3032)
![image](https://github.com/user-attachments/assets/4bbf3b29-662b-44a1-bc10-0b7c1cae9549)
Top routes for bike sharing consists of distances that ranges from `0.716 km` to `2.798 km`.
  - `Ellis Ave 60th st` to `55th st` route ranks the most number of rides (5k), with the average of 1.022 km.
  - `Shedd aquarium` to `streeter Dr. and grand ave` route has the highest distance, with an average of 3050 rides.

**Hourly Bike Ride**
---
![image](https://github.com/user-attachments/assets/573f491e-aab5-4320-b869-c791a7075d69)
![image](https://github.com/user-attachments/assets/757c2778-2771-49d7-a921-50a9d3ef3f01)
- Ridership for weekdays has two peaks:
  - 8 AM between 1112 to 1494 rides
  - 5 PM between 2523 to 2969 rides
- Distance travelled during weekdays are right-skewed.
- Ridership for weekend are partiall normal with a wider peak. For both Saturday and Sunday bikers has longer hour of activities which started from 10 AM to 7 PM.
- Additionally, during weekends, travel distance can reach up to 2.4 km in 4 AM to 2.3 km in 5 PM, that peaks at 2pm with 2.5 km.

**Usage by Distance**
---
![image](https://github.com/user-attachments/assets/35138d87-8e00-4247-b7bc-05a7fb8cb9c6)
![image](https://github.com/user-attachments/assets/c9ec6a82-e91b-4ec8-be4b-39b6d061224a)
- The three bike types follow almost the same distance distribution, with the exception of electric bikes because of its outlier.
- Electric bikes scan be used to transport up to 100 km distance.
- Negative velocity for electric and classic suggests that they can be used from origin to destination then vice versa. We can infer, in a network perspective that transportation in this two type of bikes are bidirectional in nature.
- On the other hand, docked bikes are unidirectional.

**Spatial Analysis**
---
![image](https://github.com/user-attachments/assets/7ecbeaee-686e-4999-93ce-3839f5ebede4)
![image](https://github.com/user-attachments/assets/4e67b0dc-0fd2-4639-8e91-482b5cf7e6cf)

**Statistical Analysis**
---
| Null Hypthesis (HO) | Alternative Hypothesis (HA) | p-value | Conlusion |
| -------- | ------- | ------- | ------- |
| The mean travel time is the same for electric bikes, <br>classic and docked bikes | The mean travel time is different for electric bikes, classic and docked bikes | 1.141772e-10 | Travel time is dependent to bicycle type |
|There is no significant difference in travel distance <br> between members and non-members |There is a significant difference in travel distance between<br> members and non-members |0.748 |There is no significant difference between the<br> distance travelled by member or casual|
| Travel distance is independent of the type of bike| Travel distance depends on the type of bike | 0.076429 |distance is independent from bicycle type|
|The average travel time is the same between peak <br>and non-peak hours|The average travel time is the same between <br>peak and non-peak hours|0.106|average travel time during weekdays is the same between <br>peak and non-peak hours|
|The average travel time is the same between peak <br>and non-peak hours|The average travel time is the same between <br>peak and non-peak hours|0.074|average travel time during weekends is the same between <br>peak and non-peak hours|
|Bike membership status does not influence <br>the choice of bike type|Bike membership status influences the choice of bike type|4.929534e-14|There is an association between membership type and bicycle type|
|There is no interaction effect between bike type <br>and membership status on travel velocity|There is an interaction effect between bike type <br>and membership status on travel velocity|3.171383e-23|Travel velocity is affected by membership and bicycle type|










