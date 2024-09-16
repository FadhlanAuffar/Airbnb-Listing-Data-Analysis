![DALL·E 2024-08-27 21 58 40 - A dynamic and vibrant night scene in the heart of Bangkok city, captured in ultra-high 4K detail  The street is bustling with activity, filled with a ](https://github.com/user-attachments/assets/8c8a8cbf-3e5f-4772-a158-8b94f4d4b650)

Technical Report -> [Click here!](https://drive.google.com/file/d/1qpXoxjIiZv7kz7A_IWCw9HAVcY16zq8h/view?usp=sharing)

General Report -> [Click here!](https://drive.google.com/file/d/1b8rNF1sc88NYUs8VNwSm-y3sitwwIji3/view?usp=sharing)

Presentation Slide -> [Click here!](https://drive.google.com/file/d/1-1b91ovZEEkQW1mI1OVQlVZnq9gieiyw/view?usp=sharing)

Dashboard Tableau -> [Click here!](https://public.tableau.com/app/profile/fadhlan.auffar/viz/AirbnbListingAnalysis_17253312519050/Dashboard1?publish=yes)

# Project Background
Airbnb is a marketplace connecting hosts and guests. Hosts are individuals who provide accommodations, while guests are those who rent these accommodations. Airbnb's revenue comes from host fees and guest fees. Host fees are charged to hosts who have listed their properties and have them rented by guests. Guest fees are charged to guests who rent the accommodations.

Airbnb operates with a flexible, asset-light business model, as it does not own the properties listed on its marketplace. Instead, these accommodations are owned by individuals who wish to rent them out (hosts). **This indicates that Airbnb's success relies on its ability to attract new hosts and retain existing ones.**

Probelem Statement:
- Recently, many hosts have started creating their own websites to rent out their properties ([link](https://www.cnbc.com/2020/05/06/airbnb-hosts-are-building-their-own-direct-booking-websites-in-revolt.html)), bypassing Airbnb as the rental platform despite listing their properties on Airbnb. This trend is attributed to dissatisfaction with Airbnb's programs, resulting in a loss of potential revenue for the company.
- Airbnb aims to continuously increase the number of properties listed on its app to sustain its business.
- Airbnb plans to leverage Bangkok's appeal as a top tourist destination ([link](https://www.liputan6.com/lifestyle/read/4056210/bangkok-kembali-duduki-peringkat-pertama-kota-tujuan-turis-di-dunia)) to boost transactions on its platform.

Purpose:
Therefore, Airbnb seeks insights into host behavior based on the characteristics of listed properties. This information can be used to develop new programs tailored to better retain existing hosts and attract potential new hosts.

## Data Overview
This dataset contains information about the characteristics of properties listed by Airbnb hosts in Bangkok. The dataset consists of 15,854 Airbnb listings in Bangkok, with 16 variables capturing various property details, with each row representing a property listed by a host.

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


## Executive Summary
- Host Analysis:
  
  1. Individual Hosts (81.6%): Manage 1-2 properties.
  2. Semi-Professional Hosts (15.4%): Manage 3-10 properties.
  3. Professional Hosts (3%): Manage 11 or more properties.

  Recommendations:
  1. Support Individual Hosts, Develop tools like pricing calculators and communication templates.
  2. Encourage Growth for Semi-Professional Hosts, Provide incentives and mentorship programs.
  3. Provide Tools for Professional Hosts: Offer advanced tools like bulk management and property integration.

- Geographical Insights:
  
  Listings are concentrated in central districts like Vadhana and Khlong Toei, with potential for growth in less popular districts.
  High rental prices in districts with few listings suggest exclusivity, while areas with lower availability indicate high demand.

  Recommendations:
  1. Focus on Popular Districts: Enhance listing quality in key districts and explore growth in emerging areas.
  2. Leverage High-Priced Districts: Highlight unique features to justify rates and offer budget-friendly options in lower-priced areas.
  3. Implement Dynamic Pricing: Encourage hosts to adjust availability and rates according to demand.

- Room Type Analysis:
  
  1. Entire Homes/Apartments (56.2%): High demand, lowest availability, preferred by families/groups.
  2. Private Rooms (36.4%): Cater to budget-conscious or solo travelers.
  3. Hotel Rooms (4.1%) and Shared Rooms (3.3%): Target specific segments like budget travelers or those seeking social experiences.
  
  Recommendations:
  1. Promote Entire Homes/Apartments: Especially during peak seasons.
  2. Support Private Room Hosts: Position as a budget-friendly alternative.
  3. Expand Hotel Room Partnerships: Attract hotel-loyal guests.
  4. Market Shared Rooms: Emphasize cost savings and social opportunities.

Conclusion: To sustain and grow its market presence in Bangkok, Airbnb should focus on enhancing host support, strategically targeting high-demand areas, and optimizing pricing strategies to meet diverse traveler needs.






