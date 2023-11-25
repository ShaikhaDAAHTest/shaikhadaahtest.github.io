---
title: "Spatial Data"
permalink: /SD/
author_profile: false
---

## Spatial Data

#### Selecting the Source: Fielding's Travel Guide to Europe

My choice of source material for this project was "Fielding's Travel Guide to Europe" by Jones, Lombard C Ill. This particular guide stood out due to its extensive coverage of various European countries, providing a rich and diverse cultural and historical context. The guide meticulously details hotels, nightclubs, restaurants, and other points of interest in each area, making it an ideal source for a project focused on spatial data in the humanities.

I chose to concentrate on the sections detailing restaurants because they offered an intriguing opportunity to explore and compare the culinary cultures of different European regions. The guide's comprehensive descriptions of restaurants, including their locations, key features, and signature dishes, were a gold mine of information waiting to be analyzed and visualized in a new, innovative way.

### Selection and Visualization

#### Initial Steps: Area Selection and Data Extraction

I began by selecting four diverse regions for this study: Austria, Belgium, Denmark, and England. These countries were chosen for their varied sizes, cultures, and historical backgrounds, which promised an engaging comparative analysis. To gather the data, I extracted the restaurant sections from each country's chapter in the guide and compiled them into a single document for further processing.

#### Overcoming OCR Challenges and Data Refinement

The initial hurdle in this process was the imperfect Optical Character Recognition (OCR) of the source text. The inaccuracies in the OCR output necessitated a correction phase, which I initially approached with the assistance of ChatGPT. Surprisingly, ChatGPT went beyond mere correction, providing concise summaries of each restaurant, including essential details like names, exact locations, key features, and notable dishes. This enriched summary served as a more refined dataset, suitable for spatial analysis and mapping.

#### Creating and Refining the Dataset

With the summaries in hand, I attempted to organize this information into a CSV file. The first attempt, facilitated by ChatGPT, resulted in a complex file structure that didn't quite meet the project's needs. I refined my approach, feeding the AI-generated summaries back into ChatGPT with instructions to format them into a simplified CSV structure. This process involved separating each restaurant's details with commas and organizing the data into rows and columns, each representing a different aspect of the restaurant information. The result was a streamlined dataset, perfectly structured for the next phase of the project.

#### Geolocation and Visualization

The final step in data preparation involved inputting the formatted data into Google Sheets, where it was organized into clearly defined columns. I then utilized the Geolocator extension to convert the textual location data into precise geographic coordinates, namely longitude and latitude values for each restaurant. 

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSkTflaEm-NwQ6tlFk6zbmljM8eXHbuHXnQfm_-RnxuOFaLTKu6-g7IPjvhOjiXNtz4SZNqJep3OVEW/pubhtml" width="800" height="1200"></iframe>

This geocoded data was then exported as a CSV file and imported into Kepler.gl, a great, free tool for spatial data visualization. The culmination of this process was the creation of a detailed geospatial map. This map visually represented the distribution and key attributes of the restaurants across the four selected European regions, bringing to life the rich culinary landscapes of Austria, Belgium, Denmark, and England.

### Analyzing and Interpreting the Data

![alt text](/assets/images/overall.png)
![alt text](/assets/images/denmark.png)
![alt text](/assets/images/england.png)
![alt text](/assets/images/austria.png)
![alt text](/assets/images/belgium.png)

In order to analyze the data, I asked chatgpt to give me a list of questions I should aim to answer or ponder when looking at the details and geospatial data and to help me thoroughly analyze the data. I used the questions to create the following subsections for analysis:

#### Distribution Analysis
 
- How are these top-rated restaurants geographically distributed within each country?
- Are there any noticeable clusters of high-quality restaurants in specific cities or regions?

The dataset includes a diverse range of restaurants spread across the cities of Vienna, Brussels, Copenhagen, Salzburg, and London. Vienna, Austria, shows a notable concentration of restaurants, suggesting a vibrant culinary scene. In London, England, there is a significant density of restaurants, particularly in central areas like Coventry Street, Jermyn Street, and Piccadilly, indicating a cluster of high-quality dining options in the city's heart.

#### Proximity to Tourist Attractions
- How close are these restaurants to major tourist attractions or landmarks?
- Does the proximity to tourist areas correlate with the density of high-rated restaurants?

Many restaurants, especially in Vienna and London, are located near major tourist attractions. This includes areas like the historic center of Vienna and central London near Leicester Square and Piccadilly Circus. There seems to be a correlation between the proximity to tourist areas and the density of high-rated restaurants, particularly in city centers known for tourism. Perhaps this is more a reflection on the authors own experience and stay rather than the actual density of restaurants, but this is a given as the source is from one point of view.

#### Cuisine Variety
- What types of cuisine are most common in the top-rated restaurants in each country?
- Are there any noticeable trends in cuisine types in specific areas or cities?

In Austria, traditional Austrian and international cuisines dominate, with specific mentions of Swedish-rustic and Balkan styles. Belgium's offerings are diverse, with a focus on seafood and international cuisine. Denmark's restaurants also show a preference for international cuisine, seafood, and traditional Danish dishes. London's culinary scene is cosmopolitan, with a wide range of cuisines including French, Italian, Hungarian, and traditional English fare.

#### Price Range Analysis
- How do the price ranges of these top-rated restaurants vary across different cities or regions?
- Is there a correlation between the restaurant's location and its price range?

The price ranges vary, with some restaurants like Kahlenberg in Austria and the Petit Louvain in Belgium offering meals at modest prices, while others, particularly in London, are described as elegant with high prices, suggesting a more upscale dining experience.

#### Accessibility Analysis
- How accessible are these restaurants in terms of public transportation options?
- Are the top-rated restaurants more concentrated in areas with higher accessibility?

Given their central locations in major cities, most restaurants are likely highly accessible via public transportation. Top-rated restaurants are more concentrated in areas with higher accessibility, especially in urban centers.

#### Historical vs. Modern Establishments
- What is the balance between historically established restaurants and modern, newly opened ones in each country?
- Do historical restaurants tend to cluster in certain parts of the cities?

The dataset includes both historical establishments like “The Three Hussars” in Vienna and modern ones like “Richmond Hotel & Au Coq d’Or Restaurant” in Copenhagen. In London, historical restaurants like “George and Vulture” and “Rule’s” indicate a preference for tradition in certain parts of the city.

#### Comparative Regional Analysis
- How does the concentration and variety of top-rated restaurants compare between the four countries?
- Are there any unique restaurant types or cuisines that are specific to one country over the others?

Austria and Denmark seem to focus more on traditional and international cuisines, while Belgium offers a mix, including seafood. England, particularly London, showcases a cosmopolitan and diverse culinary scene, with a range of international cuisines.

#### Seasonal Availability and Trends
- Are there any seasonal trends in restaurant locations (e.g., more coastal or outdoor restaurants open in summer)?
- How does the availability and type of restaurants change with seasons?

Some restaurants, like those in Tivoli Gardens, Copenhagen, and outdoor dining spots in Vienna, suggest seasonal operations, likely more active in warmer months.

### Conclusion: Insights and Implications

This project, which involved mapping and analyzing the restaurants listed in "Fielding's Travel Guide to Europe," has provided valuable insights into Europe's diverse culinary landscape. By examining how restaurants are distributed across different cities and their proximity to tourist attractions, we gained a better understanding of the relationship between cuisine and culture in various European regions. The analysis highlighted the variety of cuisines, the range of prices, and the historical significance of certain eateries. It also revealed how food culture in places like Austria, Belgium, Denmark, and England is deeply intertwined with their history and geography. This simple yet effective use of geospatial technology has not only made the rich culinary history of Europe more accessible but also underscored the importance of viewing history through the lens of everyday life, like dining culture.
