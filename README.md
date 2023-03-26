# Real Time Analytics

Unleash the power of real-time marketing with our exciting project! Our team simulated an RTM app on SingleStore, providing in-depth analysis and creative data engineering solutions. 

## Executive Summary

In this project, our team explored the potential of real-time marketing (RTM) by simulating an RTM application on the SingleStore platform. Our aim was to ingest data generated from the simulation, conduct in-depth analytics, and create insightful visualizations using Tableau. Our team meticulously go through the technical and business details and creatively use the knowledge we have learned so far to tackle the data engineering issues and business analysis problems. Our main contributions can be summarized as follows:

First of all, we did our best to make sure that all the data transformations and calculations align with real business logic. For example, not only did we exclude purchase records happening earlier than notification time, but also make sure the purchases records are not duplicated. To achieve this, we used ROW_NUMBER and RANK functions.

Secondly, we conduced a thorough analysis by designing KPIs that cover different angles, with both overviews and details. The visualizations are suitable for both CEOs making strategic decisions and business analysts doing daily work. The dashboards we created reveal a lot of critical information not only about the performance of the platform and of the vendors, but also about the way in which the subscribers are responding to the offers. Some of the more notable insights gained from these visualizations are the impressive percentage of subscribers that make a purchase after receiving a notification at nearly 15%, and the near 100% values for the subscriber retention rate and the vendor success rate, all of which leads us to believe that the platform is successful.

Lastly, we provided detailed feedback about the challenges we faced in the project and further research we can do based on our experience. This could be of great benefit not only for our own study purpose but also for the design of databases and simulation applications.

## Project Statement 

Real-time marketing (RTM) is a new approach that companies are adopting today to interact with their customers in real-time, based on data about how they engage with the company's product or service through multiple channels. It contrasts with traditional marketing approaches that require planning out a marketing strategy for months before implementation. Companies engage customers with short, personalized messages about product information, customer benefits, promotion details, etc., on their mobile phones, at the right time and location. This methodology often involves a sense of urgency, as customers realize that the advertisements they receive are tailored to current events or trends, and hence the offerings provided could be the most helpful in the present moment. As a result, real-time marketing is often a creative approach to attract more customers and boost engagement, leading to increased conversion rates at each stage of the sales funnel. To conduct effective real-time marketing, it is essential to develop a holistic and well-organized system of collection and processing of customer behavior data across multiple channels and try to respond to them over the channel they prefer.

In this project, we used the SingleStore platform to simulate an RTM application and conduct data analytics based on the real-time data we collect from the business process. For the business process, advertisements from multiple businesses (or vendors) are sent to customers via notifications on their cell phone, based on information about their behaviors and real-time locations. When more than one company's offers match a specific customer, there is a bidding process to decide on which company's offer to send as the final offer. 

## Full Report Attached in Repository 

Check the full reports for detailed analysis and insights.

