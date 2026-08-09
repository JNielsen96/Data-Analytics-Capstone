<h1> Data Analytics Capstone Project </h1>


<h2>Description</h2>
A capstone data analytics project evaluating the real-world effectiveness of Goodnature A24 self-resetting traps in reducing invasive predator populations (rats, mice, stoats, hedgehogs) across New Zealand, as part of the country's Predator Free 2050 initiative. Built on a dataset of 1.09M+ strike records (2018–2021) provided by Goodnature, the project runs a full pipeline: data cleaning (reconciling null kill types against activity type, purging test strikes), temporal feature engineering (season classification aligned to NZ's calendar), and spatial feature engineering (Haversine-distance-based ecosystem classification into Beach/City/Forest/Mountain/Out-of-Range zones). The analysis then investigates four research questions: the relationship between temperature and strike rate (Pearson correlation and linear regression), variation in trap effectiveness across ecosystems, population distribution modelling (kernel density/PDF estimation of daily kill counts), and long-term trend significance (independent t-test comparing 2019 vs. 2020 daily catch means, showing an 18.5% statistically significant reduction). Findings are grounded in and cross-referenced against existing ecological literature, and delivered as both a full written report and a colleague-facing briefing slide deck, including an interactive map visualising strike locations across the North and South Islands.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>pandas</b>
- <b>seaborn (interaction/point plots, regression plots)</b>
- <b>matplotlib<b>
- <b>numpy<b>
- <b>scipy.stats<b>
- <b>scikit-learn or statsmodels (linear regression)<b>
- <b>Geospatial tools (Haversine distance calculation; interactive mapping — e.g. Folium/Plotly)<b>



<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Microsoft Word</b>
- <b>PowerPoint</b>
- <b>Excel</b>


<h2>Results:</h2>

<p align="center">
<br />
Monthly strike rate vs temperature:  <br/>
<img src="https://i.imgur.com/aF5ntyg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
Trap effectiveness: 
<img src="https://i.imgur.com/AX4VSQL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Linear regression: <br/>
<img src="https://i.imgur.com/UlUM9kg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Distribution model:  <br/>
<img src="https://i.imgur.com/Ikcv91y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
