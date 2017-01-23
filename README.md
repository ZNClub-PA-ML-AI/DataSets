# DataSets

This repo stores the different training and testing data sets 

# Target - NSE CNX Nifty 50

Here is a breakdown of the 50 companies which constitute the CNX Nifty. Over the last decade, while sectoral weight-age has remained largely similar, the constituent companies have constantly changed.

NSE has announced the following changes in the composition of Nifty 50 index. The replacement of stocks in the index, change in weightage of existing companies will be effective from April 1, 2016.

The inclusion of Tata Motors Ltd (DVR) in the Nifty 50 will take the number of securities in the index to 51.

## Notable Facts:
* Financial Services and Information Technology contribute 40.81% to the overall weight-age.
* There are 5 Pharmaceutical companies. India is amongst the biggest pharmaceutical exporters in the world.
* Of all things,  cigarettes still have a dominant weight-age in the pie.
* No modern day e-commerce businesses find place in the CNX Nifty. Compare this with the U.S. where Facebook, Amazon, e-Bay and Yahoo are all part of the NASDAQ 100.
* The breakup hardly showcases India as a developing economy. Construction, Infrastructure, Industrial manufacturing and cement put together contribute 6.09%. Energy and power is at 15.17%
* 6 out of the 10 financial services companies are private sector banks. Consider the fact that in India, there are 24 listed public sector banks and only 16 listed private sector banks. This is significantly different from how things were a decade back.

![Nifty 50 sector-wise breakdown](http://www.blog.sanasecurities.com/wp-content/uploads/2015/08/nifty-50-companies-weightage.png "Nifty 50 sector-wise breakdown")

Here is the list of companies provided by [sanasecurities](http://www.blog.sanasecurities.com/nifty-50-companies-list-sector-wise-weightage/)

# Target Companies & Sectors
We have decided to go with the Top 3 weighted sectors: FinService(9), IT(5), Energy(7)
This gives us a list of 21 companies(with weightage) which are:

* FinServices: 
  Axis Bank	3.09
  Bank of Baroda	0.48
  HDFC	6.89
  HDFC Bank	8.02
  ICICI Bank	4.65
  IndusInd Bank	1.82
  Kotak Mahindra Bank	2.89
  State Bank of India	2.43
  Yes Bank	1.39

* IT:
  HCL Technologies	1.36
  Infosys	6.41
  TCS	4.14
  Tech Mahindra	0.90
  Wipro	0.98
  
* Energy: 
  BPCL	0.97
  GAIL (India)	0.56
  NTPC	1.22
  ONGC	1.31
  Power Grid	1.25
  Reliance Industries	5.43
  Tata Power	0.44

 * Telecomm
  Bharti Airtel	1.41
  Idea Cellular	0.32
  Bharti Infratel	0.66
  
 * Pharma
  Cipla	0.95
  Dr. Reddy’s Lab	1.32
  Lupin	1.19
  Sun Pharmaceutical	2.54
  Aurobindo Pharma	0.66
  
  * Automobile
  Bajaj Auto	1.21
  Bosch	0.62
  Hero MotoCorp	1.34
  Mahindra & Mahindra	1.82
  Maruti Suzuki	2.31
  Eicher Motors	0.95
  Tata Motors	2.93
  Tata Motors Ltd. (DVR)	0.50

### Market News Strategy

#### Companies and Lows of more than 4% during last 12 months

##### FinServices: 
  Axis Bank	3.09
  Bank of Baroda	0.48
  HDFC	6.89
  HDFC Bank	8.02
  ICICI Bank	4.65
  IndusInd Bank	1.82
  Kotak Mahindra Bank	2.89
  State Bank of India	2.43
  Yes Bank	1.39

##### IT:
* HCL Technologies 8-9/11;24-30/10;26-30/8;16-23/8;22-29/6;6/6-30,2/5-27/4;3-9/3;22-25/2;5-10/2;19-20,6-11/1;==2-7/12;
* Infosys	8-9,1-4/11;25-29,17-22,11-16/8;15-18/7;21-28,8-10/6;5-11/4;8-10/2;==17-19/11;
* TCS	7-9,1-3/11;7-9/9;19-23,16-18/8;15-19/7;22-24/6;20-25/4;22-25,8-10/2;11-14,1-6/1;=11-17/11;
* Tech Mahindra	8-9/11;3/10-28,7-12/9;12-19/8;26-29/7;21-27/6;2-4/5;5-8/4;22-29,1-3/2;1==5-16/12;
* Wipro	7-9/11;21-27/10;25-30/8;15-20/7;23-28,2-3/6;20-26/4;2-9/2;5-12/1;
  
##### Energy: 
  BPCL	0.97
  GAIL (India)	0.56
  NTPC	1.22
  ONGC	1.31
  Power Grid	1.25
  Reliance Industries	5.43
  Tata Power	0.44

#### Market News Websites and XPaths

##### Moneycontrol

- http://www.moneycontrol.com/news/news-All.html
+ /html/body[@id='newsn']/section[@id='mc_content']/section[@class='pgWrapper clearfix PT10']/section[@class='colLft_in']/div[@class='wbg']/div[@class='artiCol PR']/div[@class='clearfix']/div[2]/ul[@class='nws_listing']/li[2]/div[@class='clearfix']/div[@class='ohidden']/h2

+ /html/body[@id='newsn']/section[@id='mc_content']/section[@class='pgWrapper clearfix PT10']/section[@class='colLft_in']/div[@class='wbg']/div[@class='artiCol PR']/div[@class='clearfix']/div[2]/ul[@class='nws_listing']/li[2]/div[@class='clearfix']/div[@class='ohidden']/p[@class='MT2']

+ /html/body[@id='newsn']/section[@id='mc_content']/section[@class='pgWrapper clearfix PT10']/section[@class='colLft_in']/div[@class='wbg']/div[@class='artiCol PR']/div[@class='clearfix']/div[2]/ul[@class='nws_listing']/li[2]/div[@class='clearfix']/div[@class='ohidden']/p[@class='nws_datetx MT5']

- http://www.moneycontrol.com/news/all-news-All-2-next-0.html
- till li[2] ,li[4] .. li[32] http://www.moneycontrol.com/news/all-news-All-3382-next-0.html 10th Nov 2015 news

  BODY
+ /html/body[@id='newsn']/section[@id='mc_content']/section[@class='pgWrapper clearfix PT10']/section[@class='colLft_in']/div[@class='wbg']/div[@class='artiCol PR']/div[@class='arti_cont']/div[@class='MT20']




##### Livemint

- http://www.livemint.com/Query/DIoW9PdSAJUlZsu7iBevDI/companies-opinion.html?facet=subSection&page=0

- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@class='listing-box-container']/div[@class='listing-box'][1]/div[@class='text-box']/h2[@class='split-heading-strong']/a/text()
- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@class='listing-box-container']/div[@class='listing-box'][1]/div[@class='text-box']/p[@class='intro']/a/text()
- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@class='listing-box-container']/div[@class='listing-box'][1]/div[@class='text-box']/p[@class='date-box']/text()
- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@class='listing-box-container']/div[@class='listing-box'][1]/div[@class='text-box']/h2[@class='split-heading-strong']/a/@href

- till [10] page=24 OCT 27

- http://www.livemint.com/Query/V1eAlpSAzt0kHm6oBnOvDI/management.html?facet=subSection&page=0 to 24 
- http://www.livemint.com/Query/ZtZgviOVr74zwZ37eD9uDI/results.html?facet=subSection&page=0 to 24
- http://www.livemint.com/Query/lZy3FU0kP9Cso5deYypuDI/people.html?facet=subSection&page=0 to 24
- http://www.livemint.com/Query/P8RBwcvO9gvJl6xh6wTNzO/infotech.html?facet=subSection&page=0 to 24
- http://www.livemint.com/Query/5jCbPmmTjmX6bvfyV5XlkJ/financial-services.html?facet=subSection&page=0 to 24
- http://www.livemint.com/Query/hHUQJ3ncBXZBGH3eVyKlkJ/energy.html?facet=subSection&page=0 to 24
- http://www.livemint.com/Query/t5YPD42JdoNxoDBxwNemkJ/industry-opinion.html?facet=subSection&page=0 to 24

  BODY
- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@id='div_storyContent']/div[@class='story-content']

##### Economic Times

- http://economictimes.indiatimes.com/markets/stocks/news

+ /html/body/section[@id='netspidersosh']/section[@id='pageContent']/div[@class='eachStory'][1]/h3
+ /html/body/section[@id='netspidersosh']/section[@id='pageContent']/div[@class='eachStory'][1]/p
+ /html/body/section[@id='netspidersosh']/section[@id='pageContent']/div[@class='eachStory'][1]/time[@class='date-format']

- till [32] http://economictimes.indiatimes.com/markets/stocks/news/articlelist/msid-2146843,page-100.cms SEP 28

  BODY
- /html/body/div[@id='o-wrapper']/div[@class='wrapper']/section[@class='left-col']/div[@id='div_storyContent']/div[@class='story-content']
