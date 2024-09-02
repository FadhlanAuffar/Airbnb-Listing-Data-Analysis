![DALL·E 2024-08-27 21 58 40 - A dynamic and vibrant night scene in the heart of Bangkok city, captured in ultra-high 4K detail  The street is bustling with activity, filled with a ](https://github.com/user-attachments/assets/de12406c-3d25-4651-be7f-3e1c10f29700)

Technical Report -> [link](https://drive.google.com/file/d/1qpXoxjIiZv7kz7A_IWCw9HAVcY16zq8h/view?usp=sharing)
General Report -> [link](https://drive.google.com/file/d/1b8rNF1sc88NYUs8VNwSm-y3sitwwIji3/view?usp=sharing)
Presentation Slide -> [link](https://drive.google.com/file/d/1-1b91ovZEEkQW1mI1OVQlVZnq9gieiyw/view?usp=sharing)
Story Tableau -> [link](https://public.tableau.com/app/profile/fadhlan.auffar/viz/CapstoneProjectM2Fadhlan/CapstoneProjectStory?publish=yes)

![DALL·E 2024-08-27 21.58.40 - A dynamic and vibrant night scene in the heart of Bangkok city, captured in ultra-high 4K detail. The street is bustling with activity, filled with a .png](https://prod-files-secure.s3.us-west-2.amazonaws.com/6e386b82-3d73-40ce-9b8f-45e41e44616a/f18a02bb-e0a6-4b69-9781-ef2afa4d54c8/DALLE_2024-08-27_21.58.40_-_A_dynamic_and_vibrant_night_scene_in_the_heart_of_Bangkok_city_captured_in_ultra-high_4K_detail._The_street_is_bustling_with_activity_filled_with_a_.png)

# Introduction
Airbnb is a marketplace connecting hosts and guests. Hosts are individuals who provide accommodations, while guests are those who rent these accommodations. Airbnb's revenue comes from host fees and guest fees. Host fees are charged to hosts who have listed their properties and have them rented by guests. Guest fees are charged to guests who rent the accommodations.

Airbnb operates with a flexible, asset-light business model, as it does not own the properties listed on its marketplace. Instead, these accommodations are owned by individuals who wish to rent them out (hosts). **This indicates that Airbnb's success relies on its ability to attract new hosts and retain existing ones.**

Probelem Statement:
- Recently, many hosts have started creating their own websites to rent out their properties ([link](https://www.cnbc.com/2020/05/06/airbnb-hosts-are-building-their-own-direct-booking-websites-in-revolt.html)), bypassing Airbnb as the rental platform despite listing their properties on Airbnb. This trend is attributed to dissatisfaction with Airbnb's programs, resulting in a loss of potential revenue for the company.
- Airbnb aims to continuously increase the number of properties listed on its app to sustain its business.
- Airbnb plans to leverage Bangkok's appeal as a top tourist destination ([link](https://www.liputan6.com/lifestyle/read/4056210/bangkok-kembali-duduki-peringkat-pertama-kota-tujuan-turis-di-dunia)) to boost transactions on its platform.

Purpose:
Therefore, Airbnb seeks insights into host behavior based on the characteristics of listed properties. This information can be used to develop new programs tailored to better retain existing hosts and attract potential new hosts.

## Data Overview
This dataset contains information about the characteristics of properties listed by Airbnb hosts in Bangkok, with each row representing a property listed by a host.

Feature:
1. id = unique identifier for the property
2. name = property name
3. host_id = unique identifier for the host
4. host_name = host name
5. neighbourhood = district where the Airbnb is located
6. latitude = neighbourhood location
7. longitude = neighbourhood location
8. room_type = type of Airbnb (Entire home, Private room,Shared room, Hotel)
9. price = rental price (baht)
10. minimum_nights = minimum stay requirement
11. number_of_reviews = total number of reviews received
12. last_reviws = date of the last review
13. reviews_per_month = number of reviews per month
14. calculated_host_listing_count = total number of properties listed by the host
15. availability_365 = number of days the property is available for rent in a year
16. number_of_reviews_ltm = number of reviews in the last 12 months
