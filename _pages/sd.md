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

#### Overall map:
![alt text](/assets/images/overall.png)
#### Denmark map:
![alt text](/assets/images/denmark.png)
#### England map:
![alt text](/assets/images/england.png)
#### Austria map:
![alt text](/assets/images/austria.png)
#### Belgium map:
![alt text](/assets/images/belgium.png)

In order to analyze the data, I asked chatgpt to give me a list of questions I should aim to answer or ponder when looking at the details and geospatial data and to help me thoroughly analyze the data. I used the questions to create the following subsections for analysis:

#### Distribution Analysis

The dataset includes a diverse range of restaurants spread across the cities of Vienna, Brussels, Copenhagen, Salzburg, and London. Vienna, Austria, shows a notable concentration of restaurants, suggesting a vibrant culinary scene. In London, England, there is a significant density of restaurants, particularly in central areas like Coventry Street, Jermyn Street, and Piccadilly, indicating a cluster of high-quality dining options in the city's heart.

#### Proximity to Tourist Attractions

Many restaurants, especially in Vienna and London, are located near major tourist attractions. This includes areas like the historic center of Vienna and central London near Leicester Square and Piccadilly Circus. There seems to be a correlation between the proximity to tourist areas and the density of high-rated restaurants, particularly in city centers known for tourism. Perhaps this is more a reflection on the authors own experience and stay rather than the actual density of restaurants, but this is a given as the source is from one point of view.

#### Cuisine Variety

In Austria, traditional Austrian and international cuisines dominate, with specific mentions of Swedish-rustic and Balkan styles. Belgium's offerings are diverse, with a focus on seafood and international cuisine. Denmark's restaurants also show a preference for international cuisine, seafood, and traditional Danish dishes. London's culinary scene is cosmopolitan, with a wide range of cuisines including French, Italian, Hungarian, and traditional English fare.

#### Price Range Analysis

The price ranges vary, with some restaurants like Kahlenberg in Austria and the Petit Louvain in Belgium offering meals at modest prices, while others, particularly in London, are described as elegant with high prices, suggesting a more upscale dining experience.

#### Accessibility Analysis

Given their central locations in major cities, most restaurants are likely highly accessible via public transportation. Top-rated restaurants are more concentrated in areas with higher accessibility, especially in urban centers.

#### Historical vs. Modern Establishments

The dataset includes both historical establishments like “The Three Hussars” in Vienna and modern ones like “Richmond Hotel & Au Coq d’Or Restaurant” in Copenhagen. In London, historical restaurants like “George and Vulture” and “Rule’s” indicate a preference for tradition in certain parts of the city.

#### Comparative Regional Analysis

Austria and Denmark seem to focus more on traditional and international cuisines, while Belgium offers a mix, including seafood. England, particularly London, showcases a cosmopolitan and diverse culinary scene, with a range of international cuisines.

#### Seasonal Availability and Trends

Some restaurants, like those in Tivoli Gardens, Copenhagen, and outdoor dining spots in Vienna, suggest seasonal operations, likely more active in warmer months.

#### Modern day parallels

Aside from responding to chatGPTs questions for analysis, I was really interested to see wether or not any of the restaurants are still open today. To get a fair estimate, I randomly sampled 4 restaurants from each region, which left me with the following list of restaurants:

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR0-BzhgIFG1ju5jQB6OrN12vzF9y8udfnCmhDWY8iQgRJq1YqDJ2loycryYRz1tuMGEBwBJJ_wO6rC/pubhtml" width="800" height="1200"></iframe>

Based on current information, the status of each restaurant is as follows:

Austria:
- St. Stephan: I couldn't find specific current information.
- Zum Weissen Rauchfangkehrer: This restaurant is still operating. It is open Monday to Sunday. Reservations can be made via email​​. [^1]
- Peterskeller: The current status of this restaurant isn't clear.
- Franz Powondra: There isn't specific information available online regarding the current status of this restaurant.

Belgium:
- Savoy: appears to be closed​​ and has been replaced. [^2]
- Canterbury: I was unable to find current information about its operational status.
- Bolero: did not find specific information. The Boulevard Adolphe Max (where it's supposidly located) has undergone redevelopment, which could affect the businesses there​​. [^3]
- Chez Marius en Provence: I was unable to find current information about its operational status.

Denmark:
- Au Coq d'Or at H. C. Andersen's Boulevard 13: There was no specific information available about its current operational status.
- Wivex: The restaurant closed down in 1964. The building was demolished and replaced with new structures. The name "Wivex" continued for a while in a restaurant in the new building, which was inaugurated in 1971​​. [^4]
- Langelinie Pavilion: The Langelinie Pavilion is currently operational and offers services for weddings, dinners, family celebrations, meetings, and events for both small and large companies. [^5]
- Copenhagen Zoo Dining: Within Copenhagen Zoo, there are several dining options available. [^6]

England:
- Caprice (Le Caprice), Arlington Street, London: This legendary restaurant, formerly known as Le Caprice, located on Arlington Street, closed its doors during the pandemic. However, it is set to be revived and relaunched under the new name "The Arlington" by Jeremy King, one of the individuals originally responsible for its success. The reopening is planned for early 2024​​​​​​. [^7] [^8] [^9]
- Maison Basque, 11 Dover Street, London: The current status of Maison Basque is not clear from available online sources. However, the address 11 Dover Street is now occupied by Pescatori Restaurant, which serves seafood and is currently operational​​. [^10]
- Carafe, 15 Lowndes Street, London: The location at 15 Lowndes Street is now home to Zafferano, an Italian restaurant that opened in 1995 and has since gained acclaim and several awards. It is currently operational and offers a selection of Italian dishes​​​​. [^11]
- Pigalle, 190 Piccadilly, London: The Pigalle Club at 190 Piccadilly closed in 2012. There is no current information about a restaurant operating under this name at the same location. The site has since undergone changes and is no longer known as the Pigalle Club​​. [^12]

The analysis of the current status of historical restaurants is a fascinating reflection of the changes in the culinary landscape over time. The method of randomly sampling provides a snapshot of the ongoing evolution in the restaurant industry. It's interesting to see that while some establishments are still operational, others have closed down or transformed. This blend of continuity and change showcases the dynamic nature of culinary history and the impact of broader social and economic changes on local businesses.

On a more informal note: I absolutely LOVED falling down this rabbithole of finding out wether restaurants have closed down or not. It felt like watching an episode of Kitchen Nightmares, and then scurrying over to google to search up the name of the restaurant featured to see what has happened since. It's so interesting to see why certain restaurants have stayed afloat while others havent.

### Conclusion: Insights and Implications

This project, which involved mapping and analyzing the restaurants listed in "Fielding's Travel Guide to Europe," has provided valuable insights into Europe's diverse culinary landscape. By examining how restaurants are distributed across different cities and their proximity to tourist attractions, we gained a better understanding of the relationship between cuisine and culture in various European regions. The analysis highlighted the variety of cuisines, the range of prices, and the historical significance of certain eateries. It also revealed how food culture in places like Austria, Belgium, Denmark, and England is deeply intertwined with their history and geography. This simple yet effective use of geospatial technology has not only made the rich culinary history of Europe more accessible but also underscored the importance of viewing history through the lens of everyday life, like dining culture. However, it's important to recognize that this geospatial map represent more of a personal travel journey of the guide's author than a comprehensive historical database of top restaurants. It's akin to exploring someone's saved list of places on Google Maps, providing a subjective rather than an exhaustive view of the culinary scene. Additionally, the role of ChatGPT in organizing and interpreting the data was crucial. It helped in making sense of the information and preparing it for processing, thereby highlighting the synergy between AI and historical analysis. 

### Citations:

[^1]: “HOME.” Accessed November 25, 2023. https://www.weisser-rauchfangkehrer.at/en/.
[^2]: Yelp. “Spasiba - Brussels, BRU.” Accessed November 25, 2023. https://www.yelp.com/biz/spasiba-bruxelles.
[^3]: “Boulevard Adolphe Max Redevelopment,” August 24, 2021. https://www.brussels.be/boulevard-adolphe-max.
[^4]: “Wivex.” In Wikipedia, the Free Encyclopedia, March 12, 2021. https://da.wikipedia.org/w/index.php?title=Wivex&oldid=10650570.
[^5]: The Langelinie Pavillion. “Food.” Accessed November 25, 2023. https://langelinie.dk/en/food/.
[^6]: VisitCopenhagen. “Copenhagen Zoo | Key Visitor Attraction in Copenhagen.” Accessed November 25, 2023. https://www.visitcopenhagen.com/copenhagen/planning/copenhagen-zoo-gdk1077921.
[^7]: Lloyd, Hattie. “Arlington.” The Nudge London (blog), October 16, 2023. https://thenudge.com/london-restaurants/arlington/.
[^8]: restaurantonline.co.uk. “Jeremy King to Relaunch Le Caprice Site as Arlington.” restaurantonline.co.uk, October 16, 2023. https://www.restaurantonline.co.uk/Article/2023/10/16/jeremy-king-to-relaunch-le-caprice-site-as-arlington.
[^9]: “What’s in a Name? Le Caprice Becomes The Arlington | Harden’s,” October 20, 2023. https://www.hardens.com/uk-london/20-10-2023/whats-in-a-name-le-caprice-becomes-the-arlington/.
[^10]: Yelp. “Pescatori Restaurant - London, XGL.” Accessed November 25, 2023. https://www.yelp.com/biz/pescatori-restaurant-london.
[^11]: “Reservations | Zafferano Restaurant.” Accessed November 25, 2023. https://zafferanorestaurant.com/reservations/.
[^12]: Evening Standard. “The Former Pigalle Club Reopens in Piccadilly under New Name Of,” April 23, 2014. https://www.standard.co.uk/news/london/the-former-pigalle-club-reopens-in-piccadilly-under-new-name-of-werewolf-9277310.html.