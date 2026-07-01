**OTT Platform Merger Analysis — Lio & Jotstar**


Power BI dashboard analyzing the merger of LioCinema (telecom-owned streaming platform) and Jotstar (content-rich OTT platform), covering January–November 2024 performance data.



Problem Statement

Lio, one of India's top telecom companies, is merging with Jotstar to combine LioCinema's large subscriber base with Jotstar's content library — creating a unified OTT platform. Management needed a data-driven view of user behavior, subscription trends, and content performance across both platforms before finalizing the merger strategy.

Goal: Analyze both platforms independently, identify strengths/gaps, and surface the data needed to make the combined platform — Lio-Jotstar — India's leading OTT service.





Business impact delivered:
- Proposed short-form content activation strategy projected to convert 8,900 inactive users, adding ~623K watch hours.

- Designed a 4-tier pricing restructure (Free / ₹99 / ₹199 / ₹249 telecom bundle) projecting 22% growth (50.6% → 72.3%) and ₹10.3M incremental monthly revenue

- Built subscription transition logic to classify plan migrations, map churn risk zones, and quantify revenue impact





Dashboard Structure

The report is split into 7 analytical pages, each answering a specific merger-planning question.

1. Content Analysis

Business question: What content do both platforms offer, and where are the gaps?


Distribution of content type (movies, shows, etc.) per platform
Switch visual: Total Content Items vs. Avg Run Time
Content distribution by genre — identifies genre imbalance post-merger


Technique: Used the "Group" option for the key insight card. Used Field Parameters as a measure selector to toggle a single visual between Total Content Items and Avg Run Time (avoids building duplicate visuals). Used AI to generate/validate DAX and calculated columns based on the use case.

2. Subscribers Analysis

Business question: What does the subscriber base look like, and how is it growing?


Monthly user trend (growth pattern, forecasting input for post-merger)
Users by city tier & age group
Active vs. inactive users by plan
% Paid vs. Free users (revenue stability indicator)


Technique: Calculated table — Platform — built with AI assistance for DAX and calculated columns.

3. Subscriber In-Activity Analysis

Business question: Where and why is churn happening?


Active/inactive rate by month
Inactive rate % by city, age group, subscription plan


Technique: Calculated table — Platform — DAX validated and built with AI assistance.

4. Subscriber Upgrade Patterns

Business question: Who is upgrading, and where should upsell campaigns focus?


Transition table: upgrade paths by city and age group
Upgrades by age group & city tier
Monthly upgrade trend


Technique: DAX measures and calculated columns built on the Both Subscribers table, with AI-assisted validation.

5. Subscriber Downgrade Patterns

Business question: Where is pricing failing, and what's driving churn to lower plans?


Transition table: downgrade paths by city tier and age group
Monthly downgrade trend
Downgrades by city tier & age group


Technique: DAX measures and calculated columns built on the Both Subscribers table, with AI-assisted validation.

6. Content Consumption Analysis

Business question: Who is actually engaging with content, and how much?


Average watch time by demography (city tier, age group, device type)
Average watch time by subscription plan


Technique: DAX measures and calculated columns built on the Both Subscribers table, with AI-assisted validation.

7. Revenue Analysis

Business question: What's driving revenue, and what's at risk?


Revenue by demography (age group, city, subscription plan)
Revenue by downgrade & upgrade users (financial impact of plan switching)
Revenue trend by month


Technique: DAX measures and calculated columns built on the Both Subscribers table, with the help of AI LLM's

Tools & Techniques


Power BI — data modeling, DAX, report design
Field Parameters — used as dynamic measure selectors to reduce visual duplication
Calculated Tables & Columns — used to unify LioCinema and Jotstar subscriber data into a single model
DAX — custom measures for churn, transitions (upgrade/downgrade), revenue attribution
AI-assisted DAX generation and validation, applied selectively based on scenario/use case complexity


Files


Dashboard link: [https://app.powerbi.com/view?r=eyJrIjoiNzMzNTU1NjctODFhNS00YTFhLWFhNzgtYTJhNjhhMzg4MzYxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9]

-Not able to upload data sets and dashboard file due to size issue.


Key Takeaway

The analysis reframes the merger from a data-combination exercise to a behavior-combination exercise — surfacing where the two platforms' user bases will align, conflict, or need active retention work post-merger.
