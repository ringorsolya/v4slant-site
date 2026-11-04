---
title: "The Framing of LGBTQI+ Topics in Hungarian News Media"
order: 10
summary: How seven Hungarian news portals covered LGBTQI+ issues between 2021 and 2024, measured in nearly one million articles with text mining and sentiment analysis.
---
In Hungary, restrictive legislation (such as Act LXXIX of 2021) and stigmatising rhetoric continue to shape public discourse on gender and sexuality. Significant gaps remain in media analysis, particularly regarding the influence of media framing of sexual and gender minorities. Scholars agree that Hungary is experiencing democratic backsliding similarly to other countries in the Central and Eastern European (CEE) region (Bernhard, 2021), and warn that this illiberal transformation cannot be understood without gender politics (Grzebalska & Pető, 2018). The systematic undermining of gender equality in the media is often cited as one of the key signs of backsliding.

Communication through the media plays a key role in democratic regimes; fact-based, independent news sources guarantee freedom of speech and the free flow of information (Council of Europe, 2021). In the era of digital media, fake news and disinformation have become a serious social, economic and political problem in CEE. The media also play a key role in raising awareness and educating the public on LGBTQI+ issues, which, in a suitably supportive environment, can lead to a higher level of social acceptance (Randev, 2022). By shaping the representation of the LGBTQI+ community, the media influence the behaviour and attitudes of people (Happer & Philo, 2013).

## Data and method

In line with the V4 Media Slant project's general objectives, this research explored how the representation of LGBTQI+ issues in Hungarian online news portals evolved between 2021 and 2024. It analysed nearly one million articles from the seven most prominent Hungarian news portals (24.hu, 444.hu, HVG, Index, Magyar Nemzet, Origo, Telex) using text-mining techniques from computational social science. Approximately 6% of the articles addressed LGBTQI+ topics. Based on the Media Compass of the 21 Research Center (21 Kutatóközpont), the portals were classified as pro-government (Magyar Nemzet, Index, Origo) or government-critical (24.hu, 444.hu, HVG, Telex). Sentiment analysis was then used to reveal the emotional content of articles on LGBTQI+ issues.

## Anti-gender terminology

Language use, measured by the frequency of anti-gender terminology such as "paedophile", "child protection" and "ideology", varies with political orientation: government-critical outlets use these terms more often than pro-government outlets. This may suggest that critical outlets are quoting, or even challenging, the government's anti-gender narrative.

<figure>
  <img src="{{ '/assets/img/blog/lgbtqi-proportions.png' | relative_url }}" alt="Heatmap of the share of LGBTQ, anti-gender and other articles by government-critical and pro-government portals" width="556" height="356">
  <figcaption>Proportion of articles by classification and portal type.</figcaption>
</figure>

## Sentiment

The emotional content of LGBTQI+ news was measured using sentiment analysis. Sentiment analysis (also referred to as opinion mining) is a method within computational linguistics that emerged in the early 2000s. Its primary objective is to determine whether a given textual unit – a word, sentence or document – conveys positive, negative or neutral emotional content (Liu, 2010). It can be conducted with predefined sentiment dictionaries or with state-of-the-art large language models. For instance, an article may be classified as positive if most of its analytical units (e.g. words or sentences) express positive sentiment. Classification can be done at the document, sentence or aspect level.

<figure>
  <img src="{{ '/assets/img/blog/lgbtqi-sentiment.png' | relative_url }}" alt="Heatmap of average sentiment score by classification and portal type" width="486" height="360">
  <figcaption>Average sentiment score by classification and portal type.</figcaption>
</figure>

Overall, the results reveal a generally balanced sentiment in LGBTQI+-related articles. Anti-gender content is consistently more negative than value-neutral or scientific coverage on all portals. Differences, where they exist, point to individual news sites rather than political orientation. For instance, 444.hu (government-critical) and Magyar Nemzet (pro-government) both cover LGBTQI+ content more negatively than other portals on the same or the opposite side of the political spectrum. What matters more, therefore, is who discusses the topic and in what context, rather than political orientation alone.

## Conclusions

This research found that anti-gender terminology is more likely to appear on government-critical than on pro-government news portals, suggesting that framing through language depends heavily on context. The findings also point to significant variation between individual news portals that goes beyond clear political alignment, underscoring the importance of assessing each outlet on its own terms. These nuances emphasise that media analysis must remain sensitive to both linguistic choices and the political and social context.

## Limitations

Some limitations should be considered when interpreting these findings. First, keyword filtering can include irrelevant content or exclude relevant articles. Second, the lack of a timeline analysis limits insight into how specific events, such as the passage of Act LXXIX of 2021, may have influenced coverage. Third, the research did not employ topic modelling, which would have added valuable information on the themes and structure of the corpus. Research on the spread of government narratives (Horváth & Ring, 2025) shows that propaganda spreads fast in Hungarian online media. Future work could examine how long an anti-LGBTQI+ narrative remains present and which events spark increases in this activity.

## Studies cited

<div class="refs" markdown="1">
- 21 Kutatóközpont. (n.d.). Elkészült a 21 Kutatóközpont Médiairánytűje! <https://21kutatokozpont.hu/mediairanytu.html>
- Bernhard, M. (2021). Democratic Backsliding in Poland and Hungary. *Slavic Review*, 80(3), 585–607. <https://doi.org/10.1017/slr.2021.145>
- Council of Europe Commissioner for Human Rights. (2021). *Memorandum on freedom of expression and media freedom in Hungary*. <https://rm.coe.int/memorandum-on-freedom-of-expression-and-media-freedom-in-hungary/1680a1e67e>
- Grzebalska, W., & Pető, A. (2018). The gendered modus operandi of the illiberal transformation in Hungary and Poland. *Women's Studies International Forum*, 68, 164–172. <https://doi.org/10.1016/j.wsif.2017.12.001>
- Happer, C., & Philo, G. (2013). The Role of the Media in the Construction of Public Belief and Social Change. *Journal of Social and Political Psychology*, 1(1), 321–336. <https://doi.org/10.5964/jspp.v1i1.96>
- Horváth, K., & Ring, O. (2025). Az állami dezinformáció terjedésének mintázatai. *Mérték Füzetek*, 41. <https://mertek.eu/wp-content/uploads/2025/05/Mertek_Fuzetek_41.pdf>
- Liu, B. (2010). Sentiment analysis and subjectivity. In N. Indurkhya & F. J. Damerau (Eds.), *Handbook of Natural Language Processing* (2nd ed., pp. 627–666). CRC Press.
- Randev, D. J. (2022). Role of the Media in an Unequal World: LGBTQ Gender Identity and Portrayal. *Journal of Media, Culture and Communication*. <https://doi.org/10.55529/jmcc.21.1.7>
- Tamássy, R. (2024). The discursive construction of the relationship between Hungary and the European Union in light of anti-LGBTQ legislation. *Corvinus Journal of Sociology and Social Policy*, 15(3).
</div>
