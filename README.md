# Czech-Banking-Analysis
📊Dashboard Power bi service - https://app.powerbi.com/groups/1174ebfa-ab4e-4191-9901-5f7713d742c1/reports/61aea913-cadc-4aaa-ac9a-ca88bde88fa3/3c2eea99d9539005409e?experience=power-bi
This project is on the datasets covers 1M records generated on a random basis involving 8 tables.
Description to complete project:
🚀Cloud usage : Aws & Snowflake--- Dump data into it and then fetch the data from S3 buckets into Snowflake through storage integration creating roles and policies in aws. Creating file format & stage for trust relationship.
                Then creating pipelines in snowflake through which new data will flow from s3 bucket to respective tables in snowflake.Also define auto_refresh because whenever data is dumped into s3 then our table in snowflake automatically updates.
                Also created stored procedures because whenever data is dropped in aws then automatically through task on schedulled time data will come in stored procedure table.
                Then i connect snowflake to the power bi and using sql queries i created tables dropped in the power bi and used them for dashboarding.

Here are some questions for which i tried to find out the answers:
What is the demographic profile of the bank's clients and how does it vary across districts?
How the banks have performed over the years. Give their detailed analysis year & month-wise.
What are the most common types of accounts and how do they differ in terms of usage and profitability?
Which types of cards are most frequently used by the bank's clients and what is the overall profitability of the credit card business?
What are the major expenses of the bank and how can they be reduced to improve profitability?
What is the bank’s loan portfolio and how does it vary across different purposes and client segments?
How can the bank improve its customer service and satisfaction levels?

Insights Gain & Suggestions :

1)  Among all cards  gold card is most common card which is used by customers across all regions.
2)  Maximum transactions done for house hold items and from HL.m. Praha district.
3)  Maximum transactions observed in the end of the month which is indication that maximum salaries credited in the
       end  of the month.
4)  As compare to female in almost every bank male customers are more but almost equivalent.
5)   37% of customers have close their banks its a very high risk like last alarm for banks to work on it.
6)   Few customer's about to get their inactive age 48-49, so bank manager should get notification 15 days before customers account get inactive so that he can send them notification as well to do transactions.

SUGGESTIONS:

1)  Launch a higher-tier gold card with even more exclusive benefits (e.g.. airport lounge access, higher cashback, concierge services to move the top     5-10% of gold users to a higher fee-paying tier..
2)  Implement a points-based loyalty program specifically for gold users that rewards frequency of use, not just the amount spent to increase stick-     			ness so that they don't switch to competitors..
3)  Introduce a 'smart bill manager' in the mobile app that predicts upcoming household expenses based on history and allow for one -click scheduling.
4)  Since the Average Age people belongs from 44-46 who are having maximum salaries and in the end of month so bank can send them offers to    	take home-loan or low interest rate shopping offers for groceries items and during the vacation period bank can offer them 
travel packages.
5) Bank must offer female customers on voucher cards or discount on cards for household items , etc.
6)  Since this group ( 48-49) has high capital, offer them a Premium/Gold Card upgrade with no fee for the first year, or a "Senior Wealth Consultation" session..
            
