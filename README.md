# Understanding the global trends in investments 
Understanding the global trends in investments so that we can make investment decisions effectively. 

#  Where did we get the data from? 
I have taken real investment data from crunchbase.com, so the insights we get
may be incredibly useful.

# business objective? 
The business objectives and goals of data analysis are :
1) Business objective: The objective is to identify the best sectors, countries,
and a suitable investment type for making investments. The overall strategy is
to invest where others are investing, implying that the 'best' sectors and
countries are the ones 'where most investors are investing'.
2) Goals of data analysis: Goals are divided into three sub-goals:
- Investment type analysis: Comparing the typical investment amounts
in the venture, seed, angel, private equity etc. so that we can
choose the type that is best suited for their strategy.
- Country analysis: Identifying the countries which have been the most
heavily invested in the past. These will be we favourites as well.
- Sector analysis: Understanding the distribution of investments across
the eight main sectors. (Note that we are interested in the eight 'main
sectors' provided in the mapping file. The two files — companies and 
rounds2 — have numerous sub-sector names; hence, we will need to
map each sub-sector to its main sector.)

# Funding Type Analysis
This is the first of the three goals of data analysis – investment type analysis. 
The funding types such as seed, venture, angel, etc. depend on the type of the
company (startup, corporate, etc.), its stage (early stage startup, funded startup,
etc.), the amount of funding (a few million USD to a billion USD), and so on. For
example, seed, angel and venture are three common stages of startup funding. 
- Seed/angel funding refer to early stage startups whereas venture funding
occurs after seed or angel stage/s and involves a relatively higher amount of
investment
- Private equity type investments are associated with much larger companies
and involve much higher investments than venture type. Startups which have
grown in scale may also receive private equity funding. This means that if a
company has reached the venture stage, it would have already passed
through the angel or seed stage/s

# Country Analysis 
This is the second goal of analysis — country analysis(Only english speaking countries). 
Now that we know the type of investment suited for us
We wants to invest in countries with the highest amount of funding for the chosen
investment type. This is a part of its broader strategy to invest where **most
investments are occurring.**

#  Sector Analysis
This is the third goal of analysis — sector analysis. 
When we say sector analysis, we refer to one of the eight main sectors listed in the
mapping file (note that ‘Other’ is one of the eight main sectors; also, there are eight
sectors if we consider the category 'Blanks' as a missing value). This is to simplify
the analysis by grouping the numerous category lists (named ‘category_list’) in the
mapping file. For example, in the mapping file, category_lists such as ‘3D’, ‘3D
Printing’, ‘3D Technology’, etc. are mapped to the main sector ‘Manufacturing’. 
Also, for some companies, the category list is a list of multiple sub-sectors separated
by a pipe (vertical bar |). For example, one of the companies’ category_list is
Application Platforms|Real Time|Social Network Media. 

# Plot
![Image of country by inv plot](https://github.com/Paritoshyadav/understanding-the-global-trends-in-investments-/blob/master/Images_plot/country%20by%20investment.PNG?raw=true)
![Image of raised amount by inv plot](https://github.com/Paritoshyadav/understanding-the-global-trends-in-investments-/blob/master/Images_plot/raised%20amount%20by%20number%20of%20investment.PNG)
- A plot showing the fraction of total investments (globally) in venture, seed, and
private equity, and the average amount of investment in each funding type.
- A plot showing the top 9 countries against the total amount of investments of
funding type FT. This should make the top 3 countries (Country 1, Country 2,
and Country 3) very clear
- A plot showing the number of investments in the top 3 sectors of the top 3
countries on one chart 
