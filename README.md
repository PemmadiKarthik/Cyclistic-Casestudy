# Cyclistic Casestudy
# Google Data Analytics Professional Certificate

Course: Google Data Analytics Capstone: Complete a Case Study
Introduction:
In this case study, I will perform many real-world tasks of a junior data analyst at a fictional company, Cyclistic. In order to answer the key business questions, I will follow the steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.

Data Source:https://divvy-tripdata.s3.amazonaws.com/index.html

## Introduction
Welcome to the Cyclistic bike-share analysis case study! In this case study, you will perform many real-world tasks of a junior
data analyst. You will work for a fictional company, Cyclistic, and meet different characters and team members. In order to
answer the key business questions, you will follow the steps of the data analysis process: ask, prepare, process, analyze,
share, and act. Along the way, the Case Study Roadmap tables — including guiding questions and key tasks — will help you
stay on the right path.
By the end of this lesson, you will have a portfolio-ready case study. Download the packet and reference the details of this
case study anytime. Then, when you begin your job hunt, your case study will be a tangible way to demonstrate your
knowledge and skills to potential employers.
Scenario
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve your recommendations, so they must be backed up with compelling data insights and professional data
visualizations.
Characters and teams

● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself
apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with
disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about
8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to
commute to work each day.

● Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns
and initiatives to promote the bike-share program. These may include email, social media, and other channels.

● Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and
reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy
learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic
achieve them.

● Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the
recommended marketing program.

## About the company
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that
are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and
returned to any other station in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments.
One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes,
and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers
who purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the
pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will
be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a
very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic
program and have chosen Cyclistic for their mobility needs.
Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to
do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why
casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are
interested in analyzing the Cyclistic historical bike trip data to identify trends.

# ASK:
Design a new marketing strategy to convert casual riders into annual members.
Questions to be answered by analysis:
   1. How do annual members and casual riders use Cyclistic bikes differently?
   2. Why would casual riders buy Cyclistic annual memberships?
   3. How can Cyclistic use digital media to influence casual riders to become members?

# Prepare:
Data Source:
  
  I will use Cyclistic’s historical trip data to analyze and identify trends from Jan 2022 to Dec 2022 which can be downloaded from divvy_tripdata. The data has been made available by Motivate International Inc. under this license.This is public data that can be used to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

Data Organization:

  There are 12 files with naming convention of YYYYMM-divvy-tripdata and each file includes information for one month, such as the ride id, bike type, start time, end time, start station, end station, start location, end location, and whether the rider is a member or not. The corresponding column names are ride_id, rideable_type, started_at, ended_at, start_station_name, start_station_id, end_station_name, end_station_id, start_lat, start_lng, end_lat, end_lng and member_casual.

# Processing:
 PowerQuery is used to combine the various datasets into one dataset and clean it. Powerquery can be used in handeling and managing huge amount of data.

 Combining of data:

 12 csv files are uploaded as tables in the dataset '2022_tripdata'. Another table named "combined_data" is created, containing 5.7 million rows of data for the entire year.

Features Created:
   New features are created based on 

![Screenshot 2024-02-05 204105](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/e478ca1d-d731-4af9-aad5-b88976d0a69f)

# Analyze:
![Screenshot 2024-04-22 224735](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/62c7eeb8-2430-4691-a944-5ce59ed7215f)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/7122c035-c97d-4253-9ed7-a1765cf42527)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/93c88c5e-734d-4c4a-aa25-8c924f77ae8e)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/59a02117-6b63-4cf7-9e80-fd537cd8b889)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/b43c00bd-c340-48ae-b791-9bb7140acf7d)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/6797ab4a-75ef-4896-a360-1280910592fb)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/8312b2a2-1f35-4c53-95b9-f1d4223a4c4f)

![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/89c5de92-8e7d-44d1-800e-ccda22e017d2)

# Conclusion:
![image](https://github.com/PemmadiKarthik/pemmadikarthik.github.io/assets/159797209/32195bfb-8a35-4f85-bba6-11ed63f87332)






