Team meeting 9/27 notes:

paul:
what do we want out of next season?
this season: a few small victories but a lot of frustration. often beaten badly by Battley
What do we want to do next year? How do we do it? 

Paul: should we even try? we are old and distracted with kids and masters


didn't have much of a plan because first year coming out of covid. didnt execute at key moments of race

noel wants to race as long as he can. but he wants to spend time with his daughter

suggestion: 1 team ride a month for the winter
recruiting strategy?


1 sunday or 2 a month
committing early to early season races
calendar with 8 races, show up to maybe 5?
pick out some goal races 

action item: organize regular rides where we get together as a group

sdf


9.5k 401k
52k cd
73k 401k
61k cash
30k annie accounts



Doing ~4h endurance w/ 1x25m Tempo in each hour. Stay on top of your hydration and nutrition through this ride!

-30m z1-z2 warm up

3x
-20m z2
-25m z3
-15m z2

-30m z1-z2 warm down


data %>% group_by(w,x,y,z) %>%
summarise(
agg_1 = sum(var_1),
agg_1 = ifelse(agg_1 <= var_2, agg_1, var_2),

agg_2 = sum(var_3),
agg_2 = ifelse(agg_2 <= var_2, agg_2, var_2),

) %>%
ungroup() %>%
group_by(x,y,z) %>%
unique() %>%
summarise(
agg_1_sum = sum(agg_1),
agg_2_sum = sum(agg_2)
count_1 = n(),
avg_1 = agg_1_sum/count_1
)



calc_f <- function(data, alpha){

data %>%
mutate(
f_1 = x + alpha*y,
f_2 = m + alpha*n,
f_3 = f_1/f_2
)


}

df_sf <- df %>%
st_as_sf(crs = st_crs(data))

def iterate(grid):
 dt = []
 for j in range(len(grid)):
  for i in grid:
	dt[j] = f(g(data, grid[i]))

 dt= pd.concat(dt)
 return dt

tmp %>%
pivot_longer(
-id_loan_syst_gend,
names_to = "alpha",
values_to = "exceeds_1"
) %>%
group_by(alpha) %>%
summarise(
tot = sum(exceeds_1)
)


violations.spplus.com


8W<TC:\]^q'<j`%L









---
title: title: "The Distributional Impacts of Climate Changes across US Local Labor Markets"
authors:
- "Emmett Reynier & John Morehouse"
date:  "2024-10-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate:  "2024-10-05"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: []

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""


abstract: "Climate change has affected households around the globe, but its impacts are not homogenous across space. We first show that disadvantaged demographic groups are disproportionately exposed to climate change in the US and are less responsive in their adaptive behavior. Motivated by these findings, we develop and estimate a spatial equilibrium model of US local labor markets, allowing households to adapt to climate change by choosing where to live and, conditional on that choice, energy and housing consumption. Our results show that climate change to date has caused welfare losses 20% larger for Black households relative to white households and twice as large for the lowest income decile relative to the highest income decile. We estimate that these gaps will continue to grow under projections of the future climate. Both the population’s ex-ante distribution and differential mobility contribute to the observed disparities. We then evaluate a $3 billion place-based policy from the Inflation Reduction Act, quantifying the tradeoff between subsizing places with high climate damages and the resulting in-migration to climate-exposed areas.""

# Summary. An optional shortened abstract.
summary: We show that disadvantaged demographic groups are disproportionately exposed to climate change in the US and are less responsive in their adaptive behavior. We develop and estimate a spatial equilibrium model of US local labor markets and show that climate change to date has caused welfare losses 20% larger for Black households relative to white households and twice as large for the lowest income decile relative to the highest income decile

tags:
- Urban Economics
- Residential Sorting

featured: true

links:
url_pdf: 'files/papers/reynier-morehouse-climate-migration.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

