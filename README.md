# america-dropped-the-ball
A data analysis of the 2026 FIFA World Cup host performance across ticket pricing, stadium attendance, tourism, and fan access, benchmarked against every tournament since 2006. The numbers make the case. The politics explain them.

# America Dropped the Ball: A Data Analysis of the 2026 World Cup Host Failure

## Overview

The 2026 FIFA World Cup received 500 million ticket requests. The previous two tournaments combined attracted 50 million. By any measure of global demand, this should have been the greatest sporting event in American history.

It was not.

This project analyses how the United States has performed as a World Cup host across five measurable dimensions: ticket pricing, stadium attendance, tourism, fan access, and a composite host performance index, benchmarked against every World Cup since 2006. The findings are consistent and damning. By every metric, the US is underperforming relative to prior hosts, including countries with a fraction of its resources, infrastructure, and preparation time.

The underperformance is not a mystery. It has causes, and this analysis names them.

---

## The Five Pillars of Analysis

**Ticket Prices**
The cheapest seat at the 2026 World Cup Final costs USD 2,030. In Qatar four years ago, it was USD 206. FIFA's dynamic pricing model has moved the tournament into a pricing bracket previously occupied only by the Super Bowl and the Champions League Final, events that have never pretended to be for everyone.

**Stadium Attendance**
Every World Cup host between 1994 and 2022 achieved a stadium fill rate between 94% and 99.8%. The 2026 tournament opened with unsold seats at its first matches and 176,000 resale tickets still available on FIFA's own platform as the group stage began. This is not a demand problem. 500 million people requested tickets. Something else is keeping fans away.

**Tourism**
The US is the only World Cup host in modern history projected to see a decline in international visitors in its tournament year. Brazil grew tourism by 10.7% in 2014. Qatar grew it by 342% in 2022. The US is on course for minus 9.2%, a fall of 6.3 million visitors compared to the year before, in a year when the entire planet had a reason to visit.

**Fan Access**
20% of all countries on earth face US travel restrictions. Four qualified nations, Haiti, Iran, Ivory Coast, and Senegal, are under full or partial travel bans. Sixteen nations in our sample have fans facing some form of legal barrier to attending matches. ICE agents are confirmed inside every host city stadium. The Iranian squad is based in Mexico, commuting across the border for games.

**Composite Host Score**
Germany, South Africa, Brazil, Russia, and Qatar all scored between 8.0 and 9.1 out of 10 on a five-dimension host performance index. The range across twenty years of hosting is 1.1 points. The United States scores **2.8**.

---

## The Political Context

There is a structural reality worth acknowledging first, and it predates the current administration entirely: football is not America's sport. In a country where the sporting calendar revolves around the NFL, NBA, March Madness, and baseball, soccer has always occupied an awkward middle ground, loved by immigrant communities and suburban youth leagues, but never quite crossing into the mainstream consciousness the way it has on every other continent. The empty seats are partly a reflection of a country hosting the world's game without being fully converted to it.

That structural reality might have been managed, as it largely was in 1994, when organisational excellence and the passion of immigrant fan communities filled stadiums to 99.8% capacity. The difference in 2026 is the political climate that made those very communities feel like a target rather than an asset.

Donald Trump's second administration has not merely complicated the logistics of hosting a World Cup. It has fundamentally altered what America signals to the world, and the world has responded accordingly. The travel bans. The visa freezes. ICE at stadiums. Phones searched at borders. A Somali referee denied entry. An Iranian squad commuting from Mexico. Moroccan supporters turned away at embassies despite holding tickets and hotel bookings.

The 9.2% tourism decline did not happen because of visa paperwork. It happened because people made a choice about where they wanted to spend their money and their time, and they chose somewhere else.

The United States is a country built by immigrants, on the labour, culture, and sacrifice of people who came from somewhere else. The diversity that made America the most aspirational destination on earth was not a side effect of its greatness. It *was* its greatness. Trump and his MAGA movement have spent two terms making people of colour, Muslims, Latin Americans, Africans, and anyone who does not fit a narrow conception of who belongs feel unwelcome, regardless of their legal status, regardless of their history in this country, regardless of what they built.

No one is illegal on stolen land. And in the summer of 2026, when the world came to celebrate the most universal sport on earth, the communities that make America what it is were made to feel the celebration was not for them.

The data shows it. All of it.

---

## Data Sources

All datasets were manually compiled from primary sources and are available in the repository.

| File | Contents | Sources |
|---|---|---|
| `ticket_prices.csv` | Official FIFA ticket prices by category, 2014-2026 | FIFA, Gulf News, Sports Illustrated |
| `attendance.csv` | Total and average attendance per match, 1994-2026 | FIFA, Statista, FootyStats |
| `tourism.csv` | Inbound visitor data for host nations in World Cup years | ITA/NTTO, UN Tourism, Congress.gov |
| `access_barriers.csv` | Fan access restrictions by qualifying nation | CFR, American Immigration Council, Wego Travel, Reuters |
| `host_scores.csv` | Composite host performance scores across five dimensions | Researcher-assigned based on published data |

---

## Methodology Note

The composite host performance scores are researcher-assigned rather than algorithmically modelled. Each of the five dimensions, tourism uplift, stadium fill rate, ticket accessibility, fan access, and hotel readiness, was scored on a 0 to 10 scale based on published data from the sources listed above. Prior hosts were scored using historical records and academic literature. The US 2026 score reflects data available as of June 2026, with tourism projections based on forecasts from Tourism Economics and the ITA rather than final confirmed numbers. Scores are intended to be directionally accurate and comparative rather than precisely quantitative. The underlying data is available in full for anyone who wants to interrogate or challenge the findings.

---

## Tools Used

Python, pandas, matplotlib, numpy

---

## Key Finding

In 1994, the United States set the all-time World Cup attendance record: 68,991 fans per match, 99.8% capacity, across 52 games. That record has stood for 32 years.

America knows how to host a World Cup. It did it better than anyone, ever.

What the data from 2026 shows is not incompetence. It is a choice, made in executive orders, in visa rejection letters, in the deployment of federal agents inside football stadiums, to treat the arrival of the world as a threat rather than an opportunity.

The composite score is 2.8 out of 10. The lowest in the history of the modern tournament. In the country that, 32 years ago, showed everyone how it was done.

---

*Data sources: FIFA, ITA/NTTO, CFR, American Immigration Council, Statista, FootyStats, Financial Times, Tourism Economics, UN Tourism, The Conversation, Sports Illustrated, Gulf News, Reuters, NPR*
