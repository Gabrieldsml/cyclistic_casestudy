# CYCLISTIC case study.

###Please check cyclistic.md to see the notebook of the case study.

## 1. Introduction

This is a case study from one of the courses that I'm doing to learn data analysis/data science and machine learning. The Cyclistic case study is focused on data analysis.

I will be following these steps of the data analysis process:

-   Ask

-   Prepare

-   Process

-   Analyze

-   Share

-   Act

#### 1.1 Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company's future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

#### 1.2 Characters and teams

-   Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can't use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.
-   Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.
-   Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about Cyclistic's mission and business goals --- as well as how you, as a junior data analyst, can help Cyclistic achieve them.
-   Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

#### 1.3 About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic's marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic's finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs. Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

## 2. Asking

**Three questions will guide the future marketing program:**

1.  How do annual members and casual riders use Cyclistic bikes differently?

    *(this question was assigned to me.)*

2.  Why would casual riders buy Cyclistic annual memberships?

3.  How can Cyclistic use digital media to influence casual riders to become members?

**I will be producing a report with the following derivables:**

1.  A clear statement of the business task

2.  A description of all data sources used

3.  Documentation of any cleaning or manipulation of data

4.  A summary of the data analysis

5.  Supporting visualizations and key findings

6.  Top three recommendations based on my analysis

**During this case study, i will be working with data to help the company to find ways to maximize the quantity of annual memberships.My insights will support Cyclistic to understand how Annual members and Casual Riders use Cyclistic bikes differently, and with the analysis, help the company to achieve the goal of maximizing annual memberships**.

##3. Preparing

You can found the data collected in this [link](https://divvy-tripdata.s3.amazonaws.com/index.html) .

This data is the last 12 months(from Mar 2022 to Feb 2022) of Cyclistic trip data and there is no issues with credibility or bias on this data, it was collected by Cyclistic and it regards all users with no preference.

License can be found [here](https://ride.divvybikes.com/data-license-agreement). It's **prohibited** to use riders' personally identifiable information.

I verified the data integrity by cleaning and checking the data and there are no problems with the data.
