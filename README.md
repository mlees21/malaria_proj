# Malaria Eradication and Health Financing
Margaret Lees
July 11th, 2019

The Lancet Commission for Malaria Eradication
Goal: to synthesize existing evidence and new analyses that demonstrate that malaria eradication by 2050 is a bold but attainable goal
27 commissioners
10 people on the UCSF secretariat
The work that is being presented is a fraction of the work done by the whole team and was a combined effort of the secretariat at UCSF and commission institutes.

### Global Burden of Malaria
in 2017 there were 219 million cases
435,000 deaths in 87 endemic countries
Malaria is a preventable and curable life-threatening disease caused by parasites that are transmitted to people through mosquitoes. 
https://www.who.int/news-room/fact-sheets/detail/malaria
https://www.cdc.gov/malaria/about/biology/index.html

### Global Focus on Malaria
Sustainable Development Goal 3: Ensure healthy lives and promote well-being for all at all ages
3.2: By 2030, end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce neonatal mortality to at least as low as 12 per 1,000 live births and under-5 mortality to at least as low as 25 per 1,000 live births
3.3: By 2030, end the epidemics of AIDS, tuberculosis, malaria and neglected tropical diseases and combat hepatitis, water-borne diseases and other communicable diseases
The UN’s SDGs  are a collection of 17 global goals set by the United Nations General Assembly in 2015 for the year 2030.
57% of malaria deaths are from children under 5
Globally, from 2000 to 2016, the under-5 mortality rate dropped by 47 per cent, and the neonatal mortality rate fell by 39 per cent. Over the same period, the total number of under-5 deaths dropped from 9.9 million to 5.6 million.

https://sustainabledevelopment.un.org

### Infectious Disease Eradication
Control - Reduction of disease incidence, prevalence, morbidity or mortality to an acceptable level as a result of deliberate efforts
Elimination -Reduction to zero of the incidence of a specified disease in a defined geographic area as a result of deliberate efforts

Eradication - Permanent reduction to zero of the worldwide incidence of infection caused by a specific agent as a result of deliberate efforts

### Malaria Eradication Within a Generation: Ambitious, Achievable and Necessary
1. Malaria eradication: context, lessons from the past and alternatives
2. Modeling the trajectory for malaria eradication
3. Management and Operations
4. Biological challenges to eradication
5. Innovations and new tools
6. FINANCING MALARIA ERADICATION
 * What is the current state of malaria financing?
 * What is needed to eradicate malaria?
 * What can be done to get there?
7. Leadership, governance, and accountability
8. Alignment with broader health and development goals


### Health Financing Key Terms
Development Assistance for Health + Government Health Spending + Out-of-Pocket Spending + Prepaid Private Spending = Total Health Spending

Total Health Spending: The sum of government health spending, prepaid private health spending, out-of-pocket health spending, and development assistance for health. Total health spending does not include indirect health spending, such as lost wages due to illness or transportation costs; informal care (spending on care provided by a family member or by traditional healers); or illegal transactions.
Development Assistance for Health: Financial and in-kind resources that are transferred through major health development agencies (such as UNICEF, the United Kingdom’s Department for International Development, or the Bill & Melinda Gates Foundation) to low- and middle-income countries with the primary purpose of maintaining or improving health. 
Development assistance for malaria, as with development assistance for health, can be expressed as a commitment (by the donor to the recipient), a disbursement (from the donor to the recipient), or an expenditure (of the monies disbursed by the recipient)
Country development assistance for health: Development assistance for health, financial or in-kind, targeting a specific country. 
Administrative development assistance for health: The administrative costs of running development health programs born by the channel of assistance.
Global development assistance for health: Development assistance for health projects that do not target a specific country. These include research and resources for global governance. 
Government Health Spending: Spending for health care that is derived from domestic sources and is mutually exclusive from out-of-pocket, prepaid private, and development assistance spending. Government spending includes spending on public health system infrastructure and government-provided social health insurance, and patient care.
Out-of-Pocket Spending: Payments made by individuals for health maintenance, restoration, or enhancement at or after the time of health care delivery, including health insurance copayments or payments devoted to deductibles. Health insurance premiums are not considered out-of-pocket.
Prepaid Private Spending: Health spending sources from non-public programs that are funded prior to obtaining health care, such as private health insurance and services provided for free by non-governmental agencies.


### The Data

Health Financing
Supplied by the Institute for Health Metrics and Evaluation published in Financing Global Health 2018
Adjusted from the World Health Organization global health expenditure database
Malaria Incidence
World Health Organization Estimated Malaria Cases from the World Malaria Report 2018
Combined data from national malaria programmes and household surveys
Values were calculated for each country for each year from 2000 to 2016 and broken down by source and disease group.
Development assistance for health were estimated using data from international databases, all data refer to disbursements.
Estimates were made by adjusting the number of reported malaria cases for completeness of reporting, the likelihood that cases were parasite positive, and the extent of health-service use

### Data Smoothing
Development assistance for health disbursements were smoothed using a local regression model
DAH disbursements were smoothed using a local regression model
Smoothing variable (span) was optimized to ensure the area under the curve to accurately reflect the total volume of disbursement over that period
Locally Weighted Regression Smoothing
Assume for each window of data the function is locally linear
loess keeps the number of points used in the local fit the same. This number is controlled via the span argument, which expects a proportion. For example, if N is the number of data points and span=0.5, then for a given x, loess will use the 0.5 * N closest points to x for the fit.
When fitting a line locally, loess uses a weighted approach. Basically, instead of using least squares, we minimize a weighted version:

### Results
Current Total Spending on Malaria
|         Source         | 2016 Spending on malaria              |
|:----------------------:|:------------------------:|:----------:|
|                        |      US$ (millions)      | % of Total |
| Government             | 1,204                    | 29         |
| Out-of-Pocket          | 556                      | 13         |
| Prepaid private        | 99                       | 2          |
| Development Assistance | 2,418                    | 56         |
|   Of which: in-country |                    1,668 |         69 |
|         Administration |                      473 |         20 |
|                 Global |                      277 |         11 |
| Total                  | 4,277                    | 100        |

Estimates of current malaria spending from both international and domestic sources in 2016 are presented in table 2. In summary, current total spending on malaria is around US$4.3 billion per year, of which roughly 56% comes from development assistance. Focusing on in-country spending (excluding development assistance for administration and global purposes), development assistance is 47% of total malaria spending. For these 106 countries, reliance on development assistance for malaria is higher than for the health sector as a whole (14%) or for HIV (45%).
We examined development assistance for malaria in 2018 by source and channel. The US government provides 43% of all development assistance for malaria, followed by the UK government (14%), the Gates Foundation (13%), and the French government (3%). Eighty percent of all international malaria funding is channeled through the Global Fund, US government bilateral programs, and NGOs, which are in turn largely funded by the US government.

![Total Spending Plot](/plots/106_countries_spending_bil.png)

106 countries had endemic malaria in 2000
Total malaria spending rose from US$1.2B to US$3.5B from 2000 to 2016
Per capita total malaria spending almost doubled from US$0.9 to US$1.9
This rise was driven by development assistance for malaria and overtook government malaria spending in 2008

