# Topic-Modelling-Project

Project Title: Topic Modelling

Objective: Social event tracking and evolution framework to obtain the evolutionary trends of social events and 
generate effective event summary details over time.

Tools: Spyder and Streamlit.

Techniques: Web Scraping, Topic Modelling, Latent Dirichlet Allocation (LDA).

Data Collection and Model Building:
1. Web scraped text data through Google News using BeautifulSoup package and requests library.
2. Performed data cleaning and pre-processing, Exploratory Data Analysis (EDA). In EDA, performed feature 
extraction, plotted news length, wordcloud, unigram and trigram.
3. Built the LDA model using the genism library, evaluated the model using coherence and perplexity, and 
optimized the model by tuning the hyper parameters (number of topics, alpha and beta value). 
4. Visualized the output by plotting pie chart, giving a clear understanding of the dominant topic along with 
their percentage contribution to the whole corpus.
5. Deployed the model using streamlit, created a user interface where the output is visualized just by 
entering the Google news link.
