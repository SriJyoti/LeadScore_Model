# LeadScore_Model
a demonstration of lead scoring model generation include Data cleaning, Exploratory data analysis, feature selection and model training.
A lead score model is a valuable tool for businesses to prioritize their sales efforts based on the likelihood of a lead to convert into a paying customer. This model uses a variety of variables to calculate a score that represents the potential value of each lead.

Data Used:
This model was built using data with the following headers:
Agent_id: A unique identifier for the sales agent who worked on the lead.
Status: The current status of the lead, such as open or closed.
Lost_reason: The reason why the lead was lost, if applicable.
Budget: The budget of the lead for their desired rental property.
Lease: The length of lease the lead is interested in.
Movein: The date the lead intends to move in.
Source: The original source of the lead, such as a referral or online advertisement.
Source_city: The city where the lead was sourced.
Source_country: The country where the lead was sourced.
Utm_source: The specific marketing campaign or channel that the lead was sourced from.
Utm_medium: The medium used for the marketing campaign, such as email or social media.
Des_city: The city where the lead is interested in renting.
Des_country: The country where the lead is interested in renting.
Room_type: The type of rental property the lead is interested in, such as an apartment or house.

Methodology:
The lead score model was created using a machine learning algorithm that analyzes historical data to identify patterns and relationships between the input variables and the likelihood of a lead converting. The algorithm was trained on a subset of the data and then tested on a separate validation set to ensure its accuracy and reliability.

Output:
The output of the lead score model is a numerical score between 0 and 100, with higher scores indicating a greater likelihood of a lead converting into a customer. The model can be used to rank leads based on their scores, allowing sales teams to focus their efforts on the leads with the highest potential value.
