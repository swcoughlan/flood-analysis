# flood-analysis

<img src="https://i.imgur.com/Tko46mp.png" width="1000" style="display:block; margin:auto" />

Jupyter Notebook for SAR flood analysis in Pakistan with Google Earth Engine Python API

In mid-June 2022, Pakistan began experiencing unusually heavy rainfall. Within weeks, the relentless downpours had led to widespread flooding across significant parts of the country. Pakistan's climate is characterized by a distinct monsoon season, with the majority of its annual rainfall, approximately 70-75%, occurring between June and September. However, the intensity of these monsoon rains varies annually, with some years witnessing far higher rainfall than usual.

In 2022, the monsoon season was exceptionally severe. Described by U.N. Secretary-General António Guterres as a "monsoon on steroids,” Pakistan received about ten times more rain than its average. Some regions were particularly hard-hit, receiving 600-800% percent of their typical August rainfall. At the peak of this crisis, Sindh, the country's most populous province, saw an overwhelming 15 inches of rain in just one day. As the summer progressed, these waters accumulated in the low-lying areas surrounding the Indus River, transforming vast stretches of farmland into virtual lakes and isolating numerous villages.

The catastrophic floods resulted in a tragic loss of life and widespread devastation. A total of 1,739 individuals lost their lives, including 647 children, and there were 12,867 reported injuries. The disaster left over 2.1 million people without homes, marking it as the most severe flood in Pakistan since 2010, which had a death toll of nearly 2,000. These floods were also the most catastrophic globally since the South Asian floods in 2020. 

Synthetic Aperture Radar (SAR) offers several significant advantages for flood mapping, making it a highly effective tool in disaster management and environmental monitoring. Unlike optical sensors, SAR can penetrate through clouds and is not affected by weather conditions. This feature is particularly crucial for flood mapping, as heavy cloud cover often accompanies flooding events. Additionally, SAR systems can operate effectively both day and night, ensuring continuous monitoring of flood situations. Lastly, SAR is particularly sensitive to smooth surfaces like water, which appear dark on SAR images. This contrast makes it easier to differentiate between flooded and non-flooded areas, enhancing the accuracy of flood extent mapping.

This tutorial is based upon a [UN-SPIDER Google Earth Engine (GEE) JavaScript Script](https://www.un-spider.org/advisory-support/recommended-practices/recommended-practice-google-earth-engine-flood-mapping/step-by-step) for flood mapping. It has been translated to Python, heavily adapted, and expanded. 
