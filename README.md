# Titanic Exploratory Data Analysis (EDA)
## Overview
- Project Title: Exploratory Data Analysis on a Sample Dataset
- Description: Perform EDA on a publicly available dataset (e.g., Titanic or Iris dataset). Analyze distributions, correlations, and missing values. Visualize key insights using graphs.
- Dataset Reference: Titanic Dataset
## Dataset Details
- Titanic-Dataset.csv (891 entries) – This dataset contains records of 891 passengers aboard the Titanic, including survival outcomes and various passenger attributes. Each entry provides:
- Survived: Indicates whether the passenger survived (1) or not (0).
- PassengerId: Unique identifier for each passenger.
-	Pclass: Passenger class (1st, 2nd, or 3rd), representing socio-economic status.
-	Name: Full name of the passenger.
-	Sex: Gender of the passenger (male/female).
-	Age: Age of the passenger in years (some values missing).
-	SibSp: Number of siblings or spouses aboard the Titanic.
-	Parch: Number of parents or children aboard the Titanic.
-	Ticket: Ticket number assigned to the passenger.
-	Fare: The fare paid for the ticket.
-	Cabin: Cabin number (many values missing).
-	Embarked: Port where the passenger boarded (C = Cherbourg, Q = Queenstown, S = Southampton).
## Key Analyses & Findings
1.	Sex was the most significant factor in determining survival during the Titanic incident. Females had a significantly higher survival rate compared to males, indicating that women were given priority on lifeboats, even though there were more male passengers onboard than female.
2.	As shown in the exploratory data analysis (EDA) above, passengers who paid higher fares and were in first class (Pclass 1) had a higher survival rate than those who paid lower fares and were in second or third class.
3.	Females and younger children were given priority on the lifeboats, as I established through a detailed EDA of the Sex and Age columns. Passengers in the 0-10 years age group had the highest survival rate.
4.	Passengers who embarked from Cherbourg had the highest survival rate, while those who boarded from Southampton had the lowest survival rate. Based on the Fare column analysis, we know that the majority of passengers bought the cheapest tickets. Therefore, passengers who boarded from Southampton likely paid the least fare, which contributed to their lower survival rates. This was confirmed through a thorough investigation of the Embarked column.
5.	People travelling with smaller families had a higher chance of surviving the accident in comparison to people with large families and travelling alone



