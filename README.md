# Sentiment Analysis

Report link: <a href="https://app.powerbi.com/view?r=eyJrIjoiMDM1NmFhMTAtOWJiMC00ZWUyLTkyMWItYWVmNjNlMDFjOTU5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9" target="_blank">Link</a>


![emoji_satisfaction_meter](https://github.com/Ananyad7/Sentiment-Analysis/assets/164981636/1d591d9e-f28a-4197-acfc-1c0eb7e861a5)


# Tool used: Excel, Power BI, Python

Ever wonder how businesses know what their customers really think? Well, sentiment analysis is like having a direct line to customer feelings. It helps companies understand how satisfied customers are with their products and services. By listening closely to feedback and quickly addressing any concerns, businesses can build stronger bonds with their customers. It's not just about fixing problems though; sentiment analysis also guides how businesses talk to their customers. By speaking their language and tapping into what matters most to them, businesses can create marketing messages that really hit home. In short, sentiment analysis isn't just about data—it's about connecting with people and making their experiences better!!!!


# Dashboard Snapshot
![SA1](https://github.com/Ananyad7/Sentiment-Analysis/assets/164981636/80b50ff4-c75b-4f9d-9a03-eeece45bc7aa)


![image](https://github.com/Ananyad7/Sentiment-Analysis/assets/164981636/50479574-9f0f-42a6-8de3-883e84a1e9c7)

This dataset consists of 278,101 records of customer reviews about certain products. The data has been cleaned and sanitized for analysis. For sentiment analysis, Excel has been used, and Azure Machine Learning was employed to determine positive, negative, and neutral sentiments based on their respective scores. Review IDs without feedback were removed to streamline operations, which improved analysis efficiency by 80%.

![image](https://github.com/Ananyad7/Sentiment-Analysis/assets/164981636/332d9296-ce9a-407b-adc5-66df4c20358d)

Given the variability in feedback length, Python's Natural Language Toolkit (nltk) was used to accurately extract keywords and analyze data.
<a href="https://github.com/Ananyad7/Sentiment-Analysis/blob/main/Keywords_extraction.ipynb" target="_blank">Script Link</a>


![image](https://github.com/Ananyad7/Sentiment-Analysis/assets/164981636/3be7723f-479b-42ab-9141-433153656448)


# The analysis is divided into four parts:

Overall Customer Sentiment Analysis: Analyze the distribution of sentiment across customer feedback, identify trends in customer sentiment over years, and compare sentiment between the current year and previous year.

Geospatial Analysis of Customer Sentiment: Analyze store locations to understand where the highest and lowest average sentiment scores originate.

Temporal Analysis for Customer Sentiment: Analyze year-over-year and month-over-month trends in sentiment to gain deeper insights into customer sentiment dynamics.

Review Categorization and Analysis: Use keywords extracted to identify the most frequently mentioned topics in customer feedback and gain a better understanding of customer sentiments.

The most important KPIs used include Current Year vs Previous Year positive sentiment rate, negative sentiment rate, total number of sentiment record , and average review rating.


# Findings 
1. The total number of reviewers in the current year (2023) is 12.6k, representing an increase of almost 48% compared to the previous year. Among these reviewers, nearly 7.2k expressed positive sentiment towards the products, indicating a strong satisfaction level. However, 3.7k reviewers conveyed negative sentiment, which is a point of concern and highlights areas for potential improvement. From 2001 to 2023, customer sentiment has exhibited a rollercoaster trend, with significant fluctuations over the years. The highest sentiment was recorded in 2012, with 16.9k reviewers expressing their opinions. Despite the ups and downs, the overall trend from 2001 to 2023 indicates that customers have generally shown positive sentiment towards the products.
2. Throughout the year 2023, sentiment records showed fluctuations, with most months showing higher sentiment records than in 2022. However, sentiment records in February, April, September, and November were similar to those in 2022. Both years experienced an upward trend in sentiment, peaking in December. The end-of-year holiday season typically sees a surge in positive sentiment due to holiday promotions and increased customer purchases.
3. There are stores across 135 countries worldwide, with the highest number of sentiment records observed in the US, Canada, Australia, and the United Kingdom. The US holds the highest number of records at 10840  in 2023, making it crucial to monitor the sentiment trends of customers from this region.
4. From 2001 to 2023, sentiment records have shown significant fluctuations, with 2012 recording the highest sentiment at 16.9k. The year-on-year change reveals that the highest sentiment record occurred in 2014, showing a 117% increase compared to the previous year. Positive, negative, and neutral sentiments collectively increased by 50% compared to the previous year. The most substantial increases in negative and neutral sentiment were observed in 2012, while the most significant increase in positive sentiment occurred in 2014 compared to the previous year.
5. In the current year 2023, the highest increase in negative sentiment was observed in May, which is approximately 140% higher than the previous year. Similarly, the highest spikes in positive and neutral feedback were recorded in March.
6. From customer feedback in 2023, several repetitive keywords have been identified. Positive keywords like 'amazing,' 'quality,' 'product,' 'great,' and 'excellent' indicate a positive sentiment among customers. On the other hand, negative keywords such as 'accidentally,' 'wrong,' and 'issues' highlight areas of concern that need to be addressed.




# Recommendation
1. To improve customer satisfaction, it is crucial to enhance customer support by addressing common issues promptly, invest in product quality to meet customer expectations, and increase engagement with customers by responding to their reviews and showing that their opinions matter.
2. To ensure consistent customer satisfaction during the dips of 2023, monitor delivery and product quality closely. Timely address any issues related to delivery timeliness and product quality to maintain high customer satisfaction levels throughout fluctuations in sentiment.
3. Develop personalized marketing campaigns based on sentiment analysis results. Tailor promotions, messages, and offers to resonate with the sentiment expressed by customers from regions like the United States, Canada, Australia, and more.The results show that approximately 60% of the reviewers expressed positive sentiments towards the product, while around 30% showed negative sentiments in 2023. Some stores in regions like Iceland, Bulgaria, and Canada exhibited negative sentiment, whereas Finland and Bahrain showed positive sentiment. Since most reviewers are from the US and Canada, it is essential to focus on these regions to improve customer support strategies and adjust product offerings based on sentiment trends.
4. Implement targeted campaigns highlighting positive customer experiences and success stories. Enhance customer service interactions to focus on proactive problem-solving and personalized support.. Monitor customer feedback channels regularly to identify issues promptly. Implement robust feedback mechanisms to address concerns and improve service delivery.
5. Poor customer service experiences, delays in support resolution, and potential product defects or quality concerns could contribute to higher dissatisfaction. Regular monitoring of these aspects is crucial to maintain customer satisfaction and address issues promptly.
6. Focus on maintaining high standards for products customers frequently praise. Improve training and response times to address common issues related to 'wrong' or 'accidental' experiences.Clearly communicate product features and usage instructions to reduce misunderstandings.In the overall data, 278k sentiments were recorded, but approximately 13% of reviewers did not provide any feedback. Actively encourage customers to provide feedback as it plays a crucial role in sentiment analysis, helping to improve products and services based on customer experiences.

Linkedin link: https://www.linkedin.com/posts/7ananyadas_sentiment-analysis-and-trends-dashboard-activity-7211729449401085953-7Q3J?utm_source=share&utm_medium=member_desktop

icons:Flaticon
<a href="https://www.flaticon.com/free-icons/globe" title="globe icons">Globe icons created by srip - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/trend" title="trend icons">Trend icons created by Saepul Nahwan - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/feeling" title="feeling icons">Feeling icons created by bearicons - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/linkedin" title="linkedin icons">Linkedin icons created by riajulislam - Flaticon</a>

Image: <a href="https://www.freepik.com/free-vector/emoji-satisfaction-meter-small_44156211.htm#query=sentiment%20analysis&position=4&from_view=keyword&track=ais_user&uuid=b8137c23-ba84-4fb3-a9b8-9a18321d7c1a">Freepik</a>
