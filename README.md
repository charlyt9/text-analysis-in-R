# Analysis of Covid-19 Press Releases in Kenya using Swahili language

After the World Health Organization became profoundly concerned by the spread, severity, and inaction levels in early 2020, Covid-19 was declared a pandemic. The media was instrumental in keeping the public updated about the pandemic. In Kenya, English and Swahili are the national languages. My analysis is based on press releases in Kenya published by the media in Swahili. Taifa Leo owned by the Nation Media Group is the leading newspaper which publishes in Swahili.
The press releases were obtained by scrapping the [website](https://taifaleo.nation.co.ke/) of the media outlet using the keywords “covid” or “corona” as it was popularly referred to in Swahili. The press releases retrieved were between January 2020 to December 2021 and were a total of 3586 articles. Web scrapping was done using python and file saved as csv. The file had 3 columns: 

* Title (Headline of the published article)
* Date the article was published
* Content (The complete article) 

The processing and analysis of the data was done using R. 


## Packages

Use the package manager [install.packages](https://www.rdocumentation.org/packages/utils/versions/3.6.2/topics/install.packages) to install required packages.

```r
install.packages("tidytext")
install.packages("dplyr")
install.packages("tidyr")
install.packages("readr")
install.packages("ggplot2") 
install.packages("ggraph")
install.packages("igraph")
install.packages("RColorBrewer")
```
The R markdown can be accessed [here](https://charlyt9.github.io/text-analysis-in-R/)

## References

Silge, J and D. Robinson, 2017: [Text Mining with R: A Tidy Approach](https://www.tidytextmining.com/)

Niekler, A. and G. Wiedemann 2020: [Text mining in R for the social sciences and digital humanities](https://tm4ss.github.io/docs/index.html)

Masua, B., & Masasi, N. (2020). [Enhancing text pre-processing for Swahili language: Datasets for common Swahili stop-words, slangs and typos with equivalent proper words](https://www.researchgate.net/publication/347762452_Enhancing_text_pre-processing_for_Swahili_language_Datasets_for_common_Swahili_stop-words_slangs_and_typos_with_equivalent_proper_words)

Robertson, S. (2004). [Understanding inverse document frequency: on theoretical arguments for IDF](https://doi.org/10.1108/00220410410560582)
