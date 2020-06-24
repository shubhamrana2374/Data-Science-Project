
# Variables description 

-----

Airbnb dataset 🏠 has __`106 columns`__ but we are keeping only 50 columns for analysis. Below is the description of the variables used in the analysis :

|__Variable Name__                | __Description__                                                                                                                                 |
|--------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------:|
|Id                               | This uniquely identifies a lisitng.                                                                                                             |
|description                      | It describes about the house                                                                                                                    |
|experiences_offered              | It includes any experiences offered                                                                                                             |
|transit                          | It includes the information regarding the means of travelling from the house                                                                    |
|host_id                          | It is a numeric value which assigns to every user who post a listing|                                                                           |
|host_name                        | It is the name of owner (listing holder).                                                                                                       |
|host_location                    | It gives the location of the host                                                                                                               |
|host_response_rate               | This variables shows how actively host responses to the requestor's message                                                                     |
|host_is_superhost                | Superhost indicates the owner shows good attitude towards the requestor                                                                         |
|host_listings_count              | This indicates how many listings does a host hold.                                                                                              |
|host_verifications               | It includes whether the host account is verified or not                                                                                         |
|host_identity_verified           | It includes whether the host idenitity is verified by the airbnb or not                                                                         |
|street                           | This variable has street names where listing is located                                                                                         |
|neighbourhood                    | This columns shows the neighbourhood of the listings                                                                                            |
|neighbourhood_cleansed           | This indicates whether neighbourhood of the house is clean or not                                                                               |
|city                             | This column shows the city , i.e., Sydney                                                                                                       |
|State                            | This column shows the state, i.e., NSW                                                                                                          |
|zipcode                          | This gives unique digit code of every area( one suburb can have more than 1 zipcode)                                                            |
|market                           | This shows the market area of the listing which is Sydney in this dataset.                                                                      |
|smart_location                   | This variable stores the smart location (popular suburb nearby).                                                                                |
|is_location_exact                | It includes boolen value true or false saying the listing posted by the owner shows the exact location or not                                   |
|property_type                    | It includes various types of properties such as apartment, boat, many more listed by the owner.                                                 |
|room_type                        | It includes different types of rooms for instance entire house , private room or shared room.                                                   |
|accommodates                     | This column shows how many members can one listing hold.                                                                                        |
|bathrooms                        | This depicts the number of bathrooms in a listing.                                                                                              |
|bedrooms                         | This illustrates the number of bedrooms in a listing.                                                                                           |
|beds                             | This illustrates the number of beds in a listing.                                                                                               |
|bed_type                         | This variable has various types of beds in thier rows such as real bed, sofa cum bed,etc.                                                       |
|amenities                        | This variable has value regarding the various benefits or offering of the listing.                                                              |
|price                            | This is the price of a listing .                                                                                                                |
|secruity_deposit                 | This is the amount keep by the owner as a secruity , if some mishappening happens then listing owner has all rights to use the secruity money.  |
|guests_included                  | This includes how many guests can be accommodated by a listing.                                                                                 |
|extra_people                     | This has the number of extra people can a listing holds on special request , this column is different from guests_included.                     |
|minimum_nights                   | This variable has value for the how many minimum days a tenant has to live in a listing.                                                        |
|maximum_nights                   | This variable has value for the how many maximum days a tenant has to live in a listing.                                                        |
|has_availability                 | This shows the availability of the listing.                                                                                                     |
|availability_30                  | This column shows for how many days a listing is available in a month.                                                                          |
|availability_60                  | This column shows for how many days a listing is available in a 60 days.                                                                        |
|availability_90                  | This column shows for how many days a listing is available in a 90 days.                                                                        |
|availability_365                 | This column shows for how many days a listing is available in a 365 days.                                                                       |
|number_of_reviews                | This has the number of reviews submitted by the users on airbnb.                                                                                |
|number_of_review_ltm             | This column shows the number of reviews in last tweleve months (Ltm).                                                                           |
|requires_license                 | This shows whether a user requires a license or not.                                                                                            |
|instant_bookable                 | This shows whether a listing can be booked instantly or not.                                                                                    |
|cancellation_policy              | This variable shows information about the cancellation policy of the lisitng.                                                                   |
|require_guest_phone_verification | This variable shows whether user verification is required to book a particular listing or not.                                                  |
|calculated_host_listings_count   | It includes the total number of listings host by a single owner.                                                                                |
|reviews_per_month                | This shows the reviews of a listing in a month.                                                                                                 |
|house_rules                      | This column shows the house rules set by owner for the tenants.                                                                                 |

-------

__`Census dataset`__ has __`34 columns`__ but we are keeping only __`8 columns`__ for analysis. Below is the description of the variables used in the analysis :

|__Variable Name__                           | __Description__                                                                                                      |
|-------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
|Postcode                                    | It shows the zipcode of a suburb.                                                                                    |
|Average salary or wages                     | It includes the information regarding the mean salary of an individual.                                              |
|Average total income or loss                | It includes the mean total income of the individual.                                                                 |
|Average total deductions                    | It includes the mean total deductions of the individuals.                                                            |
|Average total business income               | This variable stores information regarding the average business wage of an individual.                               |
|Average total business expenses             | This columns stores the data regarding the total mean amount spends by a business of an individual.                  |
|Average net tax                             | This is the mean tax pay by individual early.                                                                        |
|Average total super member accounts balance | This column holds information regarding the mean sum value of super members accounts balance.                        |
