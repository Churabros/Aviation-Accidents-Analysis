# Moringa_Phase1_Project
![Airplane](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/c260c994-82b6-41ba-93d5-786449d41512)

# Bussiness Understanding

Selecting the right aircraft to start a business is a crucial decision, as choosing an aircraft with a high risk profile can result in operational disruptions, financial losses, and reputational damage. Therefore, it is essential to which aircraft are likely to pose the lowest risk for purchase.

in this analysis we will be looking at previous aricrafts accidents to be able to make reccomandations on which aircrafts carry the  lowest risk

# Data Understaning
The Data that was used for this analysis will be pulled from one file 
* **Source**: This dataset can be found in [`kaggle`](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses/data) which is a platform with thousands of datasets from all sorts of topics 
* **Contents**: The Data conatins various columns of diffrent information about the aircrafts involved in the accident and the locations involved 
* **Format**: The data is stored in a csv file (comma separated value )

# Data Analysis
![Number of Accidents by Aircraft Make](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/b485d541-1131-4596-b041-24a7d0830ef0)
* Aircrafts made by Cessna have the highest number of accidents compared to other makes with a total of 26,000 total accidents since 1962

![Number of Accidents by Aircraft Model](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/8c3a0732-dc93-499d-9340-69a4074b154a)

* Aircrafts of model 152 have the highest number of accidents compared to any other aircraft model with more than 2300 accidents since 1962

  ![downloadNumber of Accidents by Engine type ](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/04d44291-8e02-408e-bb60-ace9945ad59e)

* Aircrafts that use the Reciprocating engine type contribute the most in number of accidents with almost 7000 accidents since 1962
![Total Injuries](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/013cf09e-d057-4c36-98d0-7bbfd753e1ee)
* Aircrafts that are made by cessna have the most number of injuries form all the aircraft Makes
* Aircrafts that are of Model 152 have the most number of injuries in accidents that they had 
* Aircrafts that have 1 engine have the most number of injuries during accidents

![Total Uninjured](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/00938b27-fa7a-4949-bd1c-bc63a1069d58)
* Aircrafts that are made by Boeing have the most number of Uninjured people during accidents
* Aircrafts that are of Model DC-10-10 have the most number of Uninjured people during accidents
* Aircrafts that have 2 engines have the most number of Uninjured people during accidents

![Total accidents by year](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/6b28b38d-7f6e-4e40-8405-9ec1cf7dbd10)
* The number of accidents have been dropping significantly over the last 40 years with a major drop during the last 5 year

![Correltaion of features](https://github.com/Churabros/Moringa_Phase1_Project/assets/81102802/94118a4f-90e2-4528-ac16-3a50bdc0e9cd)
* There is a high correlation of 0.86 between total Injuries and fatal injuries which means that most injuries tend to be fatal 
* There is a correlation of 0.41 between number of engines and total uninjured, which correlates with the previous analysis that aircrafts with two engines have more uninjured people

# conclusion
1. The Aircrafts that are made by Cessna have been involved in the most number of accidents and has the most number of injured people compared to other makes 
2. The Aircrafts that are made by Boeing have been involved least number of accidents and has the most number of uninsured people
3. The Aircrafts of model 152 have been involved in the most number  of accident and have the most number of injuries 
4. The Aircrafts of model DC-10-10 have the least number of injuries 
5. Aircrafts that have more than one engine are less likely to get into an accident and also have less injured people during accidents

# Recommendations

1. **Model-** According to accident and injury data, the Boeing model is the least risky airplane. This proposal, which is based on statistical analysis, offers a data-driven method for making well-informed judgments when buying airplanes. The Boeing model is a wise purchase for people who value safety above all else, but the Cessna model needs more thought and safety precautions.

2. **Make -** Given its history of excellent survival rates and less injuries during accidents, the DC-10-10 stands out as the recommended choice when it comes to aircraft model for those that prioritize passenger safety. However, given that Model 157 has a higher injury rate, which may indicate safety issues that need to be fixed, it should be Avoided

3. **Engines -** Aircrafts with two engines are the safer option, with lower accident rates and superior passenger protection, according to an analysis of aviation safety by engine count. Although single-engine aircraft may be more cost-effective, they carry greater dangers, hence safety precautions and regulations must be strengthened.
