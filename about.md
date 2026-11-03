---
layout: page
title: About the project
permalink: /about/
lead: How online news in the Visegrad countries frames crises, and how artificial intelligence can make that slant measurable.
---

News content has a powerful impact on society and politics. A vast amount of information is available on the internet, which can reduce its transparency and increase the opportunity for news slant. People rely on many kinds of media as news sources, often simply assuming that they are reliable.

Slant is the more or less favourable news coverage of an individual or group. It can be explicit, if people are aware of it, but it is often implicit or unconscious. News slant can affect which events and stories are published and the perspective from which they are written. We hypothesise that slant manifests not only in what news describes, but in where it places emphasis, how it frames events, and what it keeps silent about.

The project studied crisis communication – the COVID-19 pandemic, the Russia–Ukraine war and domestic political crises – in the online news of Czechia, Hungary, Poland and Slovakia, analysing 2.9 million articles (2,899,733) from 35 outlets published between January 2018 and March 2024.

## Research pipeline

The project's outputs form one open, reproducible pipeline: **corpus → code → models → dashboard**.

1. **Portal selection.** Partners in each country selected online news portals balanced by ideological orientation and ownership.
2. **Corpus building.** Articles were collected and organised into databases with a common metadata structure (outlet, date, country, orientation).
3. **Topic modelling.** LDA topic models were fitted for each portal separately and then merged into 20 unified topics comparable across the four countries.
4. **Actor analysis.** Named-entity recognition identified mentions of influential politicians and organisations.
5. **Emotion analysis.** Texts were segmented into sentences and classified with emotion models fine-tuned for each V4 language, trained on expert-annotated data and validated by domain experts.
6. **Visualisation.** The results are published in an interactive [dashboard]({{ '/dashboard/' | relative_url }}).

## Unified topic categories

| Code | Topic | Covers |
|---|---|---|
| POL | Politics | Political events, parties, elections, politicians' statements, domestic and international debates |
| LEG | Legislation and legal affairs | Law-making, legislative proposals, court cases, constitutional issues |
| ECO | Economy and industrial sectors | Economic trends, industries, investment, inflation, employment |
| FIN | Finance | Financial markets, banks, fiscal policy, budgets, debt, exchange rates |
| MIL | Military, war and national security | Armed conflicts, defence policy, intelligence, security |
| PRO | Protests | Demonstrations, strikes, civic resistance, grassroots movements |
| CRI | Crime | Criminal acts, police investigations, arrests, criminal trials |
| INT | International affairs | Diplomacy, geopolitics, relations between countries |
| TECH | Technology | Digital technologies, AI, software, cybersecurity, platforms |
| CUL | Culture | Arts, literature, film, music, theatre, exhibitions |
| SPO | Sport | Athletes, matches, tournaments, sports organisations |
| EDU | Education | Education policy, schools, universities, teachers, students |
| FAM | Family | Family life, parenting, childcare, demography, family policy |
| TRA | Transport | Public transport, infrastructure, traffic, mobility policy |
| REG | Regional issues and housing | Local governance, urban planning, housing, real estate |
| HEA | Health and the COVID-19 pandemic | Health care, hospitals, public health, vaccines |
| MED | Media | Journalism, press freedom, media regulation, misinformation |
| ACC | Accidents | Accidents, natural disasters, emergencies, rescue operations |
| REL | Religion | Religious communities, churches, religious leaders |
| MISC | Miscellaneous | Articles that fit no other category |

## Open resources

- **Corpus:** [Visegradmedia – Central European News Corpus (OSF)](https://osf.io/45et2/). Version 1.0, 2025. Access for academic, non-commercial research on request; the copyright of the original articles remains with the publishers.
- **Code:** [github.com/ringorsolya/visegradmedia](https://github.com/ringorsolya/visegradmedia)
- **Emotion models:** [huggingface.co/visegradmedia-emotion](https://huggingface.co/visegradmedia-emotion). If you use the models, please cite Üveges & Ring (2025), [*Information*, 16(4), 330](https://doi.org/10.3390/info16040330).

## Team and partners

- **Principal investigator:** Orsolya Ring (ELTE Centre for Social Sciences)
- **Researchers:** István Üveges, Viktor Kovács, Anna Rebak, László Kiss, Ákos Holányi
- **Czech partner:** Jakub Stauber (Charles University, Prague)
- **Slovak partner:** Jaroslav Kopčan (Kempelen Institute of Intelligent Technologies, Bratislava)
- **Polish partner:** Krzysztof Rybiński (Vistula University, Warsaw)
- **Partner institutions:** Charles University, Faculty of Mathematics and Physics; Charles University, Faculty of Social Sciences; Kempelen Institute of Intelligent Technologies; Vistula University
- **Contact:** [ring.orsolya@tk.hu](mailto:ring.orsolya@tk.hu)
