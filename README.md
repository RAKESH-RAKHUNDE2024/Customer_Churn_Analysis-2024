# CUSTOMER CHURN ANALYSIS - USING MACHINE LEARNING ALGORITHM :-

This Project Performed An Extensive Descriptive Analytics To Explore Different Factors Responsible For Customers Churn In A Telecom Company.

# LOGISTICS REGRESSION :-

Post Descriptive, Predictive And Diagnostics Analytics Are Performed Using Machine Learning Algorithm. Logistics Regression And AUCROC Score Yields > 70% Which Is Significant For Modelling. The Prediction Test And Afterwards The Accuracy  Score Is Measured And Printed From This Model.


# SURVIVAL ANALYSIS : -

Logistic Regression Is Assigning A Probability To Each Observation That Describes How Likely It Is To Belong To The Positive Class. In Any Large Enough
Group Of Customers Like Telecom There Are Going To Be People Who Have The Same Attributes / Feature's.  Some Of Those Will Churns And Some Of
Them Won't, And What Telecom Company Ideally Like To Know Is The Probability Of Churn For Each Group. This Is What Logistic Regression, But It Is 
Not Clear What Time Scale It Is Predicted For. Therefore, Survival Analysis Was Conducted For This Purpose.   


# KAPLAN-MEIER AND COX PROPORTIONAL HAZARDS MODELS:-

Kaplan Is Fully Parametric And The Cox PH Model Is Semi- Parametric. Kaplan-Meier Theory Needs Specification Of The Distribution Of The Underlying
Hazard. CoxPH Analyses The Covariates (Features) Of A Dataset With Regards To How Long A Customer Survives. It Describes How Each Feature 
Proportionally Increases Risk Over The Baseline Survival Rate For A Cohort. The Expectation Is That, Churn Is Relatively Low. Kaplan- Meier Plot Suggest That, The Company Retained Almost 80-90% Of Their Customers, But There Is Steady Decline And After Over 70 Months The Company Is Able To Retain 
Almost 60% Of Their Customers. This Input Is Quite Useful For The Telecom Company To Understand The Trend And Business Forecast.   
 

To Examine The Effects Of Different Variables, The Cox Proportion Hazards Model Is Used.


# CoxPH MODEL :-

Cox Model Is File The Co-Efficients Of The Hazard Function Using Partial Likelihood Method. The Advantage Of Cox Proportional Hazards Regression
Is That The Survival Models Can Be Fitted Without The Distribution Assumption. The Time To Event For A Customers In The Data-Set Is Very Important 
For The Survival Curves At The. Aggregates Level; However, In Real Life Situation Along With The Event Data The Covariates (Features) Of That Individual Will Be Present. Therefore, It Is Very Important To Know About The Impact Of Covariates On The Survival Curve. This Would Help In Predicting The Survival Probability Of Customer , If The Associates Covariates Values Are Known. The Data Has Each Customers Tenure When They Churned (The Event Time T) And 
The Customer's Gender, MonthlyCharges Dependents, Partners, PhoneSevice Etc, The Other Variables Are The Covariates Here, It Would Be Interesting To 
Know How These Covariates  Impacts The Survival Probability Function. In Such Cases, It Is The Conditional Survival Function S(t\x) = P(T >t|x). xdenotes 
The Covariates. Company Interested In S(Tenure > t|(Gender, MonthlyCharges, Dependants, Partner, PhoneService Etc)).      
 
 A Well Calibrated Model And Important Business Inputs Are Presented Here To Help Telecom Company To Take Necessary Strategy To Retain Customers. 
