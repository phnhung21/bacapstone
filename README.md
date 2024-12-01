# Telecom Customer Churn Predictor Analysis
## Nhung Pham
## Advising Professor: Illya Mowerman
## Fairfield University
## Fall 2024

# 1. Research Question & Data Acquisition
Primary Question: What factors are the most significant predictors of customer churn, and how can a predictive model be developed to identify customers at risk of leaving?

# 2. Introduction
In today’s competitive business landscape, customer churn remains a critical challenge that directly impacts profitability and sustainable growth. Retaining customers is not only more cost-effective than acquiring new ones, but it also plays a vital role in sustaining long-term growth. Studies have shown that even a small improvement in customer retention can lead to substantial financial gains, making it crucial for companies to identify customers who are likely to leave before it happens (Kotler & Keller, 2012). This is where predictive analytics comes into play - an analysis that can help businesses pinpoint churn risks and take action to keep their customers.

Over the years, researchers and businesses have used various approaches to tackle and explain this problem. For example, Oliver’s Expectancy-Disconfirmation Theory explains that customers who perceive a gap between expected and delivered service are more likely to leave. Meanwhile, Zeithaml’s Customer Lifetime Value framework underscores the economic benefits of retaining long-term customers rather than focusing solely on acquisition. These theories, developed and cited across various studies, underscore the complex interplay of psychological and economic factors driving churn (Zeithaml, 2000).

In the effort to mitigate churn and tackle the problem with accurate statistics, organizations also increasingly leverage predictive analytics to identify at-risk customers using historical data. Traditional approaches, such as logistic regression, have been widely used for their simplicity and interpretability, while machine learning methods like Random Forests and Gradient Boosting have demonstrated superior predictive accuracy. 

This research aims to build upon existing studies by developing a robust predictive model tailored to identifying high-risk customers. The paper is structured as follows: the subsequent section provides a review of relevant literature and existing methodologies. Second is the dataset and preparation techniques. Then, the modeling process, and evaluation result are presented, and the paper concludes with a discussion of the findings and business implications.

# 3. Literature Review
Customer churn prediction has become an essential area of study over time. Several studies have explored the methodologies and challenges associated with churn predictions, particularly in the telecommunication industry, where competition is intense, and customer retention is critical.

3.1. Review of Churn Prediction Techniques

Hasmi, Butt, and Iqbal (2013) conducted a decade-long review of customer churn prediction (CCP) methods from 2002 to 2013. Their analysis revealed that Decision Trees were the most widely used technique for churn prediction. However, the study highlighted several challenges, such as the high dimensionality of data, and class imbalance in churn datasets. Meanwhile, in their study on open datasets and CCP techniques, Umayaparvathi and Iyakutti (2016) compared several machine learning methods, including Decision Trees, Neural Networks, and Support Vector Machines (SVMs). Their results indicated that SVMs outperformed other methods due to their adaptability in distinguishing between churned and non-churned customers. Additionally, the study highlighted the importance of selecting the right performance metrics, such as precision, recall, and F1 scores, to evaluate model performance accurately.

Similarly, Monani (2016) conducted a comparative analysis of churn prediction metgods, with a focus on advanced techniques like Neural Networks. They found Neural Networks to be more effective techniques than traditional methods, especially for large datasets with non-linear relationships. More recently, machine learning (ML) techniques have gained prominence for churn prediction due to their ability to analyze complex datasets. Zhang et al. (2023) highlighted the superiority of ensemble models, such as Random Forest and Gradient Boosting Machines (e.g., XGBoost), in achieving higher predictive accuracy. These methods leverage multiple weak learners to improve classification performance, particularly for imbalanced datasets.

3.2. Key Drivers of Churn and Retention

Poor Service Quality (Adebiyi, 2016)
Lack of Customer Engagement and Inadequate Personalization ((Hashmi, 2013).
Pricing and Usage Factors (Monani, 2016).
Superior Competitors and Low Switching Costs ((Adebiyi, 2016).

3.3. Challenges and Gaps in Existing Research
While significant progress has been made, certain challenges persist:
Data Imbalance: The majority of churn datasets are heavily skewed, with far fewer churn cases than non-churn. Imbalanced datasets often lead to biased models unless addressed appropriately.
Feature Engineering Complexity: Despite the proven importance of engineered features, many studies lack detailed methodologies for replicating these processes.

3.4. Contribution of This Study
Building upon the foundation of prior research, this study aims to address the identified gaps by:
Incorporating advanced feature engineering techniques to capture nuanced customer behavior.
Utilizing machine learning algorithms, such as Gradient Boosting and Random Forest, to optimize predictive accuracy.
Ensuring interpretability through tools like SHAP, making the model outputs actionable for business stakeholders.




Citation

Adebiyi, S. O., Oyatoye, E. O., & Amole, B. B. (2016).
	Relevant drivers for customers’ churn and retention decision in the Nigerian mobile 
telecommunication industry. ResearchGate.
	https://www.researchgate.net/publication/309021595
Hashmi, N. K., Butt, W. H., & Iqbal, M. J. (2013).		
Customer churn prediction in telecommunication: A decade review and classification. ResearchGate.
https://www.researchgate.net/publication/257920014
Monani, D., Shukla, S., & Chauhan, A. (2016).
	Comparative analysis of customer churn prediction techniques: A survey. International Research 
Journal of Engineering and Technology, 3(4), 1168-1173.
	https://www.irjet.net/archives/V3/i4/IRJET-V3I4213.pdf
Zhang, M., Wu, J., & Zhou, X. (2023). Predictive models for customer churn: Exploring machine learning 
techniques and data challenges. Journal of Marketing Analytics, 11(2), 147–163. 
	https://doi.org/10.1057/s41270-023-00269-9 
Umayaparvathi, V., & Iyakutti, K. (2016).
A survey on customer churn prediction in telecom industry: Datasets, methods, and metrics. International Journal of Advanced Research in Computer Science and Software Engineering, 6(2), 50-55.
https://jati.sites.apiit.edu.my/files/2018/07/2018_Issue1_Paper2.pdf

