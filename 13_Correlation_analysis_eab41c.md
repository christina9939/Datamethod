# 6. Correlation analysis

Correlation analysis aims to discover the associations between different items in a data set. These association rules describe the patterns that occur in an event or set, indicating that given some conditions, other conditions may also occur. Common applications include shopping basket analysis, cross-selling, network traffic analysis, etc.
In correlation analysis, there are two key indicators:
• Support: measures the frequency of a rule in a data set. A high support indicates that the rule appears more frequently in the data set.
• Confidence: measures the credibility of the rule, that is, the probability that the result will appear when the condition occurs. A high confidence indicates that the rule is more reliable.
Classic algorithms for correlation analysis include:
• Apriori algorithm: based on the prior principle, gradually generates association rules from frequent item sets (a set of items that frequently appear in a data set).
• FP-growth algorithm: uses a data structure called "frequent pattern tree" to recursively decompose the data set to find frequent item sets.
Correlation analysis has been widely used in business and science. For example, in the retail industry, by analyzing customers' shopping baskets, merchants can develop more effective promotion strategies; in medical research, correlation analysis can help discover patterns of illness or side effects of drugs, etc.