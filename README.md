**Exploratory Analysis for Daily Water Intake and Hydration Level**

<img width="1024" height="1074" alt="ChatGPT Image Jan 5, 2026, 03_49_04 PM" src="https://github.com/user-attachments/assets/5a9f5e5f-381d-4699-b50d-4a8279ebdfa0" />


**1.   Introduction**

Water is essential for maintaining good health and supporting vital body functions, including regulating body temperature, transporting nutrients, removing waste, and ensuring proper organ function. Adequate daily water intake is crucial for maintaining optimal hydration, which directly influences physical performance, cognitive function, and overall well-being. However, hydration requirements differ among individuals due to factors such as age, gender, body weight, physical activity level, and environmental conditions, particularly weather.

This exploratory analysis investigates a dataset containing information on Age, Gender, Weight (kg), Daily Water Intake (liters), Physical Activity Level, Weather, and Hydration Level. The dataset comprises participants grouped by physical activity level (low, moderate, and high) across different weather conditions (cold, normal, and hot). It provides an opportunity to examine how demographic, physiological, and environmental factors influence daily water intake and overall hydration status.

The primary objective of this study is to identify patterns, trends, and relationships among these variables to better understand the key determinants of hydration. Specifically, the analysis examines hydration status by age and weight, evaluates gender distribution, and assesses average daily water intake across varying levels of physical activity and weather conditions. These insights help identify factors associated with good and poor hydration outcomes. Understanding the interaction between these variables is essential for developing effective health interventions, personalized wellness strategies, and evidence-based recommendations. The findings can support public health initiatives, improve preventive healthcare planning, and assist individuals in adopting healthier hydration habits based on their lifestyle and environmental conditions.

The results of this analysis are particularly valuable to public health agencies, healthcare providers, fitness professionals, nutritionists, digital health organizations, and wellness product manufacturers seeking to promote healthier lifestyles through targeted hydration and physical activity initiatives. The dataset is analyzed using Microsoft Excel, where data exploration and visualization techniques are applied to uncover meaningful insights into daily water intake and hydration levels.


<img width="975" height="417" alt="image" src="https://github.com/user-attachments/assets/0cb6c601-9433-409e-9257-a086e4abfed9" />


**2. Story of Data**

**Data Source:** The dataset used in this study is a secondary dataset obtained from Kaggle.com.

**Data Structure:** The dataset is organized in a tabular format consisting of rows and columns, where each row represents an individual participant and each column represents a specific variable. The key features included in the dataset are Age, Gender, Weight (kg), Daily Water Intake (liters), Physical Activity Level, Weather, and Hydration Level. These variables provide demographic, physiological, lifestyle, and environmental information that enables a comprehensive exploration of the factors influencing daily water intake and hydration status.

**Story Data is Telling:** The dataset tells a story about the relationship between daily water intake and hydration level, highlighting how demographic factors (age, gender, and weight), lifestyle factors (physical activity level), and environmental conditions (weather) collectively influence an individual's hydration status. It reveals patterns in water consumption across different groups and identifies the key factors associated with good and poor hydration. These insights can be used to support healthier hydration habits, inform wellness initiatives, and guide data-driven decisions in public health and preventive healthcare.


**3. Data Splitting and Preprocessing**

Data Cleaning: To ensure a smooth and reliable analysis process, the dataset was first validated by checking for missing values, empty rows, and duplicate records. The verification confirmed that the dataset was clean and free from inconsistencies, making it suitable for analysis. To improve readability and usability, the column headers and cell contents were formatted for better visibility, the top row was frozen to facilitate easier navigation, and the dataset was converted into a structured Microsoft Excel table.

Data Transformation: No significant data transformation was required for this analysis, as the dataset was already well-structured and suitable for analysis following the data validation and preparation stage. The variables retained their original formats, and no additional columns, calculated fields, or data type modifications were necessary. Consequently, the analysis proceeded directly to data exploration and visualization using the prepared dataset.

Data Splitting: The dataset was divided into two main categories to facilitate a more focused analysis and provide clearer insights into distinct aspects of the data. This approach made it easier to identify patterns, compare trends, and interpret the relationships between the variables within each category.

**A. Category One** — Independent value

   Gender

   Physical Activity Level

   Weather

   Hydration Level

**B. Category Two** — Dependent value

   Age

   Weight

   Daily Water Intake

**Industry Context:** This analysis is particularly relevant to the healthcare and wellness industry, where maintaining adequate hydration is recognized as a key component of overall health and disease prevention. It is applicable to the public health, sports and fitness, nutrition, and digital health sectors. Organizations within these industries can use the results to develop personalized hydration recommendations.

**Stakeholders:** This project may include a wide range of stakeholders, including public health agencies, healthcare providers, nutritionists, fitness professionals, digital health companies, wellness product manufacturers, researchers, educational institutions, corporate organizations, and the general public seeking to promote healthier lifestyles through targeted hydration and physical activity interventions.

**Value to the Industry:** Within the healthcare and wellness industry, success is defined by improving health outcomes and enhancing quality of life through evidence-based interventions that encourage sustainable healthy behaviors. Promoting adequate hydration, regular physical activity, and balanced nutrition helps reduce the incidence of preventable diseases, supports preventive healthcare, and contributes to healthier, more productive populations.

**4. Potential-Analysis**

The main areas identified for potential analysis during the pre-analysis phase are outlined below.

·       Gender Analysis by Daily Water Intake

·       Physical Activity Level by Age

·       Weather Analysis by Daily Water Intake

·       Hydration Level by Weight

·       Physical Activity Level by Weight

·       Physical Activity Level by Daily Water Intake

·       Gender analysis by Weight

·       Hydration Level Analysis by Age

**Initial Insights**

·       A gender hydration gap could indicate the need for gender-specific hydration recommendations.

·       Physical activity may decline progressively with age, potentially due to occupational demands, health constraints, or lifestyle changes.

·       Higher temperatures are likely associated with increased daily water intake due to greater fluid loss through sweating.

·       Individuals with higher body weight may require greater water intake to achieve optimal hydration levels.

·       Individuals within a moderate weight range may display higher activity levels compared to underweight or obese groups.

·       Higher physical activity levels are likely associated with increased water consumption.

·       Males may show higher average body weight compared to females, reflecting physiological and muscular differences.

·       Older age groups may show lower hydration levels, possibly linked to reduced thirst sensation or health conditions.

**5. In-Analysis**

**Analysis** - Gender Analysis by Daily Water Intake

Observations

Male slightly lead with 42802.02 liters daily while Female consume 42771.31 liters daily

Pre-Insights

A clear signal that both genders understood the importance of hydration.

**· Analysis** - Hydration Level by Count of Weight

Observations

Good hydration level clearly leads by 80% while Poor hydration accounts for 20%

Pre-Insights

This indicates that the majority of individuals in the dataset maintain adequate hydration. However, the one in five participants with poor hydration suggests that a notable proportion may still be at risk of dehydration.

**·  Analysis** - Physical Activity Level by Count of Age

Observations

High physical activity clearly tops with 10,069 followed by Low physical activity individuals with 10,011, whereas the Moderate physical activity individuals show the lowest of 9,920

Pre-Insights

Investigate why moderate physical activity shows lowest individuals and assess if there is a hidden health challenges among the individuals.

**·  Analysis** - Weather Analysis by Daily Water Intake

Observations

Hot weather indicates highest daily water intake of 34,304.61 liters while the Normal weather accounts for 26,837.4 liters daily intake.  Cold weather account for the lowest daily intake of 24,431.32 liters.

Pre-Insights

Cold weather conditions may correspond with lower water consumption, which may result to an increased dehydration risk.

**·  Analysis** - Physical Activity Level by Weight

Observations

High physical activity tops by 33.50% of the total weight while Low physical activity shows 33.42% of the total weight. Moderate physical activity account for 33.08% of the total weight

Pre-Insights

The minimal differences among the three groups suggest that body weight is evenly distributed regardless of physical activity level, indicating that other factors may have a greater influence on weight within this dataset.

**·  Analysis** - Physical Activity Level by Daily Water Intake

Observations

High physical activity tops with 33,462.42 liters of daily water intake follwed by Moderate physical activity with 28,103.23 liters intake daily whereas, Low physical activity account for 24,007.68 liters which is the lowest.

Pre-Insights

Participants with higher physical activity levels consume more water, likely due to the increased fluid loss associated with exercise and other strenuous activities. This highlights the importance of adjusting water intake according to activity level to maintain adequate hydration and support overall health and physical performance.

**·  Analysis** - Hydration Level Analysis by Age

Observations

77.99% of the total age shows good hydration level, while 22.01% shows Poor Hydration level

Pre-Insights

This suggests that adequate hydration is common among most age groups in the dataset. However, the proportion with poor hydration highlights the need for targeted awareness and interventions to improve hydration among individuals who may be at greater risk.

**6. Post-Analysis and Insights**

·       14,968 female participants account for 42771.31 liters of daily water intake at an average of 2.86 liters per person. Among the population 5005 engaged in high physical activity, 4989 in low physical activity and 4974 engaged in a moderate physical activity with the respective daily water intake of 16623.38 liters, 11992.32 liters and 14155.61 liters. 78% of hydration by age is consider good while 22% is consider poor meanwhile, 80% hydration level by weight is consider good while 20% is consider poor. During the Hot weather daily water intake is increased by 40.3%, meanwhile on the Normal weather level only 31.4% is consume daily while during the Cold weather daily intake is reduced to 28.3%  

·       15,032 male participants account for 42,802.02 liters of daily water intake at an average of 2.85 liters per participant. The physical activity distribution includes High 5064, Low 5022 and moderate 4946 with a daily water intake of 16839.04 liters, 12015.36 liters and 13947.62 liters respectively. During Hot weather daily water intake is increase by 39.8%, compared to Cold weather where daily intake is decreases to 31.3%, meanwhile on a normal weather daily water intake is at 31.4%. 78% of hydration level by age is consider good while 22% is consider poor meanwhile, 80% hydration level by weight is consider good while 20% is consider poor.

·       3,386 participant which include 1,732 males and 1,654 females engaged in High physical activity during the cold weather and their total daily water intake is 9744.23 liters at an average of 2.88 liters. 96% of hydration level by age is consider good while 4% is consider poor meanwhile, 97% hydration level by weight is consider good while 3% is consider poor.

·       3,259 participant which include 1,637 males and 1,622 females engaged in low physical activity during the cold weather and their total daily water intake is 6547.11 liters at an average of 2.01 liters. 80% of hydration level by age is consider poor while 20% is consider good meanwhile, 23% hydration level by weight is consider good while 77% is consider poor.

·       3,367 participant which include 1,682 males and 1,685 females engaged in Moderate physical activity during the cold weather and their total daily water intake is 8,139.98 liters at an average of 2.42 liters. 60% of hydration level by age is consider good while 40% is consider poor meanwhile, 63% hydration level by weight is consider good while 37% is consider poor.

·       During Hot weather 3,383 participant including 1,703 males and 1,680 females engaged in High physical activity and their total daily water intake is 13,197.8 liters at an average of 3.90 liters.  hydration level by age and weight is consider 100% good.

·       During Hot weather 3,434 participant including 1,706 males and 1,728 females engaged in Low physical activity and their total daily water intake is 9987.41 liters at an average of 2.91 liters. 96% of hydration level by age is consider good while 4% is consider poor meanwhile, 97% hydration level by weight is consider good while 3% is consider poor.  

·       During Hot weather 3,264 participant including 1,596 males and 1,668 females engaged in Moderate physical activity and their total daily water intake is 11,119.4 liters at an average of 3.41 liters.  hydration level by age and weight is consider 100% good.

·       3,330 participant which include 1,621 males and 1,671 females during Normal weather engaged in High physical activity and their total daily water intake is 10,520.38 liters at an average of 3.19 liters. Hydration level by age and weight are consider 100% good.

·       3,318 participant which include 1,679 males and 1,639 females during Normal weather engaged in Low physical activity and their total daily water intake is 7,473.16 liters at an average of 2.25 liters. 43% of hydration level by age is consider good while 57% is consider poor meanwhile, 46% hydration level by weight is consider good while 54% is consider poor.

·       3,289 participant which include 1,668 males and 1,621 females during Normal weather engaged in Moderate physical activity and their total daily water intake is 8,843.85 liters at an average of 2.69 liters. 86% of hydration level by age is consider good while 14% is consider poor meanwhile, 90% hydration level by weight is consider good while 10% is consider poor.

**7.    Data visualization and Charts**

<img width="510" height="311" alt="image" src="https://github.com/user-attachments/assets/e6bef90a-70f1-47ce-9fe6-e25e5251e4db" />

This chart shows Male slightly lead with 42802.02 liters daily while Female consume 42771.31 liters daily.


<img width="336" height="327" alt="image" src="https://github.com/user-attachments/assets/5e6308fa-6691-45a3-877a-3700bf19892c" />


This pie chart indicates that hot weather accounts for the highest daily water intake of 34,304.61 liters while the normal weather accounts for 26,837.4 liters daily intake. Cold weather account for the lowest daily intake of 24,431.32 liters.

<img width="377" height="287" alt="image" src="https://github.com/user-attachments/assets/8ba71a4b-6f4f-4bba-bce1-f45a4ace3d31" />

The column chart indicates that good hydration level clearly leads by 80% while Poor hydration accounts for 20%.

<img width="583" height="321" alt="image" src="https://github.com/user-attachments/assets/f765c4d0-a75e-4f6d-bf44-040926c7fda9" />

This shows that high physical activity clearly tops with 10,069 followed by Low physical activity individuals with 10,011, whereas the Moderate physical activity individuals show the lowest of 9,920.

<img width="389" height="309" alt="image" src="https://github.com/user-attachments/assets/ebafd1e1-a8af-4717-a3dc-9d907aa7bc98" />

This shows high physical activity tops with 33,462.42 liters of daily water intake followed by Moderate physical activity with 28,103.23 liters intake daily whereas, Low physical activity account for 24,007.68 liters which is the lowest.

<img width="409" height="285" alt="image" src="https://github.com/user-attachments/assets/b41ada9c-2b13-4032-909b-87d66a3ec284" />

This chart shows that 77.99% of the total age shows good hydration level, while 22.01% shows poor hydration level.

<img width="351" height="300" alt="image" src="https://github.com/user-attachments/assets/357b186f-a838-4184-901f-57131671e575" />

This chart indicates that female shows an average weight of 77.03kg while male shows 76.67 kg.

<img width="379" height="278" alt="image" src="https://github.com/user-attachments/assets/59cfdbec-d7a5-4cb3-92ee-e4e2360bd9e4" />

This chart shows high physical activity tops by 33.50% of the total weight while Low physical activity shows 33.42% of the total weight. Moderate physical activity account for 33.08% of the total weight.


**8. Post Analysis Recommendations**

· Implement seasonal hydration guidelines, emphasizing increased water intake during hot weather and proactive hydration reminders during cold weather, where intake is consistently lower.

· Prioritize hydration education for individuals with low physical activity, particularly in cold and normal weather, where up to 80% poor hydration by age and 77% by weight were observed and encourage minimum daily intake benchmarks (≥2.5 L) for sedentary individuals to reduce dehydration risk.

· Encourage moderate physical activity as a gateway to improved hydration habits, as moderate activity groups showed substantially better hydration levels than low activity groups. Integrate also hydration prompts into fitness and wellness programs to reinforce water consumption alongside activity routines.

· Adopt age and weight adjusted hydration recommendations, especially for older or heavier individuals, to prevent underhydration, using analytics-driven thresholds rather than universal intake recommendations to improve hydration accuracy.

· Leverage wearable devices and mobile health apps to:

- Track daily water intake

- Trigger hydration reminders based on weather and activity level

- Flag dehydration risk for low-activity users

· Employers should implement hydration policies in both indoor and outdoor workplaces, especially during cold and hot seasons by providing easy access to drinking water and visual hydration cues in offices, factories, and public spaces.

**8. Conclusion**

This analysis demonstrates that physical activity level and weather conditions are the strongest determinants of hydration adequacy, while age and weight-based hydration outcomes improve significantly with increased activity and environmental heat. The findings highlight the need for targeted hydration interventions for low-activity individuals, particularly during cold and normal weather conditions, where dehydration risk is often underestimated.

**9. Reference**

Kaggle.com
