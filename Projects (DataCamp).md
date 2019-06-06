# Projects (DataCamp)

## Table of Contents
- [A New Era of Data Analysis in Baseball](#18)
- [A Network analysis of Game of Thrones](#5)
- [A Visual History of Nobel Prize Winners](#13)
- [ASL Recognition with Deep Learning](#29)
- [Bad passwords and the NIST guidelines](#24)
- [Book Recommendations From Charles Darwin](#1)
- [Classify Song Genres from Audio Data](#16)
- [Comparing Cosmetics by Ingredients](#11)
- [Do Left-handed People Really Die Young](#23)
- [Dr. Semmelweis and the Discovery of Handwashing](#8)
- [Exploring 67 years of LEGO](#7)
- [Exploring the Bitcoin Cryptocurrency Market](#9)
- [Exploring the evolution of Linux](#15)
- [Find Movie Similarity from Plot Summaries](#31)
- [Generating Keywords for Google Ads](#19)
- [Give Life- Predict Blood Donations](#6)
- [Mobile Games A/B Testing with Cookie Cats](#21)
- [Naive Bees: Deep Learning with Images](#34)
- [Naive Bees: Image Loading and Processing](#33)
- [Naive Bees: Predict Species from Images](#32)
- [Name Game Gender Prediction using Sound](#22)
- [Predicting Credit Card Approvals](#12)
- [Predict Stock Trends from News Headlines](#4)
- [Recreating John Snow's Ghost Map](#27)
- [Reducing Traffic Mortality in the USA](#28)
- [Risk and Returns: The Sharpe Ratio](#10)
- [The Android App Market on Google Play](#3)
- [The GitHub History of the Scala Language](#25)
- [The Hottest Topics in Machine Learning](#30)
- [TV, Halftime Shows, and the Big Game](#20)
- [Up And Down With The Kardashians](#2)
- [Which Debts Are Worth the Bank's Effort](#26)
- [Who Is Drunk and When in Ames, Iowa?](#17)
- [Word Frequency in Moby Dick](#14)

## Tools

- NumPy, SciPy, pandas

- matplotlib, seaborn

- scikit-learn

- NLTK, gensim

- NetworkX

## Contents

<a id='18'></a>
- [A New Era of Data Analysis in Baseball](https://github.com/iDataist/A-New-Era-of-Data-Analysis-in-Baseball):
  Aaron Judge is one of the physically largest players in Major League Baseball standing 6 feet 7 inches (2.01 m) tall and weighing 282 pounds (128 kg). He also hit the hardest home run ever recorded. How do we know this? Statcast.
  Statcast is a state-of-the-art tracking system that uses high-resolution cameras and radar equipment to measure the precise location and movement of baseballs and baseball players. Introduced in 2015 to all 30 major league ballparks, Statcast data is revolutionizing the game. Teams are engaging in an "arms race" of data analysis, hiring analysts left and right in an attempt to gain an edge over their competition. This video describing the system is incredible.
  This project wrangled, analyzed, and visualized Statcast data to compare Mr. Judge and another (extremely large) teammate of his.

<a id='5'></a>
- [A Network analysis of Game of Thrones](https://github.com/iDataist/A-Network-analysis-of-Game-of-Thrones):
  If you haven't heard of Game of Thrones, then you must be really good at hiding. Game of Thrones is the hugely popular television series by HBO based on the (also) hugely popular book series A Song of Ice and Fire by George R.R. Martin. In this notebook, we will analyze the co-occurrence network of the characters in the Game of Thrones books. Here, two characters are considered to co-occur if their names appear in the vicinity of 15 words from one another in the books. The raw data constitutes a network and is given as a text file describing the edges between characters, with some attributes attached to each edge. The project conducted a network analysis of Game of Thrones.

<a id='13'></a>  
- [A Visual History of Nobel Prize Winners](https://github.com/iDataist/A-Visual-History-of-Nobel-Prize-Winners):
  The Nobel Prize is perhaps the world's most well known scientific award. Except for the honor, prestige and substantial prize money the recipient also gets a gold medal showing Alfred Nobel (1833 - 1896) who established the prize. Every year it's given to scientists and scholars in the categories chemistry, literature, physics, physiology or medicine, economics, and peace. The first Nobel Prize was handed out in 1901, and at that time the Prize was very Eurocentric and male-focused, but nowadays it's not biased in any way whatsoever. Surely. Right? This project investigated that.

<a id='29'></a>  
- [ASL Recognition with Deep Learning](https://github.com/iDataist/ASL-Recognition-with-Deep-Learning):
  American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures. A lot of recent progress has been made towards developing computer vision systems that translate sign language to spoken language. This technology often relies on complex neural network architectures that can detect subtle patterns in streaming video. However, as a first step, towards understanding how to build a translation system, we can reduce the size of the problem by translating individual letters, instead of sentences. This project trained a convolutional neural network to classify images of American Sign Language (ASL) letters.

<a id='24'></a>
  - [Bad passwords and the NIST guidelines](https://github.com/iDataist/Bad-passwords-and-the-NIST-guidelines):
  This project went through the rules in <a href="https://pages.nist.gov/800-63-3/sp800-63b.html">NIST Special Publication 800-63B</a> which details what checks a <em>verifier</em> (what the NIST calls a second party responsible for storing and verifying passwords) should perform to make sure users don't pick bad passwords. The raw data are the passwords of users from a fictional company.

<a id='1'></a>
- [Book Recommendations From Charles Darwin](https://github.com/iDataist/Book-Recommendations-From-Charles-Darwin):
  Charles Darwin is one of the few universal figures of science. His most renowned work is without a doubt his "On the Origin of Species" published in 1859 which introduced the concept of natural selection. But Darwin wrote many other books on a wide range of topics, including geology, plants or his personal life. This project investigated how closely related his books are to each other.

<a id='16'></a>
- [Classify Song Genres from Audio Data](https://github.com/iDataist/Classify-Song-Genres-from-Audio-Data):
  Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.

  For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. This project examined data compiled by a research group known as The Echo Nest, and classified songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one.

<a id='11'></a>
- [Comparing Cosmetics by Ingredients](https://github.com/iDataist/Comparing-Cosmetics-by-Ingredients):
  Whenever I want to try a new cosmetic item, it's so difficult to choose. It's actually more than difficult. It's sometimes scary because new items that I've never tried end up giving me skin trouble. We know the information we need is on the back of each product, but it's really hard to interpret those ingredient lists unless you're a chemist. You may be able to relate to this situation.

  So instead of buying and hoping for the best, why don't we use data science to help us predict which products may be good fits for us? In this notebook, we are going to create a content-based recommendation system where the 'content' will be the chemical components of cosmetics. Specifically, we will process ingredient lists for 1472 cosmetics on Sephora via word embedding, then visualize ingredient similarity using a machine learning method called t-SNE and an interactive visualization library called Bokeh.

<a id='23'></a>
- [Do Left-handed People Really Die Young](https://github.com/iDataist/Do-Left-handed-People-Really-Die-Young)

  <p>Barack Obama is left-handed. So are Bill Gates and Oprah Winfrey; so were Babe Ruth and Marie Curie. A <a href="https://www.nejm.org/doi/full/10.1056/NEJM199104043241418">1991 study</a> reported that left-handed people die on average nine years earlier than right-handed people. Nine years! Could this really be true? </p>

  This project explored this phenomenon using age distribution data to see if we can reproduce a difference in average age at death purely from the changing rates of left-handedness over time, refuting the claim of early death for left-handers. It used <code>pandas</code> and Bayesian statistics to analyze the probability of being a certain age at death given that you are reported as left-handed or right-handed.

<a id='8'></a>
- [Dr. Semmelweis and the Discovery of Handwashing](https://github.com/iDataist/Dr.-Semmelweis-and-the-Discovery-of-Handwashing):
  Dr. Ignaz Semmelweis was a Hungarian physician born in 1818 and active at the Vienna General Hospital. In the early 1840s at the Vienna General Hospital as many as 10% of the women giving birth die from childbed fever, a deadly disease affecting women that just have given birth. Dr. Semmelweis found cause of childbed fever: the contaminated hands of the doctors delivering the babies. This project analyzed the data that made Semmelweis discover the importance of handwashing.

<a id='7'></a>
- [Exploring 67 years of LEGO](https://github.com/iDataist/Exploring-67-years-of-LEGO):
  Everyone loves Lego (unless you ever stepped on one). Did you know by the way that "Lego" was derived from the Danish phrase leg godt, which means "play well"? Unless you speak Danish, probably not. This project analyzed a fascinating dataset on every single lego block that has ever been built!

<a id='9'></a>
- [Exploring the Bitcoin Cryptocurrency Market](https://github.com/iDataist/Exploring-the-Bitcoin-Cryptocurrency-Market):
  Since the launch of Bitcoin in 2008, hundreds of similar projects based on the blockchain technology have emerged. We call these cryptocurrencies (also coins or cryptos in the Internet slang). Some are extremely valuable nowadays, and others may have the potential to become extremely valuable in the future1. In fact, on the 6th of December of 2017, Bitcoin has a market capitalization above $200 billion. This project looked into the cryptocurrency market.

<a id='15'></a>
- [Exploring the evolution of Linux](https://github.com/iDataist/Exploring-the-evolution-of-Linux):

  Version control repositories like CVS, Subversion or Git can be a real gold mine for software developers. They contain every change to the source code including the date (the "when"), the responsible developer (the "who"), as well as little message that describes the intention (the "what") of a change. This project analyzed the evolution of a very famous open-source project – the Linux kernel. The Linux kernel is the heart of some Linux distributions like Debian, Ubuntu or CentOS. We get some first insights into the work of the development efforts by identifying the TOP 10 contributors and visualizing the commits over the years.Linus Torvalds, the (spoiler alert!) main contributor to the Linux kernel (and also the creator of Git), created a mirror of the Linux repository on GitHub. It contains the complete history of kernel development for the last 13 years, and is used as the raw data.

<a id='31'></a>
- [Find Movie Similarity from Plot Summaries](https://github.com/iDataist/Find-Movie-Similarity-from-Plot-Summaries):
  We all love watching movies! There are some movies we like, some we don't. Most people have a preference for movies of a similar genre. Some of us love watching action movies, while some of us like watching horror. Some of us like watching movies that have ninjas in them, while some of us like watching superheroes.
  Movies within a genre often share common base parameters. Consider the following two movies:
  2001: A Space Odyssey Close Encounters of the Third Kind
  Both movies, 2001: A Space Odyssey and Close Encounters of the Third Kind, are movies based on aliens coming to Earth. I've seen both, and they indeed share many similarities. We could conclude that both of these fall into the same genre of movies based on intuition, but that's no fun in a data science context. This project quantified the similarity of movies based on their plot summaries available on IMDb and Wikipedia, then separated them into groups, also known as clusters.

<a id='19'></a>
- [Generating Keywords for Google Ads](https://github.com/iDataist/Generating-Keywords-for-Google-Ads):

  This project created a prototype set of keywords for search campaigns for sofas. The client is generally a low-cost retailer, offering many promotions and discounts. We will need to focus on such keywords. We will also need to move away from luxury keywords and topics, as we are targeting price-sensitive customers. Because we are going to be tight on budget, it would be good to focus on a tightly targeted set of keywords and make sure they are all set to exact and phrase match.

<a id='6'></a>
- [Give Life- Predict Blood Donations](https://github.com/iDataist/Give-Life--Predict-Blood-Donations):
  Blood transfusion saves lives - from replacing lost blood during major surgery or a serious injury to treating various illnesses and blood disorders. Ensuring that there's enough blood in supply whenever needed is a serious challenge for the health professionals. According to WebMD, "about 5 million Americans need a blood transfusion every year". The raw data is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive.

<a id='21'></a>
- [Mobile Games A/B Testing with Cookie Cats](https://github.com/iDataist/Mobile-Games-A-B-Testing-with-Cookie-Cats):

  Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. It also features singing cats. We're not kidding! Check out this short demo:

  As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

  But where should the gates be placed? Initially the first gate was placed at level 30, but this project analyzed an AB-test where the first gate in Cookie Cats was moved from level 30 to level 40, and looked at the impact on player retention.

<a id='34'></a>
- [Naive Bees: Deep Learning with Images](https://github.com/iDataist/Naive-Bees-Deep-Learning-with-Images):
  Can a machine identify a bee as a honey bee or a bumble bee? These bees have different behaviors and appearances, but given the variety of backgrounds, positions, and image resolutions, it can be a challenge for machines to tell them apart.
  Being able to identify bee species from images is a task that ultimately would allow researchers to more quickly and effectively collect field data. Pollinating bees have critical roles in both ecology and agriculture, and diseases like colony collapse disorder threaten these species. Identifying different species of bees in the wild means that we can better understand the prevalence and growth of these important insects.
  This project walked through building a simple deep learning model that can automatically detect honey bees and bumble bees and then loads a pre-trained model for evaluation.

<a id='33'></a>
- [Naive Bees: Image Loading and Processing](https://github.com/iDataist/Naive-Bees-Image-Loading-and-Processing):
  The question at hand is: can a machine identify a bee as a honey bee or a bumble bee? These bees have different behaviors and appearances, but given the variety of backgrounds, positions, and image resolutions it can be a challenge for machines to tell them apart.

  Being able to identify bee species from images is a task that ultimately would allow researchers to more quickly and effectively collect field data. Pollinating bees have critical roles in both ecology and agriculture, and diseases like colony collapse disorder threaten these species. Identifying different species of bees in the wild means that we can better understand the prevalence and growth of these important insects.

  This project walked through loading and processing images. After loading and processing these images, they will be ready for building models that can automatically detect honeybees and bumblebees.

<a id='32'></a>
- [Naïve Bees: Predict Species from Images](https://github.com/iDataist/Naive-Bees-Predict-Species-from-Images):
  Can a machine identify a bee as a honey bee or a bumble bee? These bees have different behaviors and appearances, but given the variety of backgrounds, positions, and image resolutions, it can be a challenge for machines to tell them apart.
  Being able to identify bee species from images is a task that ultimately would allow researchers to more quickly and effectively collect field data. Pollinating bees have critical roles in both ecology and agriculture, and diseases like colony collapse disorder threaten these species. Identifying different species of bees in the wild means that we can better understand the prevalence and growth of these important insects. This project built a model that can automatically detect honey bees and bumble bees.

<a id='22'></a>
- [Name Game Gender Prediction using Sound](https://github.com/iDataist/Name-Game-Gender-Prediction-using-Sound):

  Grey and Gray. Colour and Color. Words like these have been the cause of many heated arguments between Brits and Americans. Accents (and jokes) aside, there are many words that are pronounced the same way but have different spellings. While it is easy for us to realize their equivalence, basic programming commands will fail to equate such two strings.
  More extreme than word spellings are names because people have more flexibility in choosing to spell a name in a certain way. To some extent, tradition sometimes governs the way a name is spelled, which limits the number of variations of any given English name. But if we consider global names and their associated English spellings, you can only imagine how many ways they can be spelled out.
  One way to tackle this challenge is to write a program that checks if two strings sound the same, instead of checking for equivalence in spellings. This project did that here using fuzzy name matching.

<a id='12'></a>  
- [Predicting Credit Card Approvals](https://github.com/iDataist/Predicting-Credit-Card-Approvals)

  Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. This project built an automatic credit card approval predictor using machine learning techniques.

<a id='4'></a>
- [Predict Stock Trends from News Headlines](https://github.com/iDataist/Predict-Stock-Trends-from-News-Headlines):
  It used to take days for financial news to spread via radio, newspapers, and word of mouth. Now, in the age of the internet, it takes seconds. Did you know news articles are automatically being generated from figures and earnings call streams? Hedge funds and independent traders are using data science to process this wealth of information in the quest for profit. This project generated investing insight by applying sentiment analysis on financial news headlines from FINVIZ.com.

<a id='27'></a>
- [Recreating John Snow's Ghost Map](https://github.com/iDataist/Recreating-John-Snow-s-Ghost-Map):

  Dr. John Snow (1813-1858) was a famous British physician and is widely recognized as a legendary figure in the history of public health and a leading pioneer in the development of anesthesia. Some even say one of the greatest physicians of all time.
  As a leading advocate of both anesthesia and hygienic practices in medicine, he not only experimented with ether and chloroform but also designed a mask and method how to administer it. He personally administered chloroform to Queen Victoria during the births of her eighth and ninth children, in 1853 and 1857, which assured a growing public acceptance of the use of anesthetics during childbirth.
  But, as we will show later, not all his life was just a success. John Snow is now also recognized as one of the founders of modern epidemiology (some also consider him as the founder of data visualization, spatial analysis, data science in general, and many other related fields) for his scientific and pretty modern data approach in identifying the source of a cholera outbreak in Soho, London in 1854, but it wasn't always like this. In fact, for a long time, he was simply ignored by the scientific community and currently is very often mythified. This project reanalyzed the data that he collected in 1854 and recreate his famous map (also called The Ghost Map).

<a id='28'></a>
- [Reducing Traffic Mortality in the USA](https://github.com/iDataist/Reducing-Traffic-Mortality-in-the-USA):
  While the rate of fatal road accidents has been decreasing steadily since the 80s, the past ten years have seen a stagnation in this reduction. Coupled with the increase in number of miles driven in the nation, the total number of traffic related-fatalities has now reached a ten year high and is rapidly increasing.
  Per request of the US Department of Transportation, we are currently investigating how to derive a strategy to reduce the incidence of road accidents across the nation. By looking at the demographics of traﬃc accident victims for each US state, we find that there is a lot of variation between states. Now we want to understand if there are patterns in this variation in order to derive suggestions for a policy action plan. In particular, instead of implementing a costly nation-wide plan we want to focus on groups of states with similar profiles. How can we find such groups in a statistically sound way and communicate the result effectively? This project answered this question.

<a id='10'></a>
- [Risk and Returns-The Sharpe Ratio](https://github.com/iDataist/Risk-and-Returns--The-Sharpe-Ratio):
  An investment may make sense if we expect it to return more money than it costs. But returns are only part of the story because they are risky - there may be a range of possible outcomes. How does one compare different investments that may deliver similar results on average, but exhibit different levels of risks?

  Enter William Sharpe. He introduced the reward-to-variability ratioin 1966 that soon came to be called the Sharpe Ratio. It compares the expected returns for two investment opportunities and calculates the additional return per unit of risk an investor could obtain by choosing one over the other. In particular, it looks at the difference in returns for two investments and compares the average difference to the standard deviation (as a measure of risk) of this difference. A higher Sharpe ratio means that the reward will be higher for a given amount of risk. It is common to compare a specific opportunity against a benchmark that represents an entire category of investments.

  The Sharpe ratio has been one of the most popular risk/return measures in finance, not least because it's so simple to use. It also helped that Professor Sharpe won a Nobel Memorial Prize in Economics in 1990 for his work on the capital asset pricing model (CAPM).

  This project calculates the Sharpe ratio for the stocks of the two tech giants Facebook and Amazon. The S&amp;P 500 that measures the performance of the 500 largest stocks in the US serves the benchmark.

<a id='3'></a>
- [The Android App Market on Google Play](https://github.com/iDataist/The-Android-App-Market-on-Google-Play):
  Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. This project looked for insights in the raw data to devise strategies to drive growth and retention.

<a id='25'></a>
- [The GitHub History of the Scala Language](https://github.com/iDataist/The-GitHub-History-of-the-Scala-Language):

  With almost 30k commits and a history spanning over ten years, Scala is a mature programming language. It is a general-purpose programming language that has recently become another prominent language for data scientists.
  Scala is also an open source project. Open source projects have the advantage that their entire development histories -- who made changes, what was changed, code reviews, etc. -- publicly available.
  This project read in, cleaned up, and visualized the real world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub).
  The dataset we will use, which has been previously mined and extracted directly from GitHub, is comprised of two files:
  pulls.csv contains the basic information about the pull requests.
  pull_files.csv contains the files that were modified by each pull request.

<a id='30'></a>
- [The Hottest Topics in Machine Learning](https://github.com/iDataist/The-Hottest-Topics-in-Machine-Learning):
  The NIPS conference (Neural Information Processing Systems) is one of the most prestigious yearly events in the machine learning community. At each NIPS conference, a large number of research papers are published. Over 50,000 PDF files were automatically downloaded and processed to obtain a dataset on various machine learning techniques. These NIPS papers are stored in datasets/papers.csv. The CSV file contains information on the different NIPS papers that were published from 1987 until 2017 (30 years!). These papers discuss a wide variety of topics in machine learning, from neural networks to optimization methods and many more. This project analyzed these papers with natural language processing methods.

<a id='20'></a>
- [TV, Halftime Shows, and the Big Game](https://github.com/iDataist/TV-Halftime-Shows-and-the-Big-Game):

  Whether or not you like football, the Super Bowl is a spectacle. There's a little something for everyone at your Super Bowl party. Drama in the form of blowouts, comebacks, and controversy for the sports fan. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes riding giant mechanical tigers or leaping from the roof of the stadium. It's a show, baby. And in this notebook, we're going to find out how some of the elements of this show interact with each other. This project answered questions like:

  What are the most extreme game outcomes?
  How does the game affect television viewership?
  How have viewership, TV ratings, and ad cost evolved over time?
  Who are the most prolific musicians in terms of halftime show performances?

<a id='2'></a>
- [Up And Down With The Kardashians](https://github.com/iDataist/Up-And-Down-With-The-Kardashians):
  While I'm not a fan nor a hater of the Kardashians and Jenners, the polarizing family intrigues me. Why? Their marketing prowess. Say what you will about them and what they stand for, they are great at the hype game. Everything they touch turns to content. The sisters in particular over the past decade have been especially productive in this regard. Let's get some facts straight. I consider the "sisters" to be the following daughters of Kris Jenner.

  Three from her first marriage to lawyer Robert Kardashian:

  - Kourtney Kardashian (daughter of Robert Kardashian, born in 1979)

  - Kim Kardashian (daughter of Robert Kardashian, born in 1980)

  - Khloé Kardashian (daughter of Robert Kardashian, born in 1984)

  And two from her second marriage to Olympic gold medal-winning decathlete, Caitlyn Jenner (formerly Bruce):

  - Kendall Jenner (daughter of Caitlyn Jenner, born in 1995)

  - Kylie Jenner (daughter of Caitlyn Jenner, born in 1997)

<a id='26'></a>
- [Which Debts Are Worth the Bank's Effort](https://github.com/iDataist/Which-Debts-Are-Worth-the-Banks-Effort):

  After a debt has been legally declared "uncollectable" by a bank, the account is considered to be "charged-off." But that doesn't mean the bank simply walks away from the debt. They still want to collect some of the money they are owed. The bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to receive from the customer in the future (for a fixed time period such as one year). This amount is a function of the probability of the customer paying, the total debt, and other factors that impact the ability and willingness to pay.
  The bank has implemented different recovery strategies at different thresholds ($1000, $2000, etc.) where the greater the expected recovery amount, the more effort the bank puts into contacting the customer. For low recovery amounts (Level 0), the bank just adds the customer's contact information to their automatic dialer and emailing system. For higher recovery strategies, the bank incurs more costs as they leverage human resources in more efforts to contact the customer and obtain payments. Each additional level of recovery strategy requires an additional $50 per customer so that customers in the Recovery Strategy Level 1 cost the company $50 more than those in Level 0. Customers in Level 2 cost $50 more than those in Level 1, etc.
  The big question: does the extra amount that is recovered at the higher strategy level exceed the extra $50 in costs? This project investigated whether there was a jump (also called a "discontinuity") of more than $50 in the amount recovered at the higher strategy level.

<a id='17'></a>
- [Who Is Drunk and When in Ames, Iowa?](https://github.com/iDataist/Who-Is-Drunk-and-When-in-Ames-Iowa):
  Ames, Iowa, USA is the home of Iowa State University, a land grant university with over 36,000 students. By comparison, the city of Ames, Iowa, itself only has about 65,000 residents. As with any other college town, Ames has had its fair share of alcohol-related incidents. (For example, Google 'VEISHEA riots 2014'.) This project took a look at some breath alcohol test data from Ames that is published by the State of Iowa.

<a id='14'></a>
- [Word Frequency in Moby Dick](https://github.com/iDataist/Word-Frequency-in-Moby-Dick):
  What are the most frequent words in Herman Melville's novel, Moby Dick, and how often do they occur?
  This project scraped the novel Moby Dick from the website Project Gutenberg (which contains a large corpus of books) using the Python package requests, extracted words from this web data using BeautifulSoup, and analyzed the distribution of words using the Natural Language ToolKit (nltk). The Data Science pipeline can be used to visualize the word frequency distributions of any novel found on Project Gutenberg.
