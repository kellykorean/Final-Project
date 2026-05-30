A foundational question in global economics is why some nations achieve significant economic prosperity while others face persistent developmental challenges. A prominent historical theory suggests that geographic location—specifically a country's distance from the equator—plays an important role in shaping its economy and standard of living. This project investigates that theory by exploring whether a meaningful relationship exists between global geography, economic output, and social development.

**Research Question**
Is a country's distance from the equator associated with higher macroeconomic prosperity (GDP per capita) and superior human development outcomes (Human Development Index scores)?

**Target Audience**
This analysis is designed for global development analysts, international investors, and policymakers who rely on data-driven frameworks to assess long-term socioeconomic trends and make informed cross-border investment or aid decisions.

**Data Sources**
To evaluate these relationships, this project integrates information from three distinct dimensions across a sample of 70 countries:

Economic Output: Real-time GDP per capita data retrieved directly from the World Bank API.

Social Well-being: Human Development Index (HDI) data tracking global health, education, and standard of living metrics.

Geography: Coordinate mappings (latitude and longitude) used to classify countries into regional and climate zones.

**Methodology**
Using absolute latitude as a proxy for distance from the equator, the project transforms geographic coordinates into actionable features like absolute distance metrics and localized climate-zone categories (Tropical, Subtropical, Temperate, and Cold). The data is compiled using an SQL database framework and analyzed using Exploratory Data Analysis (EDA), statistical correlation techniques, and predictive modeling.

**Key Findings**
Strong Latitudinal Correlation: The data reveals a strong positive correlation between a country's absolute distance from the equator and both its economic output (GDP per capita) and social well-being (HDI). As distance from the equator increases, these development metrics generally rise.

The "Tropical Gap": Statistical testing and regional grouping confirm that countries situated in designated Tropical zones consistently experience lower average GDP per capita and HDI scores compared to those located in Temperate and Cold zones.

Predictive Value of Geography: Linear regression models demonstrate that absolute latitude acts as a statistically significant predictor for both economic performance and human development scores, explaining a notable portion of the global variance.
