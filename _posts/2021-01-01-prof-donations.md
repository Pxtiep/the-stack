---
title: Put Your Money Where Your Politics Are— Professors’ Political Donations
teaser: How do UCLA professors' political donations stack up against USC and UC Berkeley?

authors:
  - brittney_le
  - derrick_chau
  - keri_chen
  - laurel_woods
  - maria_becerra
  - vivian_luk
key_takeaways:
  - Aggregating across UCLA, USC, and UC Berkeley, over 50% of professors’ donations went to just 5 political organizations.
  - The donation amounts of UCLA professors during the months leading up to a national election nearly doubled from 2016 to 2020.
  - UCLA professors’ donations tend to spike in the months ahead of a national election.

featured_image:
  url: prof-donations/cover_photo.png
og_image: prof-donations/cover_photo.png

scripts:
  - //cdnjs.cloudflare.com/ajax/libs/Chart.js/2.8.0/Chart.js
  - //ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js
  - //d3js.org/d3.v6.min.js
  - //cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@0.7.0
  - /js/posts/prof-donations-2021/bubble-chart.js
  - /js/posts/prof-donations-2021/ucla-top-5.js
  - /js/posts/prof-donations-2021/ucb-top-5.js
  - /js/posts/prof-donations-2021/usc-top-5.js
  - /js/posts/prof-donations-2021/monthly-donations-line-chart.js

stylesheets:
  - //cdnjs.cloudflare.com/ajax/libs/c3/0.4.10/c3.min.css
  - /css/posts/prof-donations/app.css
---

“Professors, partly because of their almost universally high levels of education, are likely to be [politically] engaged,” says Martin Gilens, Chair of the Department of Public Policy and Professor of Public Policy, Political Science, and Social Welfare at UCLA.

Analyzing political engagement through the metric of political campaign donations, we tracked the donations from University of California, Los Angeles professors over the past two presidential election cycles, using publicly available data from the Federal Election Commission. We also compared the donations of professors from UCLA, University of Southern California, and University of California, Berkeley from January 2019 to December 2020, and looked at the top political campaigns that professors from each of the universities supported.

### UCLA Professors’ Donations over Time

<div class="chart-container">
  <canvas id='timeline-chart'></canvas>
</div>

The above graph shows the cumulative donation amounts from UCLA professors towards political campaigns from January 1, 2016 to December 31, 2020. This encompasses the months leading up to the 2016 general election through the months following the 2020 general election, including the 2018 midterm elections.

<div class="bubble-container">
  <canvas id='bubble-chart'></canvas>
  <p class="chart-descrip">The area of each circle is proportional to the amount of political donations by UCLA professors in that year.</p>
</div>

<div class="small-line-break"></div>

Donations tended to spike right before national elections, both general and midterm. Donation amounts also increased for every national election relative to the prior national election.

“Pretty much every election has been more expensive than what came before it,” says Gilens. However, voter turnout for midterm elections has historically been much lower than that of general elections. The 2018 midterm cycle donation spike is an interesting anomaly, with 2018’s peak donation amount to the election surpassing 2016’s peak donation amount.

Donald Trump’s victory in the 2016 presidential election may have affected the higher donation amounts for both the 2018 and 2020 general elections. “Trump was a very unconventional candidate. And he ran a very unconventional campaign,” says Gilens.

The 2016 general election results might have spurred more UCLA professors to donate to political organizations. Some UCLA professors may have also donated more money than usual to political organizations.

Interestingly, donations to House campaigns in particular jumped from $35,805.40 in the 2016 national elections to $184,492.34 during the 2018 midterm elections, an increase of more than 500%. For comparison, donations to Senate campaigns in particular only increased from $69,852.72 in 2016 to $70,877.44 in 2018.

<div class="line-break"></div>

### Breaking Down the Campaigns

<div class="ucla-chart"> <canvas id='ucla-top-5'> </canvas> </div>
<div class="ucb-chart"> <canvas id='ucb-top-5'> </canvas> </div>
<div class="usc-chart"> <canvas id='usc-top-5'> </canvas> </div>

<img class="graphic" src="/img/posts/prof-donations/stack.professordonations-01.png">

Across all three universities, just five campaigns raked in more than half of all donations made by professors to political organizations: ActBlue, Biden for President, Biden Victory Fund, Democratic Congressional Campaign Committee, and Democratic National Committee.

Additionally, President Joe Biden’s presidential campaign in 2020 was among the top three campaigns supported by professors from all three universities, as measured by donations to Biden for President and Biden Victory Fund.

It’s not surprising that there was a lot of money flowing in the Democratic direction during national elections, says Gilens. The closeness of the 2020 national election may have also contributed to the spike in donations in the months leading up to the election.

“If people had perceived it as being… a nail biter presidential election, more of the money might have flowed in that direction, rather than to congressional elections”, says Gilens.

One political organization, ActBlue, made up around a quarter of all professors’ donations. Gilens says that donating to ActBlue may have allowed professors to contribute to campaigns in other states in the interests of promoting the party’s control in the House and the Senate.

Ultimately, though donations are only one metric of political engagement, professors’ political donations across UCLA, USC, and UC Berkeley reveal a generally Democratic trend.

“Faculty in higher education… tend to [lean Democratic] in general,” says Gilens. However, Gilens notes that “there's… more liberal leaning disciplines and more conservative leaning disciplines…”, adding that “once you're… working in those fields, you tend to adopt the sort of worldviews and understandings that that field… encourages and focuses on.”
