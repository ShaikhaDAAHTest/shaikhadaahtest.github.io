---
title: "Working With a Corpus"
permalink: /WWC/
author_profile: false
---

# Analyzing Three Works by L. Frank Baum: A Computer-Assisted Study of Oz Texts

## Introduction

In this assignment, I will delve into an analysis of three iconic works by L. Frank Baum, called "The Wonderful Wizard of Oz" (1900), "The Marvellous Land of Oz" (1904), and "Ozma of Oz" (1907). Through a computer-assisted analysis of the texts using an R notebook, I aim to gain insights into the frequency of specific words across the corpus and explore the potential trends in Baum's storytelling.

## Prior Knowledge

Before embarking on the analysis, it is essential to reflect on what I already knew about the subject. In this case, L. Frank Baum's Oz books are recognized as timeless classics in the realm of children's literature and film. Most notably, the first of the series was popularized through the book-to-film adaptation in 1939, and is known for its whimsical and fantastical elements, often centered around the main characters Dorothy, the Scarecrow, the Tin Woodman, the Lion, and the Witch. My understanding was largely based on this first iteration of the trilogy, as I've been an avid fan of the tale for a while now. The world building and adventure I was introduced to as a child still fills me with nostalgia and wonder. So naturally, I was eager to gain a more in-depth perspective through data-driven analysis.

## Benefits of Computer-Assisted Analysis

Computer-assisted analysis offers several advantages over traditional linear reading. The most prominent advantage is efficiency. Reading and analyzing a substantial corpus, especially within a limited timeframe, can be a daunting task for a single human reader. While research groups could definitely accomplish the task, computer-assisted tools allow individuals to process and analyze the texts at a much faster pace. This acceleration provides the opportunity to extract meaningful patterns and trends that may not be as evident through a single or even multiple linear readings of a text.

Moreover, computer-assisted analysis facilitates comparisons across multiple texts. By conducting this study, I can compare the three Oz books by Baum and identify patterns and differences in the most frequently used words. I can also create appealing visualizations that allow for unconventional data-reading methodologies and allow for visual extrapolation of important themes quickly.

## Format of the Corpus

The format in which the corpus was used, through Project Gutenberg, was very suitable for my purposes. Project Gutenberg provides a valuable resource for accessing a wide range of public domain texts published pre-copyright laws. Being able to study the text without needing to export and import it into R made for a hassle-free process, as noting the code of each text as labelled per Gutenberg’s database was enough to run the analysis.

## Comparative Analysis

The most frequently used words amongst the three Oz books offer fascinating insights into the unique characteristics and themes of each work. 

![alt text](/assets/images/oz1.png)

In "The Wonderful Wizard of Oz," the name "Dorothy" is the most prominent, appearing 347 times. This prominence underscores Dorothy's central role as the story's heroine. Furthermore, "Scarecrow" and "Tin Woodman" are also highly frequent, highlighting their importance as Dorothy's companions on her journey. Words like "Lion" and "Wicked" appear frequently, reflecting the presence of the Cowardly Lion and the Wicked Witch, key characters and antagonists. "Emerald" and "City" are notable terms, signifying the iconic Emerald City as the ultimate destination and symbol of Oz. "Brains" and "Kansas" are also significant, representing the intelligence sought by the Scarecrow and the starting point of Dorothy's adventure.

![alt text](/assets/images/oz2.png)

In "The Marvellous Land of Oz," "Tip" takes the lead with 285 mentions, reflecting the book's primary protagonist. "Scarecrow" and "Jack" follow, emphasizing the continuity of the Scarecrow's role and the introduction of Jack Pumpkinhead. Notably, the term "Pumpkinhead" stands out, underscoring the unique quality of Jack's character. "City" and "Mombi" are frequent, emphasizing the focus on urban settings and the main antagonist in the story. The term "Gump" also appears prominently, as it represents the peculiar flying creature, the Gump, featured in this narrative.

![alt text](/assets/images/oz3.png)

In "Ozma of Oz," "Dorothy" remains a central figure, with 337 mentions. "King" is a notable addition, highlighting the book's thematic exploration of royalty. "Billina" takes a significant role, reflecting the introduction of a new character, Billina the talking hen. "Ozma" is also prominent, indicating the book's emphasis on Ozma's role as the ruler of Oz. "Tiktok" stands out as well, signifying the clockwork man who plays a key role in the narrative. "Palace" and "Nome" are frequent, pointing to the royal setting and the Nome King, a central antagonist. "Yellow" suggests the unique character of the yellow hen Billina.

![alt text](/assets/images/ozcomparison.png)

When comparing the two sequels to the first text of the trilogy, one can immediately see differences in how certain words increased and decreased in frequency. In "The Marvellous Land of Oz," the term "Tip" emerges as the most frequent word, reflecting the introduction of a new protagonist and shifting the narrative focus away from Dorothy. Conversely, we also see a decrease in the usage of the words "Lion" and "Emerald." This change highlights Baum's aim to introduce new characters. In "Ozma of Oz," we observe a renewed emphasis on the character "Dorothy," and the term "Witch" decreases, reflecting a departure from the Wicked Witch theme that was central in the first book. 

## Insights from Most Frequent Words Overall

The analysis of the most frequently used words across the trilogy provides a valuable lens through which I can gain insights into children's media and literature, Baum's literary style, the trilogy's overarching themes, and how these elements reflect on the broader genre of fiction.

![alt text](/assets/images/ozgrouped.png)

Firstly, the repeated occurrence of words like "Dorothy," "Scarecrow," "Woodman," and "Oz" throughout the trilogy underscores the enduring appeal of these characters and the enchanting world of Oz. It speaks to the timeless nature of Baum's storytelling and his ability to create characters that resonate with both children and adults. Dorothy, in particular, embodies the relatable, brave, and resourceful child protagonist that remains a staple in children's literature, reinforcing the enduring power of relatable young heroes.

Baum's literary style, as revealed through these frequent words, reflects a blend of whimsy, adventure, and creativity. His use of the term "illustration" among the most frequent words serves as a reminder of the vivid imagery present in the Oz books. Baum's imaginative descriptions, combined with the iconic illustrations that accompany his works, create a visual value that contributes to the books' appeal to young readers. This visual element remains a hallmark of children's literature, emphasizing the importance of engaging young minds through the fusion of words and images.

The trilogy's most prominent themes are evident in the frequently used words as well. "King" appears prominently, pointing to the theme of leadership and royalty that permeates the stories. "Emerald" and "Palace" emphasize the enchantment of Oz and the royal setting of the Emerald City. Moreover, the recurrent use of "Cried" could be reflecting the emotional depth within the narratives, perhaps underscoring the importance of empathy and connection in children's media.

![alt text](/assets/images/ozsummary.png)

**Screenshot key:** <br>
pg33361: "Ozma of Oz" (1907) <br>
pg54: "The Marvellous Land of Oz" (1904) <br>
pg55: "The Wonderful Wizard of Oz" (1900)

From the summary of all three texts, we can deduce through the vocabulary density, average words per sentence, and readability index metrics that Baum's Oz books are well-suited for children's media and literature. The relatively low vocabulary density and straightforward language, as indicated by the readability index, make these texts accessible to young readers. 

Additionally, both "The Marvellous Land of Oz" and "The Wonderful Wizard of Oz" seem to differentiate the most out of the three, supporting the fact that there was a drastic change in storyline, characters, and overall style. Meanwhile, "Ozma of Oz" seems to lie somewhere in between the two. It seems that after the first sequel, Baum leans back on the original appeal of the first book in the series.

## Issues and Further Discussion

![alt text](/assets/images/illustrationmicrosearch.png)

**Screenshot key:** <br>
pg33361: "Ozma of Oz" (1907) <br>
pg54: "The Marvellous Land of Oz" (1904) <br>
pg55: "The Wonderful Wizard of Oz" (1900)

While linear reading remains a valuable approach, computer-assisted analysis offers an efficient and systematic method for exploring textual patterns and trends. However, one problem I noticed through my analysis is the absence of label "illustration" in the first book (as seen in the screenshot above of a microsearch of the term). This inconsistency in labelling makes it seem like the first text is completely absent of illustrations while the sequels are full of them. This lack of standardization could potentially lead to deductions that would create misimformed or false conclusions. This stresses the fact that while computer-assisted analyses of texts is useful, it is just that; assisted. Considerable amount of contextual knowledge of the baseline texts is needed for thorough exploration and the prevention of false conclusions being formed.

On another note, my analysis focused on English texts, however, the assignment's methodology prompts the question; can these forms of digital analyses be applied to other languages? From my experience with the arabic language, I can say with certainty that using these text analysis tools would be challenging. The arabic language is written in a completely different style and format, and has its own list of rules that dictate what meaning ought to be derived from a word, phrase, or sentence. Meticulasly placed characters and dialects make it extremely difficult for it to even be processed in Natural Language Processing (NLP)[^1]. I think in order to apply digital analyses tools to a language such as arabic, it would need to be designed specifically for it as opposed to adapting or tweaking existing tools. Only through this would researchers be able to gain meaningful insights into frequency, themes, and character prominence in the linguistic context.

## Conclusion and Closing Remarks

In conclusion, my computer-assisted analysis of L. Frank Baum's Oz books has provided valuable insights into the most frequently used words in these texts. It allowed me to see trends and variations in his storytelling style and character prominence.

[^1] 