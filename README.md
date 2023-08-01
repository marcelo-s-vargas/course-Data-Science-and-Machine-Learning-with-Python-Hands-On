# course-Data-Science-and-Machine-Learning-with-Python-Hands-On
Repo with "Data Science and Machine Learning with Python – Hands-On!" course activities

Course material
https://learning.oreilly.com/videos/data-science-and/9781787127081/



Notes:


- **Covariance** measures how two variables vary in tandem from their means.
  - For example, let's say we work for an e-commerce company, and they are interested in finding a correlation between page speed (how fast each web page renders for a customer) and how much a customer spends.
  - Result
    - A positive value indicates that the two variables tend to increase or decrease together, meaning that when one of them is above its mean, the other is also above its mean, and vice versa. This indicates a direct relationship or a positive linear trend.
    - A negative value indicates that the two variables tend to vary in opposite directions, meaning that when one of them is above its mean, the other is below its mean, and vice versa. This indicates an inverse relationship or a negative linear trend.
    - A value close to zero indicates that there is no clear linear relationship between the two variables.
 - **Correlation** is a statistical measure that quantifies the relationship or association between two variables. It indicates the strength and direction of the linear relationship between the variables. Correlation is typically represented by the correlation coefficient, which can range from -1 to 1. The correlation coefficient measures both the strength and the direction of the relationship.
    * Results:
        * A correlation coefficient of +1 indicates a perfect positive correlation, meaning that the variables have a strong linear relationship in which an increase in one variable is associated with an exact proportional increase in the other variable.
        * A correlation coefficient of -1 indicates a perfect negative correlation, meaning that the variables have a strong linear relationship in which an increase in one variable is associated with a proportional decrease in the other variable.
        * A correlation coefficient of 0 indicates no linear relationship between the variables. However, it's important to note that this doesn't necessarily imply the absence of any relationship between the variables, as there could be a nonlinear relationship or other types of associations.
* **Correlation and covariance** are both statistical measures that describe the relationship between two variables, but **they have some key differences**:
    * **Scale:** Covariance is not standardized, meaning its value depends on the scale of the variables being measured. On the other hand, correlation is a standardized measure that ranges from -1 to 1, providing a normalized assessment of the relationship.
    * **Interpretability:** Due to its scale dependency, covariance is not as easily interpretable as correlation. Covariance values can range from negative infinity to positive infinity, making it difficult to compare or assess the strength of the relationship. Correlation, being standardized, provides a clear indication of the strength and direction of the relationship.
    * **Units:** Covariance is measured in the units obtained from multiplying the units of the two variables, which can make it challenging to compare covariances across different datasets or variables. Correlation, however, is a unitless measure, as it is based on standardized variables.
    * **Relationship Assessment:** Covariance measures both the strength and direction of the linear relationship between variables, similar to correlation. However, correlation focuses specifically on the strength and direction of the linear relationship and is particularly useful for detecting and quantifying linear associations. Covariance, being more general, can also capture nonlinear relationships between variables.
    * **Interpretation:** Correlation has a clear interpretation. A correlation coefficient of +1 indicates a perfect positive linear relationship, -1 indicates a perfect negative linear relationship, and 0 indicates no linear relationship. Covariance lacks a standard interpretation since its value depends on the scales and units of the variables.
    * **In summary**, correlation provides a standardized measure of the linear relationship between variables, making it easier to interpret and compare. Covariance, while capturing both linear and nonlinear relationships, lacks standardization and may be less interpretable without considering the specific scales and units of the variables.


* **Bayes' theorem** is a fundamental concept in probability theory and statistics. It describes how to update our beliefs or probabilities about an event based on new evidence or information.
    * Bayes' theorem is expressed as follows:
        * P(A|B) = (P(B|A) * P(A)) / P(B)
        * where:
        * P(A|B) is the conditional probability of A given B, which means the probability of A occurring given that B has occurred.
        * P(B|A) is the conditional probability of B given A, which means the probability of B occurring given that A has occurred.
        * P(A) is the probability of A occurring.
        * P(B) is the probability of B occurring.
        * In other words, Bayes' theorem allows us to calculate the probability of an event A occurring, taking into account evidence B. It relates the conditional probability of A given B to the conditional probability of B given A, along with the marginal probabilities of A and B.
    * Bayes' theorem is particularly useful when we want to update our prior probabilities or beliefs based on new information. It provides a formal framework for probability updating, incorporating both prior probabilities and observed evidence.
    * Bayes' theorem is widely applied in various fields such as statistics, machine learning, artificial intelligence, and data analysis. It is used in classification problems, spam filtering, medical diagnosis, pattern recognition, and much more. It plays a crucial role in statistical inference, enabling the updating of estimates based on new data.

* **Multiple Regression**
    * If you also have multiple dependent variables – things you’re trying to predict – that’s “multivariate regression”


* **Multi-Level Models**
    *  The concept is that some effects happen at various levels.
        * Example: your health depends on a hierarchy of the health of your cells, organs, you as a whole, your family, your city, and the world you live in.
    * https://link.springer.com/book/10.1007/978-3-642-17946-4
