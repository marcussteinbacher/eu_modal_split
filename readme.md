<header>
<center>
    <h1 style='font-family:georgia serif'>An Analysis of the European Modal Split on a National and Urban Level</h1>
    <i style='font-family:georgia serif'>A hands-on interactive study on the traffic behaviour in Europe</i>
    <br>
    <br>
    <div style='font-family:georgia serif'>by</div>
    <div style='font-family:georgia serif'>Marcus Steinbacher</div>
</center>
</header>

<body>
<h2 style='font-family:georgia serif'>Abstract</h2>
    
<p style='text-align:justify; font-family:georgia serif'>
This study investigates european national (NUTS 1-3) and urban traffic behaviour based on data from Eurostat, Unided Nations and Gapminder. I present several interactive applications to investigate the correlation between socio-economic metrics and traffic data on a temporal and local dimension. <br>
The interactive analysis provides a healthy basis for the identification and extraction of relevant features features for a regional K-Means clustering of countries and cities. Furthermore, I conduct a Time-Series K-Means clustering of cities. <br>
The hyperparameter-tuned models reveal three types of countries that share similar features as well as four kinds of cities. A cities' temporal clustering application presents the optmial clusters for each feature individually.
</p>

<h2 style='font-family:georgia serif'> 1 Introduction</h2>

<p style='text-align:justify; font-family:georgia serif'>
The European traffic modal split, particularly in urban areas, presents a dynamic and complex picture influenced by various factors such as city size, infrastructure, and cultural attitudes toward transportation. Understanding these patterns is crucial for developing sustainable mobility solutions that help improving the overall quality of life - considering a increasing urbanization, this is particularly relevant in cities. <br>
We'll see that urban areas in Europe can be broadly categorized into several types based on their traffic behavior and socio-economic properties. Major metropolitan centers like London, Paris, and Berlin, characterized by extensive public transportation networks, typically see high usage of buses, trams, and subways. In contrast, mid-sized cities such as Vienna, Copenhagen, and Zurich exhibit a balanced modal split, with significant portions of the population relying on cycling and walking due to well-developed infrastructure for non-motorized transport. Smaller cities and towns on the other hand, often lack extensive public transit options, displayind higher reliance on private vehicles. <br>
The study is structured as follows: Section 2 briefly presents the data under investigation, section 3 interactively explores the different datasets. The feature engineering and missing data imputation in section 4 prepares the data for a correlation analysis in section 5 and the (Time-Series) K-Means clustering in section 6. Finally, i conclude the major findings in section 7.
</p>

<h2 style='font-family:georgia serif'>2 Data</h2>

<p style='text-align:justify; font-family:georgia serif'>
Exploration of the different data files
15 Eurostat on national, regional and urban level (granularity)
3 UN ECE (national level)
7 Gapminder (national level)
from xxxx to xxxx

</p>

<h2 style='font-family:georgia serif'>3 Data Exploration & Vizualisation</h2>
<p style='text-align:justify; font-family:georgia serif'>
Mostly Abbildungen
NUTS level map
City Kernel map
</p>

<h2 style='font-family:georgia serif'>4 Feature Engineering & Missing Data Handling</h2>
<p style='text-align:justify; font-family:georgia serif'>
Reduction: Merging of all datasets into two frames on selected features
EU National
EU Regional
EU Urban
UN ECE
Gapminder

-> df_national & df_urban

Feature selection -> Missing Data -> feature distribution
</p>

<h2 style='font-family:georgia serif'>5 Correlation Analysis</h2>
<p style='text-align:justify; font-family:georgia serif'>
bla bla
</p>

<h2 style='font-family:georgia serif'>6 Cluster Analysis</h2>
<p style='text-align:justify; font-family:georgia serif'>
bla bla
</p>

<h2 style='font-family:georgia serif'>7 Conclusion</h2>
<p style='text-align:justify; font-family:georgia serif'>
bla bla
</p>

</body>




