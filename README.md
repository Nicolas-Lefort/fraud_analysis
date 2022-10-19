The goal is to detect Insurance Fraud for vehicle accidents. 
The analysis is done on Jupyter Notbook with Python and sklearn.

Data source: https://www.kaggle.com/code/girishvutukuri/exercise-insurance-fraud/data

About dataset: 

Attribute Information: The dataset depicts the details of the auto insurance claim, like,
the policy details, vehicle details, claim details and also the customer demographic
information etc.
Information about attributes:
Demographics Data :
• CustomerID : Customer ID
• InsuredAge : age
• InsuredZipCode : Zip Code
• InsuredGender : Gender - the missing value is represented as “NA”
• InsuredEducationLevel : Education
• InsuredOccupation : Occupation
• InsuredHobbies : Hobbies
• CapitalGains : Capital gains(Financial Status)
• CapitalLoss : capital loss(Financial Status)
• Country : Country
Policy Information :
• CustomerID : Customer ID
• CustomerLoyaltyPeriod : Duration of customer relationship
• InsurancePolicyNumber : policy number
• DateOfPolicyCoverage : policy commencement date
• InsurancePolicyState : Policy location (State)
• PolicyCombinedSingleLimit : Split Limit and Combined Single Limit • PolicyDeductible : Deductible amount
• PolicyAnnualPremium : Annual Premium – the missing value is represented as “-1”
• UmbrellaLimit : Umbrella Limit amount
• InsuredRelationship : Realtionship
• TotalCharges : Customer account information (Total). ( For this attribute,
missing values are denoted as “MISSINGVAL” also)
• DOE : Date of entry as customer
• ElectronicBilling : Customer account information - whether electronic
billing
• ContractType : Contract type ( For this attribute, missing values are
denoted as “NA”)
• PaymentMethod : payment method
Claim Information :
• CustomerID : Customer ID
• DateOfIncident : Date of incident
• TypeOfIncident : Type of incident
• TypeOfCollission : Type of Collision - “?” is the missing value
• SeverityOfIncident : Collision severity
• AuthoritiesContacted : Which authorities are contacted
• IncidentState : Incident location (State)
• IncidentCity : Incident location (City)
• IncidentAddress : Incident location (address)
• IncidentTime : time of incident – Hour of the day - the missing value is represented
as “-5”
• NumberOfVehicles : Number of vehicles involved
• PropertyDamage : If property damage is there - “?” is the missing value
• BodilyInjuries : Number of bodily injuries
• Witnesses : Number of witnesses - missing value is represented as
"MISSINGVALUE"
• PoliceReport : If police report available - “?” is the missing value
• AmountOfTotalClaim : Total claim amount - the missing value is represented as
“MISSEDDATA”
• AmountOfInjuryClaim : Claim for injury
• AmountOfPropertyClaim : claim for property damage
• AmountOfVehicleDamage : claim for vehicle damage
Data of Vehicle:
• CustomerID : Customer ID
• VehicleAttribute : Service signed for
• VehicleAttributeDetails : Value of the vehicle attribute - the missing value is
represented as “???”
Fraud Data :
• CustomerID : Customer ID
• ReportedFraud : Fraud or not – Target



