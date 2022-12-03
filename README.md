# Annual-Base-Salary-Percentile-Estimation
A machine learning model is created on a subset of OWES dataset (Occupational Employment and Wage Statistics) 
The Occupational Employment and Wage Statistics (OEWS) program produces employment and wage estimates annually for nearly 800 occupations. These estimates are available for the nation as a whole, for individual states, and for metropolitan and nonmetropolitan areas; national occupational estimates for specific industries are also available.
The data used in this problem is a subset of the OEWS data, which include the 10-th percentile, 25-th percentile, 50-th percentile (a.k.a median), 75-th percentile, and 90-th percentile of the annual salary of a given combination of states, industries, and occupations.

Data
Independent Variables
There are three independent variable columns:

<br> PRIM_STATE </br>
<br> NAICS_TITLE </br>
<br> OCC_TITLE </br>

indicating the state, industry, and occupation.
In the PRIM_STATE variable, each category indicates a state postal abbreviation (like "CA", "TX", etc.) or "U.S" as the whole United States. When PRIM_STATE is "U.S", it means the percentiles are aggregated across all the states.
In thes NAICS_TITLE, each category indicates an industry sector name (like "Retail Trade", "Manufacturing") or "Cross-industry". When NAICS_TITLE is "Cross-industry", it means the percentiles are aggregated across all the industries.


Target Variables
There are 5 dependent (target) variable columns:

<br> A_PCT10 </br>
<br> A_PCT25 </br>
<br> A_MEDIAN </br>
<br> A_PCT75 </br>
<br> A_PCT90 </br>
indicating the 10-th percentile, 25-th percentile, median, 75-th percentile, 90-th percentile of the annual base salary given the state, industry, and occupation information.
