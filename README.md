# 📊 CodeX Market Analysis Dashboard

## 📖 Project Overview

This Power BI project analyses 10,000 consumer survey responses across 10 Indian cities for the energy drink market. It covers demographics, consumer preferences, purchase behaviour, competition, marketing and CodeX performance, and turns the findings into practical recommendations.

## 🎯 Business Problem

CodeX is a German beverage company that wants to enter the Indian energy drink market. It needs to know who the consumers are, what they want, which brands lead and what is stopping people from trying CodeX.

## 🗃️ Data Model

The project uses survey data of 10,000 respondents, modelled as a star schema with one fact table and two dimension tables.

**📈 Fact tables**
- `fact_survey_responses`: survey answers for each respondent

**📐 Dimension tables**
- `dim_repondents`: respondent details
- `dim_cities`: city and tier details

**Main fields used in the analysis**
- 👤 Respondent details: age group, gender, city and city tier
- 🥤 Consumption: consume frequency, typical consumption situations, consume time and consume reason
- 🛒 Purchase: purchase location, price range and packaging preference
- 🌱 Preferences: ingredients expected, interest in organic or natural options and health concerns
- 🏁 Brand: current brand, reasons for choosing a brand, brand perception and general perception
- ⭐ CodeX: heard before, tried, taste experience, improvements desired and reasons for not trying

## 🛠️ Tools

- 📊 Power BI
- 🧮 DAX
- 🔄 Power Query
- 🗂️ Data modelling
- 🎚️ Slicers and page navigation

## 📋 Dashboard Analysis

### 1. 🏠 Home

Introduces the project and links to every report page. Every page can be filtered by Age, Tier, Gender and City.

### 2. 👥 Demographics

**🔍 Key findings**
- The 19–30 age group is the largest with 5,520 of the 10,000 respondents.
- About 6.0K respondents are male, 3.5K female and 0.5K non-binary.
- Bangalore (2,828), Hyderabad (1,833) and Mumbai (1,510) have the most respondents.

**💡 Business implication:** The core market is young adults in the large metro cities.

### 3. 🥤 Consumer Preference

**🔍 Key findings**
- Caffeine is the most expected ingredient (3.9K), followed by vitamins (2.53K).
- Compact and portable cans are the most preferred packaging (3,984).
- About 60.45% of respondents have health concerns, and 5.0K are interested in organic or natural options.

**💡 Business implication:** Consumers want portable packaging and natural, health-conscious options.

### 4. 🛒 Purchase Behaviour

**🔍 Key findings**
- Supermarkets (4.5K) and online retailers (2.6K) are the top purchase locations.
- Sports and exercise is the most common consumption situation, especially for ages 19–30.
- The 50–99 price range is the most common (4,288), followed by 100–150 (3,142).

**💡 Business implication:** Start distribution in supermarkets and online, and focus campaigns on workout and study moments.

### 5. 🏁 Competition Analysis

**🔍 Key findings**
- Cola-Coka (2.5K), Bepsi (2.1K) and Gangster (1.9K) lead the current brands, while CodeX has about 1.0K.
- Brand reputation (2.7K) is the top reason for choosing a brand, followed by taste (2.0K).
- Overall brand perception is mostly neutral (59.74%), with 22.57% positive.

**💡 Business implication:** Reputation drives choice, so CodeX must build trust and compete on taste and availability.

### 6. 📣 Marketing

**🔍 Key findings**
- Online ads (4.0K) and TV commercials (2.7K) are the biggest marketing channels.
- The top reasons for not trying CodeX are not available locally (2.4K) and health concerns (2.3K).
- Never-tried rates are very high in Pune (95.6%), Mumbai (90.3%) and Delhi (89.3%).

**💡 Business implication:** Availability, health messaging and brand familiarity are the main barriers to trial.

### 7. ⭐ CodeX Performance

**🔍 Key findings**
- There are 980 CodeX respondents, 488 of whom tried it, with an average taste rating of 3.3.
- Reduced sugar content is the top improvement desired (3.0K), followed by more natural ingredients (2.5K).
- CodeX is strongest in Bangalore (292), Hyderabad (182) and Mumbai (156), and weakest in Lucknow (5).

**💡 Business implication:** Taste is average, so product improvements and growth in the strongest cities should come first.

## 📌 Executive Findings

| Area | Key Finding |
|---|---|
| 👥 Respondents | 10,000 survey responses across 10 cities, of which 980 are CodeX respondents. |
| 🎂 Age | The 19–30 age group is the largest with 5,520 respondents, followed by 31–45 with 2,376. |
| ⚧ Gender | About 6.0K male, 3.5K female and 0.5K non-binary respondents. |
| 📍 Cities | Bangalore (2,828), Hyderabad (1,833) and Mumbai (1,510) have the most respondents. |
| 🏁 Competition | Cola-Coka (2.5K) and Bepsi (2.1K) lead the current brands, while CodeX has about 1.0K. |
| 📣 Marketing | Online ads (4.0K) and TV commercials (2.7K) are the biggest marketing channels. |
| 🚫 Barriers | The top reason for not trying CodeX is that it is not available locally (2.4K), followed by health concerns (2.3K). |
| ⭐ CodeX | 488 respondents tried CodeX, and the average taste rating is 3.3. |

## ✅ Recommendations

1. 🎯 **Focus on young adults in the large metros.** Target ages 19–30 in Bangalore, Hyderabad and Mumbai first.
2. 🏪 **Fix availability before scaling marketing.** Improve supermarket and online retail presence.
3. 🌱 **Build trust and health credibility.** Offer natural or reduced-sugar options and communicate ingredients clearly.
4. 📣 **Use the right channels.** Lead with online ads and TV, and add gym and fitness partnerships.
5. 🧪 **Improve the product.** Reduce sugar, use more natural ingredients and widen the flavour range.
6. 💰 **Price in the sweet spot.** The 50–99 range is the most common, followed by 100–150.

## 🏆 Final Business Conclusion

The CodeX opportunity is in a young, metro-based consumer who drinks energy drinks for energy, focus and workouts, but the brand is held back by low availability, low familiarity and health concerns.

The data points to a connected chain:

Low availability and awareness -> few consumers try CodeX -> competitors keep brand reputation and market share -> average taste experience does not build loyalty.

The growth plan should work in the opposite direction:

Improve availability -> build trust and health credibility -> improve taste and ingredients -> then scale marketing.

The main lesson from the analysis is that growth should be targeted. The strongest opportunity is the 19–30 age group in the cities where CodeX is already strongest.

## 🔗 Live Dashboard

### [📊 View the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTU5MDUyZjEtMDBlMy00ODk5LTllZjMtNGU4ZDUzN2ZkZDg0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

### [⬇️ Download the Power BI File (.pbix)](Food_Beverages_Project.pbix?raw=true)
