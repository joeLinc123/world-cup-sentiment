# world-cup-sentiment

A tracker of fan opinion throughout the world cup 2026. The initial run contains three nations, England, Scotland and Brazil. 
Posts are scraped off Bluesky due to the sheer cost scale of the X API, which was infeasible, although I believe that would've been a more realistic group of fan opinion, for better or for worse.
To commit sentiment analysis, the cardiffnlp/twitter-roberta-base-sentiment was used. This is trained on Tweets, so should be able to gauge social media slang better to more realistically understand fan sentiment. This is split into three strata of fan opinion, 1) Positive, 2) Neutral and 3) Negative. This is then visualised using a stacked bar chart
