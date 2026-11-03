---
title: "Decoding Media Bias in the Russian-Ukrainian War: Lessons from Czech News"
order: 6
summary: A pilot study uses a fine-tuned DeBERTa model to track how far Czech outlets echo Western or Russian strategic narratives about the war.
---
The Russian-Ukrainian war is not just a battle fought with weapons; it is also a war of stories. Around the world, media outlets have shaped how people understand the conflict. Western media often portrays it as Russia's unprovoked aggression, while Russian media frames it as a justified response to NATO's expansion. But how do narratives play out in Czech media, a country with a very diverse media landscape?

Our pilot study used advanced natural language processing (NLP) techniques to uncover how Czech news outlets cover the Russian-Ukrainian war. By analysing media bias and tracking the narratives in play, this research reveals how news platforms can add to the formation of public perception of the war.

## What are strategic narratives?

Strategic narratives are stories crafted by states and organisations to explain their actions and policies. These narratives frame conflicts, shape public opinion and justify political decisions. In the context of the Russian-Ukrainian war, two key narratives dominate:

1. **Western narrative:** the war is described as an illegal invasion by Russia, violating Ukraine's sovereignty and endangering Europe.
2. **Russian narrative:** the conflict is cast as a defensive measure against NATO's expansion and Western interference.

Understanding media bias means examining how these narratives are presented: whether they are simply reported, selectively highlighted, or actively endorsed by news outlets.

## How the study was conducted

1. **Collecting news articles.** The study analysed articles from a range of Czech news outlets, including *iRozhlas* (public broadcaster), *Novinky* (mainstream, centre-left), *iDnes* (mainstream, centre-right) and *Parlamentní listy* (disinformation outlet).
2. **Classifying narratives.** A DeBERTa-v3 model was trained on over 6,400 labelled text samples to detect whether articles aligned with Western or Russian narratives. Tools like ChatGPT were used to validate the findings, achieving high accuracy in identifying narrative bias.
3. **Measuring bias.** The study examined how closely sentences in each article aligned with either the Western or the Russian narrative. By aggregating this data, researchers tracked bias patterns over time.

## Key takeaways

**Different news, different biases.** Czech media showed clear differences in how they reported the war. Public broadcasters and mainstream outlets leaned toward the Western narrative, while disinformation platforms like *Parlamentní listy* often echoed Russian propaganda.

<!-- FIGURE 1 MISSING: difference between Western and Russian narrative over time (higher means more Russian narrative reported) -->

**AI as a research tool.** Generative AI tools proved invaluable for analysing media bias. By fine-tuning models and labelling data, the study achieved high accuracy in detecting biases. This approach highlights how technology can enhance our understanding of complex social issues.

**Reporting vs. endorsing narratives.** The study emphasised the importance of distinguishing between merely reporting a narrative and actively endorsing it. This subtle difference is key to understanding the intent behind media coverage.

**Bias changes over time.** Media bias evolved throughout the conflict, influenced by major events like battlefield developments or international negotiations. This dynamic nature underscores the importance of ongoing analysis.

<!-- FIGURE 2 MISSING: the prevalence of a "bias" effect after the initial spike -->

## Why it matters

Being aware of media bias helps people critically evaluate the news they consume. The study underscores the importance of consulting diverse sources to get a balanced perspective on global events. Insights from this research can help governments combat disinformation and promote accurate reporting. The study's methods could also be applied to other media landscapes to track and address bias. This work demonstrates how combining AI tools with social science theories can tackle complex questions, and it prepares the way for new studies in political communication and the role of media in shaping public opinion.

## Conclusion

The Russian-Ukrainian war is a stark reminder of how powerful narratives can influence public opinion. By using innovative AI techniques, this research offers a detailed look at media bias in Czech news coverage. It highlights the critical role of journalism in democracies and the need to stay vigilant against disinformation.
