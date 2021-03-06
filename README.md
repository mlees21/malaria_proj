# Malaria Eradication and Health Financing Analysis
Published as part of the Lancet Commission on Malaria Eradication Sept 9th, 2019
https://www.thelancet.com/commissions/malaria-eradication

### The Lancet Commission for Malaria Eradication
Goal of the Commission: to synthesize existing evidence and new analyses that demonstrate that malaria eradication by 2050 is a bold but attainable goal
The commission was made up of 27 global experts in malaria research and eradication, and 10 UCSF secretariat representatives.
The work that is being presented is a fraction of the work done by the whole team and was a combined effort of the secretariat at UCSF and commission institutes.

#### _Malaria Eradication Within a Generation: Ambitious, Achievable and Necessary_
There are 8 total sections of _The Lancet_ publication, but we will just focus on number 6.
1. Malaria eradication: context, lessons from the past and alternatives
1. Modeling the trajectory for malaria eradication
1. Management and Operations
1. Biological challenges to eradication
1. Innovations and new tools
1. **FINANCING MALARIA ERADICATION**
   1. What is the current state of malaria financing?
   1. What is needed to eradicate malaria?
   1. What can be done to get there?
1. Leadership, governance, and accountability
1. Alignment with broader health and development goals

### Global Burden of Malaria
In 2017 there were 219 million malaria cases, 435,000 deaths in 87 endemic countries.

Malaria is a preventable and curable life-threatening disease caused by parasites that are transmitted to people through mosquitoes. 

https://www.who.int/news-room/fact-sheets/detail/malaria

https://www.cdc.gov/malaria/about/biology/index.html

### Global Focus on Malaria
In 2015 the United Nations General Assembly published their 17 global Sustainable Development Goals (SDGs) for 2030. Malaria eradication falls under SDG 3.

Sustainable Development Goal 3: Ensure healthy lives and promote well-being for all at all ages
* 3.2: By 2030, end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce neonatal mortality to at least as low as 12 per 1,000 live births and under-5 mortality to at least as low as 25 per 1,000 live births
* 3.3: By 2030, end the epidemics of AIDS, tuberculosis, malaria and neglected tropical diseases and combat hepatitis, water-borne diseases and other communicable diseases

57% of malaria deaths are from children under 5. Globally, from 2000 to 2016, the under-5 mortality rate dropped by 47%, and the neonatal mortality rate fell by 39%. Over the same period, the total number of under-5 deaths dropped from 9.9 million to 5.6 million.

https://sustainabledevelopment.un.org

### Infectious Disease Eradication Terms
 * Control - Reduction of disease incidence, prevalence, morbidity or mortality to an acceptable level as a result of deliberate efforts
 * Elimination -Reduction to zero of the incidence of a specified disease in a defined geographic area as a result of deliberate efforts
 * Eradication - Permanent reduction to zero of the worldwide incidence of infection caused by a specific agent as a result of deliberate efforts

### Health Financing Key Terms
Definitions supplied by IHME to use along with their data

**Development Assistance for Health (DAH) + Government Health Spending (GHE) + Out-of-Pocket Spending (OOP) + Prepaid Private Spending (PPP) = Total Health Spending (THE)**

**Total Health Spending:** The sum of all health spending in a country, this includes government health spending, prepaid private health spending, out-of-pocket health spending, and development assistance for health.

**Development Assistance for Health:** Financial and in-kind resources that are transferred through major health development agencies (such as UNICEF or the Bill & Melinda Gates Foundation) to low- and middle-income countries with the primary purpose of maintaining or improving health.

**Government Health Spending:** Spending for health care that comes from the government budget of a country and is not included in out of pocket spending, private spending or development assistance. This includes spending on public health systems, insurance and patient care.

**Out-of-Pocket Spending:** Payments made by individuals for health maintenance, restoration, or enhancement at or after the time of health care delivery, including health insurance copayments or payments devoted to deductibles. Health insurance premiums are not considered out-of-pocket.

**Prepaid Private Spending:** Health spending sources from non-public programs that are funded prior to obtaining health care, such as private health insurance and services provided for free by non-governmental agencies.


### The Data
**Health Financing** - Data created by the Institute for Health Metrics and Evaluation published in Financing Global Health 2018. These spending numbers are adjusted from the World Health Organization global health expenditure database. Values were calculated for each country for each year from 2000 to 2016 and broken down by source and disease group. Development assistance for health were estimated using data from international databases, all data refer to disbursements.

**Malaria Incidence** - World Health Organization Estimated Malaria Cases from the World Malaria Report 2018. This is from combined data from national malaria programmes and household surveys. Estimates were made by adjusting the number of reported malaria cases for completeness of reporting, the likelihood that cases were parasite positive, and the extent of health-service use

### Data Smoothing
Development assistance for health disbursements were smoothed using a local regression model. Smoothing variable (span/frac) was optimized to ensure the area under the curve to accurately reflect the total volume of disbursement over that period.

### Results
**2016 Total Spending on Malaria**
|         **Source**         | **2016 Spending on malaria** |            |
|:----------------------:|:------------------------:|:----------:|
|                        |      **US$ (millions)**      | **% of Total** |
| **Government**             | 1,204                    | 29%         |
| **Out-of-Pocket**          | 556                      | 13%         |
| **Prepaid private**        | 99                       | 2%          |
| **Development Assistance** | 2,418                    | 56%         |
|   Of which: in-country |                    1,668 |         69% |
|         Administration |                      473 |         20% |
|                 Global |                      277 |         11% |
| **Total**                | 4,277                    | 100%      |

Current (2016) total spending on malaria is around US$4.3 billion per year, of which 56% comes from development assistance. For these 106 malarious countries, reliance on development assistance for malaria is higher than for the health sector as a whole (14%) or for HIV (45%).

From the 2018 data, development assistance for malaria is mostly made up of contributions from:
 * the US government (43%)
 * the UK government (14%)
 * the Gates Foundation (13%)
 * the French government (3%). 
Eighty percent of all international malaria funding is channeled through the Global Fund, US government bilateral programs, and NGOs, which are also largely funded by the US government.

**Total health spending for all malarious countries**
![Total Spending Plot](/plots/106_countries_spending_bil.png)
![Total Spending Plot per capita](/plots/106_countries_spending_per_capita.png)
 * 106 countries had endemic malaria in 2000
 * Total malaria spending rose from US$1.2B to US$3.5B from 2000 to 2016
 * Per capita total malaria spending almost doubled from US$0.9 to US$1.9
 * This rise was driven by development assistance for malaria and overtook government malaria spending in 2008

**Eliminating Countries:**

For most of the eliminating countries, shown here as the bottom 30 malarious countries, the general trend in spending was that as total malaria expenditures increased, the number of malaria cases decreased and approached zero. 

![Bottom 30 Spending Plot](/plots/30_lowest_burden_countries_spending_bil.png) 
![Bottom 30 Spending Plot per capita](/plots/30_lowest_burden_countries_spending_per_capita.png)

The 30 countries with the lowest malaria incidence rates, most of the spending on malaria comes from the government - avg per capita US$1

**High Burden Countries:**

For the highest burden countries it was also observed that as total malaria expenditures increased, the number of malaria cases decreased. In general, variability in total spending in these countries is largely due to variability in donor spending, and less due to changes in domestic spending. 

![Top 30 Spending Plot](/plots/30_highest_burden_countries_spending_bil.png)
![Top 30 Spending Plot per capita](/plots/30_highest_burden_countries_spending_per_capita.png)
The 30 countries with the highest incidence rates are home to 86% of all malaria cases and recieve 75% of development assistance for malaria. These countries dominate the global spending patterns - Avg per cap US$4

Overall malaria decline ranging from 33% in the 30 most malarious countries to 84% in those with the lowest rates, with an overall average decline in the 106 countries of 44%.
