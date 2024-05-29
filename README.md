# Product-Funneling-SaaS-FinTech-DataAnalytics
Executive Summary:
Using SQL, Python, and Power BI, I pulled order status data from the database and created a dashboard to track orders through the funnel. After identifying that the largest revenue opportunities are to increase user interaction rate and completed login attempts, I recommend that the product team implements a few adjustments that will lead to higher conversion:

Copy changes within the workflow
Reminder emails/texts
Better client relationships
Business Problem:
Completed orders are essential for this SaaS Fintech company since they're directly tied to revenue. Product and sales stakeholders have noticed that the product has a lower conversion rate than expected (based on users who start orders vs. complete the order). How can we determine where users are falling out of the workflow and make product adjustments to encourage users to complete their orders?

Screenshot 2024-05-25 at 2 05 24 PM

Methodology:
SQL query that extracts, cleans, and transforms the data from the database.

Build a dashboard in Power BI that tracks the number of orders in each status.

Conduct a more detailed funnel analysis in Python to simulate changes and determine the best areas of opportunity.

Skills:
SQL: CTEs, Joins, Case, aggregate functions

Power BI: Dax, writing functions, ETL, calculated columns, data visualization, data modeling

Python: Pandas, Matplotlib, Numpy, Writing functions, building a product funnel, statistics

Results & Business Recommendation:
Creating a dashboard to track product orders gives product and sales stakeholders visibility into the product funnel both overall and for specific clients. Because of democratizing this data, stakeholders are now able to self serve, and the analytics team now has 5 less hours of ad hoc requets per week. This analysis showed us that almost 50% of orders fall out before entering the workflow, and less than 25% of users enter their correct banking credentials to connect their account. According to the model built in Python, increasing user interaction rates by 1% will result in $285 more in daily revenue and increasing completed bank login attempts by 1% will result in $405 more in daily revenue.

Screenshot 2024-05-25 at 2 04 48 PM

Because the biggest revenue impacts will likely come from increasing the user interaction rate & completed login attempts, I recommend a few product adjustments:

Send inactive users reminder emails and texts to encourage them to enter the platform to complete their order.
Work with clients (mortgage lenders) to help coach the users through the process and see the value in doing so.
Add copy at the beginning of the workflow stating that the process only takes 5 min, and feature a progress bar throughout.
Add copy at the bank login page to encourage users to look up their credentials to make sure they're correct.
I believe these adjustments will best tackle the largest workflow fallout points, increase conversion & revenue, and save the analytics team hours per week from a decrease in ad hoc requests.

Next Steps:
AB Test copy within the workflow
Train clients and users
Measure email and text open & click rates 
