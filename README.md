# Premium users
This solution defines potential premium clients on the condition that we only 
have a few clients who use the premium feature.

### The question
Which restaurants should we contact first to sell Premium option?

### Data
There are 2 csv files for this work: subscription.csv and restaurants.csv. 

subscription.csv:

Column | Description | 
--- | --- 
location_id | Unique identifier of a restaurant
is_active | Is the restaurant active on Premium subscription on this day?
start_date | Start date of Premium subscription
end_date | Expected end date of Premium subscription

restaurants.csv:

Column | Description | 
--- | --- 
location_id	| Unique identifier of a restaurant
continent | Continent of the restaurant
country | Country of the restaurant
days_since_abandoned_cart | Days since the restaurant had a Premium abandoned cart
days_since_last_email | Days since we last delivered an marketing Email
email_delivered_last_month | Number of marketing Emails delivered last month
email_opens_last_month | Number of marketing Emails opened by the restaurant last month
manage_listings_last_month | Number of times owner updated listing
manage_photos_last_month | Number of times owner managed restaurant photos
visitor_calls_last_month | Number of website redirected phone calls last month
visitor_reservations_last_month | Number of website redirected online reservations last month
visitor_saves_last_month | Number of times saved as favorite by visitors last month
visitor_website_clicks_last_month | Number of redirected website clicks last month
awards | Number of awards given by website
days_since_creation | How long has the restaurant been created on website
days_since_claim | How long has the owner claimed the listing on website
geo_rank | How is the restaurant ranked in the geo?
geo_rank_all | How many restaurants are there in the geo?
photos | Total number of photos on website
rating | Rating of the restaurant
days_since_last_review | Days since the restaurant received the last review
reviews | Total number of reviews on website
uniques | Number of annual unique visitors on website
ds | date stamp

### Solution
Solution can be found in solution.ipynb file and overview of the solution in 
the premium_clients_prediction_presentation.pdf