# Social Cops Challenge

<h3>Aim</h3>
Your team is working on building a variety of insight packs to measure key trends in the Agriculture sector in India. You are presented with a data set around Agriculture and your aim is to understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

<h3>Objective:</h3>
<ol>
<li>Test and filter outliers.</li>

<li>Understand price fluctuations accounting the seasonal effect
<ol><li>Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities</li>
<li>De-seasonalise prices for each commodity and APMC according to the detected seasonality type</li></ol>
</li>

<li>Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised</li>

<li>Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.</li>
</ol>

Data: https://drive.google.com/drive/u/0/folders/0B-zoMsiXW40gZlNtNnlINEszRTg

<h3>Variable description:</h3>
●	msprice- Minimum Support Price<br>
●	arrivals_in_qtl- Quantity arrival in market (in quintal)<br>
●	min_price- Minimum price charged per quintal<br>
●	max_price- Maximum price charged per quintal<br>
●	modal_price- Mode (Average) price charged per quintal<br>

<h3>Description of the files in this Repository</h3>
<ol>
  <li><strong>main.ipynb - </strong>The Main Jupyter Notebook for analysis and Documentation with graphs.</li>
  <li><strong>CMO_MSP_Mandi.csv - </strong>Input Commodity MSP dataset</li>
  <li><strong>Monthly_data_cmo.csv - </strong>Input Monthly Price analysis</li>
  <li><strong>Commodity_seasonality.csv - </strong>APMC-Commodity Seasonality</li>
  <li><strong>Deseasonalised_prices.csv - </strong>Deseasonalised Prices</li>
  <li><strong>Highest_Fluctuation_Commodity_APMC.csv - </strong>Highest Fluctuation Commodities aling APMCs</li>
  <li><strong>Highest_Fluctuation_Season_Year.csv - </strong>Highest FLuctuation Commodities along a season and yearly</li>
  <li><strong>Mandi_msp_processed.csv - </strong>Preprocessed Mandi MSP dataset</li>
  <li><strong>monthly_data_cmo_no_outliers.csv - </strong>Preprocessed Monthly Price dataset</li>
</ol>
