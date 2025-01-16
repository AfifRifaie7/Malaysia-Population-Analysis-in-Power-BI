# Malaysia-Population-Analysis-in-Power-BI

## Objective

Using dataset from Department of Statistics Malaysia (DOSM), create an interactive, functional and visual appealing single page Malaysia population dashboard using Power Bi. Demostrate Power BI data connection and shaping, data model and usage of calculated fields with DAX. Based on the dashboard, discuss insights based on the data, addressing the following questions: 

1. If birth rates and migration patterns remain unchanged, what is your projection for the workforce in Kuala Lumpur 20 years from now?
2. Describe notable trends in the birth and deaths chart by ethnicity.
3. Describe notable trends in the birth and deaths chart in overall.
4. Other insights.

## Data source

1. Population by State, Age, Sex, Ethnicity [Available Here](https://open.dosm.gov.my/data-catalogue/population_state)
2. Birth by State, Sex, Ethnicity [Available Here](https://open.dosm.gov.my/data-catalogue/births_annual_sex_ethnic_state) 
3. Death by State, Sex, Ethnicity [Available Here](https://open.dosm.gov.my/data-catalogue/deaths_sex_ethnic_state)

## Data modeling 

![image](https://github.com/user-attachments/assets/36f30b84-3410-41d9-a906-47b615be2057)

## Dashboard overview

![image](https://github.com/user-attachments/assets/59a50232-7b6f-4dab-baac-d7be19e3d92b)

## Discuss insights based on the data, addressing the following questions:

### 1. If birth rates and migration patterns remain unchanged, what is your projection for the workforce in Kuala Lumpur 20 years from now?

![image](https://github.com/user-attachments/assets/6f2f840a-d07e-4085-82e9-308c56eff3e2)

Chart 1: Age distribution chart, majority of workforce will be in their early 40’s to mid-50’s in 2042

Based on the last four years' trend of total population growth, estimated at 0.2% CAGR, Malaysia's
population is projected to be 34,031,383, increase of 2 million from the current total population. This
trend suggests that Malaysia’s workforce in 2042 will be characterized by an aging population with fewer
young workers entering the labor force which age between 15 to 64 (OECD). If current birth rates and
migration patterns remain unchanged, a significant portion of the workforce will be in their 40s to 50s, as
illustrated by the red box in the age distribution chart 1.

This pattern will have significant consequences on the labor force of the country. There may not be an
adequate workforce to sustain economic growth, necessitating labor dependency from other countries or
extensive need for improvement in mechanization, such as automation. Another effect of an aging
population is an increased dependency ratio (WBG), meaning more people will be entering the non-
productive age group. This will result in a smaller percentage of people directly contributing to the
economy.

Countries such as South Korea, France, and Finland, which also experience similar population growth(CIA),
have implemented policies to manage these demographic changes. Malaysia can adopt similar strategies to address these challenges, such as incentivizing higher birth rates, encouraging immigration, and
investing in automation and technology to boost productivity.

### CAGR calculation

![image](https://github.com/user-attachments/assets/4cb02ed4-4f7e-42b9-ba04-c77ba59cac5f)

### Population Growth calculation

![image](https://github.com/user-attachments/assets/1b0ea4f2-a643-4046-876a-e60a9498d9f9)

Figure 1: CAGR and Population Growth calculation

### 2. Describe notable trends in the birth and deaths chart by ethnicity.

![image](https://github.com/user-attachments/assets/56498531-6eea-4391-bc49-da91d9d46b48)

Chart 2: Birth and death trends for 3 major ethnic group in Malaysia

Over the years, total births have been in a declining stage for the three major ethnic groups in Malaysia.
The most noticeable decline is in the Chinese community, which saw a fall in total births from 115,429 in
2000 to 40,249 in 2022, approximately 65% fall. In 2021, the number of deaths surpasses total births rate.
This pattern is also observed in the Indian community, where the birth rate steadily decreased from
35,329 in 2000 to 17,439 in 2022, a decline of approximately 51%, and birth rate also crossed below the
death rate in 2021. For Malay community, the birth rate is also in a decreasing trend but is not as
significant. The total births in 2022 were 291,353, still slightly higher compared to the lowest recorded
year in 2006, which had 273,358 births.

The death rates for the three major ethnic groups in Malaysia indicate a similar pattern of steady increase
over the years, with a significant spike in 2020. This could be attributed to the COVID-19 pandemic that
affected the country.

### 3. Describe notable trends in the birth and deaths chart in overall.

![image](https://github.com/user-attachments/assets/3bf6c8b1-1df9-4579-b244-fead9ba40616)

Chart 3: Total birth and death trends in Malaysia

Overall, the birth rate appears steady growth from 2005 until it peaks in 2014 with total population of 30,708,600 then started to decline. The death shows steady increase over the years with peak on 2021. Decreasing in birth rate and decreasing in death rate pattern could suggest that Malaysia may face challenges of ageing population and lacking in meeting labor force demand in future. There are internal and external factors that affecting these results and it is noteworthy that the trend is similar across many countries around the world (Reuters).

### Other insights

![image](https://github.com/user-attachments/assets/557729d6-e5ac-4a80-8cab-133a3aad8038)

Chart 4: Age distribution for 3 Major Ethnic in Malaysia

Comparing the age distribution charts among Malay, Chinese, and Indian populations reveal interesting observations. The Bumi_Malay population has a higher and more sustained proportion of age groups from 0 to 40s. In contrast, the Chinese and Indian populations show middle-age dominance, with lower numbers in the younger age group especially newborn 0-4 years group. The number of males and females is equally distributed across all age groups and ethnics.

![image](https://github.com/user-attachments/assets/60463faf-4348-44c0-a9a7-758398583135)

Chart 5: Age distribution for Terengganu and W.P Kuala Lumpur

If we drill down each state more closely, Terengganu having the youngest population while W.P Kuala
Lumpur has the lowest younger population in Malaysia.
