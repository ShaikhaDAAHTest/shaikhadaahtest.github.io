---
title: "Cultural Heritage By the Numbers"
permalink: /CHBTN/
author_profile: false
---

## Cultural Heritage By the Numbers

### Introduction 

Usually, when completing an assignment that involves choosing items, ideas, or constructs for comparison, I would choose the ones I feel most drawn to or that feel the most familiar to me. However, going into this assignment, I wanted to take a unique approach that would 

### Part 1: Exploring the HAM website and the csv file of All Objects

In order to keep my process randomized, I decided to use the csv file instead of exploring the HAM website. I generated a bunch of random numbers from the total number of objects, leaving me with these numbers that corresponded to the following objects on the csv file: 

- 120216: [Holy Family,18th century,German](https://www.harvardartmuseums.org/collections/object/299295,https://nrs.harvard.edu/urn-3:HUAM:INV002077_dynmc)
- 203756: [The Inner Pages,20th century,American](https://www.harvardartmuseums.org/collections/object/250621)
- 192601: [Races, Jews: United States. New Jersey. Woodbine. Baron de Hirsch Agricultural and Industrial School: Woodbine Settlement and School, Woodbine, N.J. Baron de Hirsch Fund.: 32. Harvesting Peaches,19th-20th century,American](https://www.harvardartmuseums.org/collections/object/314695,https://nrs.harvard.edu/urn-3:HUAM:OCP19424_dynmc)
- 160305: [Follis of Justin II, Constantinople,6th century,Byzantine](https://www.harvardartmuseums.org/collections/object/196514,https://nrs.harvard.edu/urn-3:HUAM:COIN13167_dlvr)
- 67246: [Coin of Alexander the Great, ""Amphipolis""",4th century BCE,Greek](https://www.harvardartmuseums.org/collections/object/176706,https://nrs.harvard.edu/urn-3:HUAM:COIN06300_dlvr)
- 141363: [Untitled (back of soldier standing slightly stooped in small clearing with yellowish smoke rising in background, central highlands near Dak To, Vietnam),20th century,American](https://www.harvardartmuseums.org/collections/object/327592,https://nrs.harvard.edu/urn-3:HUAM:INV198116_dynmc)
- 67811: [Hemilitron of Syracuse,5th century BCE,Greek](https://www.harvardartmuseums.org/collections/object/177280,https://nrs.harvard.edu/urn-3:HUAM:COIN11062_dlvr)
- 193628: [Rembrandt,18th-19th century,Flemish](https://www.harvardartmuseums.org/collections/object/239525,https://nrs.harvard.edu/urn-3:HUAM:INV216598_dynmc)
- 88641: [Anonymous Aes Grave Quadrans, Rome,3rd century BCE,Roman Republican](https://www.harvardartmuseums.org/collections/object/180746,https://nrs.harvard.edu/urn-3:HUAM:COIN04981_dlvr)
- 10934: ["[""Pyramid of Sails,"" 1930, oil painting by Lyonel Feininger]",20th century,German](https://www.harvardartmuseums.org/collections/object/29383)

Only 2 out of the 10 items I sampled were accessible through the live HAM website; “The Inner Pages” and the “Pyramid of Sails”. This tedious search made me realize that my chosen methodology - randomized sampling - would not work well if I wanted to sample and access website pages that were still live from the information in the API. However, I was surprised to see that the API notebook description alone already gave me sufficient information about each piece, even though it was not active on a webpage. Each item in the list had the title, time period, culture, and category, making it easy to navigate with a simple command + F search. Even if I only had the inactive urls, I can see that each object had a specific numeric value and could be traced back to a specific collection. It was interesting to me how well documented normal url links are, and how they can provide insight into metadata.

Aside from the inactive URLs, the two active ones provided me with enough information to have a baseline understanding of how the piece was created and where, but did not have a thorough explanation of any contextual background. However, given the nature of both works, I began to understand why this might have been the case. While “The Inner Pages”  was a print, the "Pyramid of Sails" was a photograph of a painting. This gives me the impression that both are perhaps secondary sources of primary works of art, and this might have placed them at a lesser priority. However, one interesting difference I found in the metadata was the ‘Verification Level’ section. While “The Inner Pages” was reviewed by the curatorial staff, the "Pyramid of Sails" wasn't, however both are given a disclaimer of possibly not being complete.

### Part 2: Most and least viewed items for a given culture

Using the same random sampling method, and based on the number 206, this corresponded to the culture “Korean”. I used the Posit.cloud notebook “Harvard_API_TopBottomObjects” to create a list in ascending order of the most viewed objects in that culture from the Harvard Art Museum. The top three items I focused on were the “Water-moon Avalokiteshvara”, “Buddhist Triad”, and the “Portable Buddhist Shrine”. Upon delving into the metadata associated with these pieces, I was able to discern certain similarities and contrasts. Firstly, a common thread running through all three pieces is their thematic emphasis on Buddhism. All of the items visualize, in one way or another, buddhist figures. Moreover, each piece incorporates gold, whether through the medium of silk or the utilization of gilt silver and bronze. When it comes to their physical dimensions, both the “Buddhist Triad” and the “Portable Buddhist Shrine” are notably smaller in comparison to the “Water-moon Avalokiteshvara”. Additionally, these artifacts originate from close time frames, specifically the 14th or 15th century, and they are associated with either the Koryŏ or Chosŏn dynasty. On the other hand, a distinction can be drawn based on their intended purposes as told by their descriptions. While the “Water-moon Avalokiteshvara” appears to be a decorative scroll, the “Buddhist Triad” and “Portable Buddhist Shrine” both serve as mobile item for worship that represent a “stylistic cross-pollination” and cultural interplay between China, Korea, and Japan.

The items that had the least views (ascending order) were all sherds of ceramics or porcelain that were each documented as separate pieces of art with their own classifications. This was a really interesting choice to me because I never knew that fragmented, shards of a larger work are given as much value on a museum's website as a fully completed and polished work of art. In a way this made me think of just how much we as a society have come to appreciate every small bit of art, as long as it is embedded in history.

### Part 3: Using a choice of three cultures to build a word cloud

I used the same randomizer to pick three cultures from the notebook list. I ended up with Cambodian, Czech, and Netherlandish. 

![alt text](/assets/images/freqGraph.png)

Looking at the bar graph, it is clear that Netherlandish artworks completely outweigh the other two cultures by a large amount. Cambodian artworks seem to be the least popular amongst the three with Czech artworks only outnumbering it by a small percentage. This could indicate a historic interest in Netherlandish art by American universities or reflect perhaps a more considerable availability of Netherlandish works.

![alt text](/assets/images/timeSeries.png)

The time series chart provides deeper insights into why these pieces might have been acquired and when. The exclusive acquisition of Cambodian artworks between 1959 and 1960 may be linked to specific events or expeditions during that period. It might also hint at a momentary fascination with or access to Cambodian art during those years.

The gradual acquisition of Netherlandish works over time, with spikes between 1990-2010 and a significant surge in 2011, could be attributed to particular donations, purchases, or even exhibitions which made these works more accessible or desirable. The specific spike in 2011 warrants further investigation – was there a large donation or purchase that year?

When I first saw the Czech artworks' acquisition trend between 1995 and 2017, with a spike around 2009, I suspected it might reflect global or local events. However upon further investigation, one artist’ work seems to dominate the collection; František Kupka. His prints make up 32 out of the 118 total objects available when you search up the terms “Czech” on the website. This could be contributor to one of the spikes in the 2000’s 

![alt text](/assets/images/aFilter2.png)

The Cambodian word cloud reflects Cambodia's rich historical and cultural heritage. Words like "Angkor" and "Wat" point to the iconic temple complexes of the ancient Khmer empire. [^1] "Rubbing," could be alluding to the popular technique of reproducing engraved designs, implies an interest in capturing and preserving the intricate details of Cambodian art. "elephant," "demon," "humans," and "dancing" are seen immediately when Cambodian artwork is searched up on the website, as most of the collection appears to be depicting scenes from ancient Cambodian stories or religious rituals.

![alt text](/assets/images/aFilter3.png)

The frequent terms "Black," "white," "curved lines," "space," and "rectilinear" in the Czech word cloud point towards a strong emphasis on abstract, and perhaps modern or contemporary art forms. Terms like "four" and "stories" may hint at narrative techniques or the frequent use of seriality in the artworks.

![alt text](/assets/images/aFilter1.png)

The emphasis in the Netherlandish word cloud is clearly religious, with words such as "Saint," "Christ," "Angel," and "Virgin." This aligns with the historical importance of religious scenes in Netherlandish art, especially during the Renaissance period. [^2] Words like "Jacob," "Abraham," "Joseph," and "Creation" allude to biblical stories, indicating that these themes were frequently depicted in the artworks from this region.

Overall, these acquisition trends might suggest that while certain cultures like the Netherlandish have consistently been popular, others like the Cambodian and Czech have had moments of heightened interest.

[^1]: Reynolds, F. E. (2023, September 29). Angkor | History, Location, & Facts | Britannica. https://www.britannica.com/place/Angkor
[^2]: Netherlandish Renaissance Art. (n.d.). Retrieved October 2, 2023, from http://www.visual-arts-cork.com/history-of-art/netherlandish-renaissance.htm