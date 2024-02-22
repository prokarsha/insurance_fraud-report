# insurance_fraud-report
Each row represents a different policyholder and their associated information. Here's a breakdown of the columns:

    months_as_customer: Number of months as a customer
    age: Age of the policyholder
    policy_number: Policy number
    policy_bind_date: Date the policy was bound
    policy_state: State where the policy is issued
    policy_csl: Policy combined single limit
    policy_deductable: Policy deductible
    policy_annual_premium: Annual premium for the policy
    umbrella_limit: Umbrella limit for the policy
    insured_zip: ZIP code of the insured
    insured_sex: Gender of the insured
    insured_education_level: Education level of the insured
    insured_occupation: Occupation of the insured
    insured_hobbies: Hobbies of the insured
    insured_relationship: Relationship of the insured
    capital-gains: Capital gains
    capital-loss: Capital loss
    incident_date: Date of the incident
    incident_type: Type of incident
    collision_type: Type of collision
    incident_severity: Severity of the incident
    authorities_contacted: Authorities contacted after incident
    incident_state: State where the incident occurred
    incident_city: City where the incident occurred
    incident_location: Location of the incident
    incident_hour_of_the_day: Hour of the day when the incident occurred
    number_of_vehicles_involved: Number of vehicles involved in the incident
    property_damage: Whether property damage occurred
    bodily_injuries: Number of bodily injuries in the incident
    witnesses: Number of witnesses
    police_report_available: Whether a police report is available
    total_claim_amount: Total claim amount
    injury_claim: Claim amount for injuries
    property_claim: Claim amount for property damage
    vehicle_claim: Claim amount for vehicle damage
    auto_make: Make of the vehicle
    auto_model: Model of the vehicle
    auto_year: Year of the vehicle
    fraud_reported: Whether fraud was reported
    _c39: Unnamed column

It appears that the last column _c39 doesn't seem to have any meaningful data and could be an artifact. Additionally, there are missing values denoted by "?" in the dataset, particularly in columns like collision_type, property_damage, and police_report_available.


n this study, an insurance dataset underwent an exploratory data analysis (EDA) to unveil relationships between attributes. Through this analysis, missing values were identified and replaced, while outliers were detected and removed to ensure data integrity. A correlation heatmap was constructed to visualize variable relationships and address multicollinearity concerns. Leveraging insights from the EDA, machine learning algorithms were employed to predict insurance fraud likelihood. Models were trained and evaluated using diverse metrics, ensuring effectiveness in fraud detection. This approach, spanning from data exploration to predictive modeling, offers a robust framework for insurance dataset analysis and fraud mitigation.
