# 🏋️‍♀ Fitness Class Attendance Prediction 

![](https://www.pngkey.com/png/full/808-8089823_fitness-clipart-group-fitness-workout-group-transparent.png)
This project aims to solve the problem:
"Will a client attend a class they booked?"

💡 Objective:
Fitness clubs often experience no-shows, resulting in lost revenue and unused spaces. By predicting whether a client will attend a class, fitness clubs can optimize their class bookings, improve client satisfaction, and maximize attendance.

### 📊 Dataset Description

The dataset used in this project contains key features related to fitness class bookings. Below is a breakdown of the dataset columns:
|Column Name |	Description|
| ------ | ------ |
| booking_id	| Unique identifier for each booking. |
| months_as_member |	Number of months the client has been a member of the fitness club. |
| weight	| Client's weight (in kg). |
| days_before	| Number of days between the booking date and the class date. |
| day_of_week	| The day of the week the class is scheduled (e.g., Mon, Tue). |
| time	| The time of the class (morning, afternoon, or evening). |
| category	| Type of class (e.g., Yoga, Pilates, Cardio). | 
| attended	| Target variable — whether the client attended the class (1 = Yes, 0 = No). |

### 📈 Key Insights

- Days Before the Class Matters:
    The number of days between the booking and the class significantly impacts whether a client attends. The longer the gap, the less likely they are to show up.

-  Day of the Week Influences Booking:
    Attendance rates vary depending on the day of the week and time of day. Morning classes are more popular. Thursday and Friday are the most booked.

- Category of Class is Important:
    Different class types have different attendance patterns. For instance, HIIT and cycling classes might have higher attendance rates than yoga classes.

### 🤖 Logistic Regression vs. Random Forest Model
|Model |	Accuracy | Precision | Recall | F1 Score|
| ------ | ------ | ------ | ------ | ------ |
| Logistic Regression | 76.3% | 82% | 39.8% | 53.5% |
| Random Forest	| 72.3%	| 62.8% |	47.5% |	54.1% |
